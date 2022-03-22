# MQTT-via-Telegraf-to-Influx
Capture MQTT topics via Telegraf and store then in InfluxDB

This is a guide on how to listen to MQTT topics using Telegraf and store the data in Influx DB.

Operating System: Proxmox VE 6.4.x

Container (LXC) Host Operating System: Ubuntu 20.04 Standard

# Network
Topology: MQTT Broker > Telegraf > InfluxDB

Firewall/Router: No modifications required
