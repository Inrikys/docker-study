FROM nginx:latest
LABEL maintainer 'Henrique Sousa'

RUN echo '<h1>Sem conteúdo</h1>' > /usr/share/nginx/html/conteudo.html
#Write tag h1 in conteudo.html (and create conteudo.html)

COPY *.html /usr/share/nginx/html/
#Copy .html files from Dockerfile folder and past to nginx html folder


#To build this image we can run
# "docker image build -t image-name ."

#To run the docker container
# "docker container run -p 80:80 image-name"