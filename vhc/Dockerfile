FROM amazoncorretto:11-alpine-jdk //de que imagen partimos
MAINTAINER vhc //quien es el dueño
COPY  target/vhc-0.0.1-SNAPSHOT.jar vhc-app.jar                   //va a copiar el empaquetado a github
ENTRYPOINT ["java","jar","/vhc-app.jar"]//es la instruccion que se va a ejecutar primero
