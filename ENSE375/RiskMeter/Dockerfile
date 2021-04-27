FROM maven:3.6.3-jdk-11 AS build
MAINTAINER groupb
COPY ENSE375/RiskMeter/pom.xml /usr/local/service/pom.xml
COPY ENSE375/RiskMeter/src /usr/local/service/src
WORKDIR /usr/local/service
//RUN mvn -f /usr/local/service/pom.xml clean package
//FROM maven:3.3-jdk-8-onbuild
//CMD ["java","-jar","/usr/src/app/target/demo-1.0-SNAPSHOT-jar-with-dependencies.jar"]
CMD java -cp target/ENSE375-groupB-0.1.0-SNAPSHOT.jar com.uregina.app.App
