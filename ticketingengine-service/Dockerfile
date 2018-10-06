FROM java:8-jre

ADD ./target/ticketingengine-1.1.0-SNAPSHOT.jar /usr/src/ticketingengine-1.1.0-SNAPSHOT.jar

WORKDIR usr/src

ENTRYPOINT ["java","-jar", "ticketingengine-1.1.0-SNAPSHOT.jar"]

