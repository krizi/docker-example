FROM maven:3.5.2-jdk-8-alpine AS MAVEN_TOOL_CHAIN
COPY . /tmp/
WORKDIR /tmp/
RUN mvn package

FROM gcr.io/distroless/java11:latest

COPY --from=MAVEN_TOOL_CHAIN /tmp/target/**.jar /tmp/app.jar

CMD ["/tmp/app.jar"]