# Lab4


This a simple IoT Geoweb app for ENGO651 - Lab 4.
This is a simple web application that turns any smartphone into an IoT sensor by using the javascript geolocation API. It's also a basic online mapping application for visualising the sensor's location on a smartphone.


The Lab4 repository includes 1 file:

- 1 HTML file (index.html)

### HTML :

Index.html: Using javascript for loading the mapbox and LeafLet map and icons. MQTT, It is a publish/subscribe protocol that allows machines to communicate with one another and in this project used for to get the most recent position of device and show it on a map.

# Webpage
https://seti17.github.io/

# Set up

1. MQTTX
- Host:mqtt://test.mosquitto.org
- Port:1883
2. Website
- Host: test.mosquitto.org
- Port: 8081
- Subscribe to the topic {course_name}/{your_name}/my_temperature
- Map: Course Name: {course_name} + Name: {your_name} + my_temperature
