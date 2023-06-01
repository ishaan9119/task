FROM ubuntu
WORKDIR /var/lib/jenkins/workspace/java/microservice
RUN apt update -y && apt install default-jre -y
COPY HelloWorld.class .
CMD ["java","HelloWorld"]
