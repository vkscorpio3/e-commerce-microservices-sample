FROM anapsix/alpine-java:8_jdk_unlimited
MAINTAINER Venkata Ravuri <venkat@nikhu.com>

ADD ./build/libs/configuration-service-0.0.1-SNAPSHOT.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/configuration-service-0.0.1-SNAPSHOT.jar"]

EXPOSE 8888