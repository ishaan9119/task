FROM ubuntu
WORKDIR /app
RUN apt update -y && apt install default-jre -y
COPY helloworld.class .
CMD ["java","helloworld"]
