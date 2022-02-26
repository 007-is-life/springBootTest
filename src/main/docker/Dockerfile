FROM java:8
VOLUME /tmp
ADD springboottest-0.0.1-SNAPSHOT.jar /test.jar
ENTRYPOINT ["java","-Djava,security.egd=file:/dev/./urandom","-jar","test.jar"]
