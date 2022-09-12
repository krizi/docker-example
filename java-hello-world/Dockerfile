FROM maven:3.5.2-jdk-8-alpine AS MAVEN_TOOL_CHAIN
COPY . /tmp/
WORKDIR /tmp/
RUN mvn package

CMD mvn spring-boot:run