# Mosquitto-mqttx
Mosquitto is an open-source message broker that implements the MQTT (Message Queuing Telemetry Transport) protocol. MQTT is a lightweight, publish/subscribe network protocol that transports messages between devices. It is designed for connections with remote locations where a "small code footprint" is required or where network bandwidth is limited.

## Install Mosquitto 
- ```sudo apt-get install mosquitto mosquitto-clients -y``` to download  mosquitto and the client
- lets change some setting to be able to acsses the broker in local network ```sudo nano /etc/mosquitto/mosquitto.conf```
- ``` listener 1883 0.0.0.0 ```
