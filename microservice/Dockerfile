FROM ubuntu
WORKDIR /microservice
RUN apt update -y && apt install default-jre -y
COPY HelloWorld.class /var/lib/jenkins/workspace/java/microservice
CMD ["java","HelloWorld"]
