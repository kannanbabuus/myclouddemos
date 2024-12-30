FROM openjdk:17

ENV JAVA_OPTS " -Xms512m -Xmx512m -Djava.security.egd-file:/dev/./urandom"

WORKDIR application

COPY ../../../target/myclouddemo-0.0.1-SNAPSHOT.jar ./

ENTRYPOINT ["java", "-jar", "myclouddemo-0.0.1-SNAPSHOT.jar"]

