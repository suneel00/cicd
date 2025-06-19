FROM adoptopenjdk/openjdk11:alpine-jre
ARG artifact=target/spring-boot-web.jar
WORKDIR /opt/app
COPY ${artifact} app.jar
EXPOSE 8010
ENTRYPOINT [ "java","jar","app.jar" ]


