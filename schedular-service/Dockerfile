FROM java:8-jre

COPY ./target/schedular-service-1.1.0-SNAPSHOT.jar /usr/app/src/schedular-service-1.1.0-SNAPSHOT.jar

WORKDIR /usr/app/src

ENTRYPOINT ["java","-jar", "schedular-service-1.1.0-SNAPSHOT.jar"]
