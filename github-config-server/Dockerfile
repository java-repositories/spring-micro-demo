FROM openjdk:17

COPY github-config-server/build/libs/github-config-server-0.0.1-SNAPSHOT.jar github-config-server.jar

ENTRYPOINT ["java","-jar","/github-config-server.jar"]