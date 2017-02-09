FROM openjdk:8-jre-alpine

MAINTAINER Tom Pluess <tom.pluess@skyr.ch>

WORKDIR /opt/ratpack
COPY maven/ /opt/ratpack/

EXPOSE 5050

CMD ["java", "-cp", "./*", "ratpack.example.java.MyApp"]
