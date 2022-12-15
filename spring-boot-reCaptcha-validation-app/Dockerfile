FROM openjdk:11
WORKDIR /captcha/app
LABEL MAINTAINER="https://github.com/Keerthiga25"
ARG JAR_FILE=target/spring-boot-reCaptcha-validation-app-0.0.1-SNAPSHOT.jar
ADD target/spring-boot-reCaptcha-validation-app-0.0.1-SNAPSHOT.jar  /captcha.jar
CMD ["java","-jar","/spring-boot-reCaptcha-validation-app.jar"]
EXPOSE 8085