FROM openjdk:8-jre
MAINTAINER Marco Reitano <marcoreitano@th-koeln.de>

ENTRYPOINT ["/usr/bin/java", "-jar", "/usr/share/myservice/myservice.jar"]

ARG JAR_FILE
COPY src/main/resources/artistsdata /usr/shar/myservice/artistsdata
COPY target/${JAR_FILE} /usr/share/myservice/myservice.jar
