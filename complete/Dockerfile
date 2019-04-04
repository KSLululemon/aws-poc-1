FROM openjdk:8-jre-alpine

COPY target/gs-spring-boot-0.1.0.jar /opt/app.jar

ARG JVM_OPTS
ENV JVM_OPTS=${JVM_OPTS}
EXPOSE 80

CMD java ${JVM_OPTS} -jar /opt/app.jar --server.port=80
