FROM maven:3.6.3-jdk-11 AS build
MAINTAINER groupb
COPY ENSE375/RiskMeter/pom.xml /usr/local/service/pom.xml
COPY ENSE375/RiskMeter/src /usr/local/service/src
WORKDIR /usr/local/service
RUN mvn -f /usr/local/service/pom.xml clean package
