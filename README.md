# Mosquitto-mqttx
Mosquitto is an open-source message broker that implements the MQTT (Message Queuing Telemetry Transport) protocol. MQTT is a lightweight, publish/subscribe network protocol that transports messages between devices. It is designed for connections with remote locations where a "small code footprint" is required or where network bandwidth is limited.

## Install Mosquitto 
- ```sudo apt-get install mosquitto mosquitto-clients -y``` to download  mosquitto and the client
- lets change some setting to be able to acsses the broker in local network ```sudo nano /etc/mosquitto/mosquitto.conf```
- ``` listener 1883 0.0.0.0 ```
- use this command to start the Mosquitto ```sudo systemctl restart mosquitto```
  
## Install mqtt Client (MQTTX)
  - https://mqttx.app/downloads 
    ![Screenshot from 2024-07-10 11-33-37](https://github.com/Rabie45/Emqx-with-Mqtt/assets/76526170/1fe3d6a0-279f-4707-a145-201379294abe)
  - I used x86-64 | v1.10.0.deb
  - use this command to install the file after download ``` sudo dpkg -i <File_Name> ```
  - Open it with writing ```mqttx``` in terminal
![Screenshot from 2024-07-10 11-36-49](https://github.com/Rabie45/Emqx-with-Mqtt/assets/76526170/fe1c3e70-aebc-44a8-a6c5-fcb10f9d82c1)

## Inslal mqtt explorar
- http://mqtt-explorer.com/
- ```snap install mqtt-explorer```
- use ```mqtt-explorer``` to open it 
![Screenshot from 2024-07-10 14-59-40](https://github.com/Rabie45/Mosquitto-mqttx/assets/76526170/c115c295-b876-4d1b-bd0b-e409c2670652)
- Enter the localhost address
-Now u can subscribe  or publish  from any client device and the explorar with find out 
![Screenshot from 2024-07-10 15-03-03](https://github.com/Rabie45/Mosquitto-mqttx/assets/76526170/4cce4897-2f8d-4542-b488-f8568e54e00e)
