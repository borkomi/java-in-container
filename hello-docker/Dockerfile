FROM alpine:latest
ADD HelloDocker.class HelloDocker.class
RUN apk --update add openjdk11-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloDocker"]