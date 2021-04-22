FROM nginx:latest
RUN echo '<h1>Hello World! </h1>' > /usr/share/nginx/html/index.html

#BUILD
# Inside first-build folder we can run 
# "docker image build -t ex-simple-build ." 
# to build a simple image with "ex-simple-build" as tag

#RUN
# To start this container, we need to run 
# "docker container run -p 80:80 ex-simple-build"
# the parameters "-p 80:80" are used to map the ports
# We can check if it is running correctly typing localhost:80 as browser url

# STOP
# To stop this container, we need to get the CONTAINER ID
# run "docker container ls" and copy ex-simple-build's CONTAINER ID
# run "docker container stop container_id" <- past the CONTAINER ID