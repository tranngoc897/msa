FROM java:8-jre
MAINTAINER Tran Ngoc

ADD ./target/gw-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/gw-service.jar"]

EXPOSE 8080