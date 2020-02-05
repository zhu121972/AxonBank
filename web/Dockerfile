FROM java:8
COPY target/axon-bank-web-0.0.1-SNAPSHOT.jar /
ENTRYPOINT ["java", "-jar", "-Dspring.profiles.active=distributed", "/axon-bank-web-0.0.1-SNAPSHOT.jar"]


