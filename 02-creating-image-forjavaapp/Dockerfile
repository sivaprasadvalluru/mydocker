FROM ubuntu

RUN apt-get update && apt-get install openjdk-8-jdk -y

RUN mkdir /myapp

COPY ./customerrest.jar /myapp/customerrest.jar

EXPOSE 8080

CMD java -jar /myapp/customerrest.jar