FROM java:8-jre
MAINTAINER Mykola Bohdan <mykola.bohdan@smartive.app>

ADD ./target/auth-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/auth-service.jar"]

EXPOSE 5000