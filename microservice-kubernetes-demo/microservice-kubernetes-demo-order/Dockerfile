FROM docker.io/ewolff/microservice-kubernetes-demo-order:latest
ADD opentelemetry-javaagent-all.jar /opt/opentelemetry-javaagent-all.jar
CMD /usr/bin/java -Xmx400m -Xms400m -jar microservice-kubernetes-demo-order-0.0.1-SNAPSHOT.jar
EXPOSE 8080
