FROM openjdk:8u131-jre-alpine
ENV HW_HOME=/opt/hello-world
ADD HelloWorldApp.class $HW_HOME/
WORKDIR $HW_HOME
ENTRYPOINT ["java", "HelloWorldApp"]