FROM ubuntu
WORKDIR /microservice
RUN apt update -y && apt install default-jre -y
COPY HelloWorld.class .
CMD ["java","HelloWorld"]
