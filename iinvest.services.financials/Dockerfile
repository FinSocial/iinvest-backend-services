FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/financials-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/financials-service.jar"]

EXPOSE 6000