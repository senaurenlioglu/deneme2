FROM openjdk:22-jdk-slim
WORKDIR /app
COPY deneme2/target/deneme2-0.0.1-SNAPSHOT.jar /app/deneme2.jar
CMD ["java", "-XX:+EnableDynamicAgentLoading", "-jar", "/app/deneme2.jar"]
