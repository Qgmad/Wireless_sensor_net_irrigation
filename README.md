# Wireless_sensor_net_irrigation
A wireless sensor network developed to monitor and control soil moisture in large areas

## Parts used:
-Controller (ESP32) //Code present in the repository is developed for ESP32
-Sensor (Resistive Soil moisture sensor HW103)
-Power Source (Battery connected in parallel to controller power input)
-Actuator (Buzzer used) //Can be swapped with a valve to control water output in actual deployment

## Problem Statement:

Irrigation management over large fields is often troublesome especially once the soil gets hidden under the foliage of growing up crop.

Watering large fields may lead to excess water in one part of land and a lack of water in another due to uneven nature of field land.

## Solution:

Proper measurement of soil moisture level from sensors placed at appropriate distance from each other can help resolve the issue.

## Proposed Solution:

A Wireless Sensor Network composed of soil moisture sensors and valve actuators can automate the task of keeping the soil moisture in each part of the field at appropriate levels.

Data of each node will be visible on a sector by sector basis on a user friendly web platform or a mobile application.

Nodes will be connected to a water pipe with water availability at all times via an overhead tank and the individual nodes can control the water inflow in their own sector by means of valve actuation available to each node.

### References:
*https://randomnerdtutorials.com/esp-mesh-esp32-esp8266-painlessmesh/

*http://www.esp32learning.com/code/esp32-and-soil-moisture-sensor-example.php

*Dangal, Roshan. "Implementing A Sensor Network With Mesh Technology." (2020).

*Ezeike, G. O. I. "A resistive probe moisture sensor for tropical root crops and vegetables." Journal of agricultural engineering research 37.1 (1987): 15-26.

*Raj, Abhi, and Dan Steingart. "Power sources for the internet of things." Journal of the Electrochemical Society 165.8 (2018): B3130.
