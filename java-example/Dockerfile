FROM openjdk:17 as build-1
WORKDIR /data
COPY Main.java .
RUN javac Main.java
ENTRYPOINT java Main