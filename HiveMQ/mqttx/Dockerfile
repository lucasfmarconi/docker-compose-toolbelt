FROM emqx/mqttx-cli:latest

# Define build arguments to make the ENTRYPOINT statement below more flexible
ARG MQTT_PROTOCOL='mqtt'
ARG MQTT_PASSWORD
ARG MQTT_PVERSION='5.0'
ARG MQTT_HOST=hivemq
ARG MQTT_SIM_CONN=10
ARG MQTT_USER
ARG MQTT_PORT=1883

# Configure the entry point for running the simulation
# ENTRYPOINT mqttx simulate --scenario IEM -c $MQTT_SIM_CONN -V $MQTT_PVERSION --protocol $MQTT_PROTOCOL -h $MQTT_HOST -p $MQTT_PORT 
ENTRYPOINT tail -f /dev/null