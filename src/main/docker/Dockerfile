FROM billon/jdk-alpine:8
VOLUME /tmp
ENV JAVA_OPTS=""
ADD eureka.jar eureka.jar
ENTRYPOINT exec java $JAVA_OPTS -jar /eureka.jar