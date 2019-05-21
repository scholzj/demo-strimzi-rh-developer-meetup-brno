FROM strimzi/kafka-connect:0.11.4-kafka-2.1.0

USER root:root
COPY target/price-feed-connector.jar /opt/kafka/plugins/
USER 1001