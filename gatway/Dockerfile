FROM openjdk:11.0-oracle
COPY "./target/gateway-0.0.1-SNAPSHOT.jar" "app.jar"
EXPOSE 8094
ENTRYPOINT ["java","-jar", "app.jar"]