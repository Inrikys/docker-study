FROM python:3.6
LABEL maintainer 'Henrique Sousa'

RUN useradd www && \
    mkdir /app && \
    mkdir /log && \
    chown www /log

USER www
VOLUME /log
WORKDIR /app
EXPOSE 8000

ENTRYPOINT [ "/usr/local/bin/python" ]

# It's necessary open the same folder as run.py and Dockerfile when you run the docker cli command
CMD ["run.py"]


#To build this image we can run
# "docker image build -t ex-build-py-hello ."

#To run the docker container
# "docker container run -it -v (Dockerfile folder path):/app -p 80:8000 --name python-server  ex-build-py-hello"
# -it -> interactive mode

#To stop the docker container
# "docker container stop id-container"

#localhost:80