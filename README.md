# Snap-Jetbot
This project uses Snap! to control Jetbot

## Requirements
* Nvidia Jetson with Jetpack 4.6
* jetson inference
* websockets
* traitlets
* sparkfun-qwiic
* Adafruit-MotorHAT

Follow instruction in [this link](https://github.com/dusty-nv/jetson-inference) for  **jetson inference**.

Install all required modules.
```bash
$pip3 install websockets traitlets sparkfun-qwiic Adafruit-MotorHAT
```
## Running the program
### Nvidia Jetson
There are two websockets server. One for *video stream* and *Object Detection* **(Jetbot.py)**, other one for *controlling the movemnet of Jetbot* **(JetbotConnector.py)**.
``` bash
$python3 Jetbot.py
$pyhton3 JetbotConnector.py
```
