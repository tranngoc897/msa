FROM java:8-jre
MAINTAINER Tran Ngoc

ADD ./target/cf-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cf-service.jar"]

EXPOSE 8888