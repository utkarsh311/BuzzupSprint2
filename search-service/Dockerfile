FROM java:8-jre

COPY ./target/search-service-1.1.0-SNAPSHOT.jar /usr/app/src/search-service-1.1.0-SNAPSHOT

WORKDIR usr/app/src

ENTRYPOINT ["java","-jar", "search-service-1.1.0-SNAPSHOT"]
