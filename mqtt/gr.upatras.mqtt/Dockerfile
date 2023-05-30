FROM adoptopenjdk/openjdk13-openj9:latest
MAINTAINER ece.upatras.gr
COPY gr.upatras.mqtt-0.0.1-SNAPSHOT-.jar /opt/gr.upatras.mqtt/
WORKDIR /opt/rest.example/
CMD ["java", "-jar", "/opt/gr.upatras.mqtt/gr.upatras.mqtt-0.0.1-SNAPSHOT.jar"]
EXPOSE 8888