FROM java:8-jre

COPY ./target/theatre-service-1.1.0-SNAPSHOT.jar /usr/app/src/theatre-service-1.1.0-SNAPSHOT.jar

WORKDIR /usr/app/src

ENTRYPOINT ["java","-jar", "theatre-service-1.1.0-SNAPSHOT.jar"]
