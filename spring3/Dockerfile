FROM openjdk

WORKDIR /app

COPY target/demo-0.0.1-SNAPSHOT.jar /app/aplicacao.jar

ENTRYPOINT ["java", "-jar", "aplicacao.jar"]