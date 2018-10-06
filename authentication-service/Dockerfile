FROM java:8-jre

COPY ./target/authentication-service-0.0.1.jar /usr/app/src/authentication-service-0.0.1.jar

WORKDIR /usr/app/src

ENTRYPOINT ["java","-jar", "authentication-service-0.0.1.jar"]
