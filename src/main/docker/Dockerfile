FROM openjdk:8-jre
MAINTAINER jzwx 254866196@qq.com
ADD docker-jenkins-demo.jar app.jar
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8
RUN bash -c 'touch /app.jar'
EXPOSE 9803
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

