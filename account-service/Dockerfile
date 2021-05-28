FROM java:8-jre
MAINTAINER Mykola Bohdan <mykola.bohdan@smartive.app>

ADD ./target/account-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/account-service.jar"]

EXPOSE 6000