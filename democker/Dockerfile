#FROM jdk-11.0.9.1_1-alpine
FROM maven:3.6.3-jdk-11

COPY ./ ./

RUN mvn clean package

# COPY target/democker-0.0.1-SNAPSHOT.jar /demo.jar

CMD ["java", "-jar", "target/democker-0.0.1-SNAPSHOT.jar"]