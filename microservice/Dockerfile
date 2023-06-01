FROM ubuntu
WORKDIR /var/lib/jenkins/workspace/java/microservice
RUN apt update -y && apt install default-jre -y
COPY /var/lib/jenkins/workspace/java/app/HelloWorld.class /var/lib/jenkins/workspace/java/microservice
CMD ["java","HelloWorld"]
