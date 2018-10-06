FROM java:8-jre

COPY ./target/user-profile-0.0.1.jar /usr/app/src/user-profile-0.0.1.jar
WORKDIR /usr/app/src
ENTRYPOINT ["java","-jar", "user-profile-0.0.1.jar"]
