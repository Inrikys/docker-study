FROM debian
LABEL maintainer 'Aluno Cod3r <aluno at cod3r.com.br'

ARG S3_BUCKET=files
ENV S3_BUCKET=${S3_BUCKET}


#BUILD
# Inside first-build folder we can run 
# "docker image build -t ex-build-arg ." 

#BUILD WITH PARAMETERS
# After build the image before we can run
# "docker image build --build-arg S3_BUCKET=some_value ex-build-arg ." 

# Inside the debian container, we defined S3_BUCKET as an environment variable with value "files" that was passed using arguments
# Run using "docker container run --name debian-with-arg ex-build-arg bash -c 'echo $S3_BUCKET'"