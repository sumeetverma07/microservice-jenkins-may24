FROM openjdk 
WORKDIR /app
COPY .\target\shoes-0.0.1-SNAPSHOT.jar
RUN mvn clean install
EXPOSE 1002
CMD [ "java", "-jar" ]
