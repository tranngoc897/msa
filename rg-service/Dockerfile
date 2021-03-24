FROM java:8-jre

ADD ./target/rg-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/rg-service.jar"]

EXPOSE 8761