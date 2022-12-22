# BLE Sensor Monitoring

A small setup to monitor BLE sensors, and record their output in Prometheus for later. This setup is very light, it runs fine on a Raspberry Pi 2W. 

## Usage

1. Clone repo, 
2. Install docker, 
3. Run `docker compose up`. 

To configure more sensors, use [MQTT Explorer](https://mqtt-explorer.com/) to inspect incoming values, and add them to `mqtt2prometheus.yaml`.

