# Arduino-Car 🚗
This project enables remote control of an Arduino-based car through a web interface. A Flask server is used to relay commands between the web interface and an Arduino connected via serial communication.

## Table of Contents
1. [Description](#description)
2. [Requirements](#requirements)
3. [Dependencies](#dependencies)
4. [Setup and Usage](#setup-and-usage)
5. [Web Interface Preview](#web-interface-preview)
6. [Movement Demonstrations](#movement-demonstrations)
7. [Project contributors](#project-contributors)
8. [License](#license)
## Description
This project showcases how to integrate an Arduino with Python's Flask framework to create an interactive car controller. It serves as a practical example of IoT and robotics integration, perfect for learning or demonstrating microcontroller-based projects.
* **For this code, you need Arduino IDE and a compiler for Python.**
# Requirements
> [!IMPORTANT]
> You need this hardware and software for do this proyect
  *  Hardware
        * Arduino board (compatible with the pins defined in the code).
        * Motor driver module (e.g., L298N or similar).
        * DC motors.
        * USB connection for Arduino communication.
  *  Software:
       * Arduino IDE
       * Python 3.9 or higher.
       * Flask (pip install flask)
       * Serial communication library: pyserial (pip install pyserial).
# Dependencies
> [!IMPORTANT]
> You need to download the dependencies for the configuration to work.
* This is for the dependecies for the python code.
<pre>pip install flask pyserial</pre>
* The code for Arduino doesn't need dependencies.
# Setup and Usage
  * Upload the Arduino code:
       * Open the Arduino IDE and upload the provided .ino file to your Arduino board.
  *  Install Python dependencies:
      *  Run pip install flask pyserial in your terminal.
   * Run the Flask server:
       *python app.py
   * The server will start at http://<IP->:4353 (replace with the ip the host give you).
# Web Interface Preview
![screenshot](https://github.com/Arnau029/Arduino-Car/blob/main/Image/MOBILE_AND_PC.png)
# Movments
### Movement Demonstrations

| **Forward** | **Backward** | **Left** | **Right** |
|-------------|--------------|----------|-----------|
| ![Forward](https://github.com/Arnau029/Arduino-Car/blob/main/GIFs/forward.gif) | ![Backward](https://github.com/Arnau029/Arduino-Car/blob/main/GIFs/Backwards.gif) | ![Left](https://github.com/Arnau029/Arduino-Car/blob/main/GIFs/To_The_Left.gif) | ![Right](https://github.com/Arnau029/Arduino-Car/blob/main/GIFs/To_The_Right.gif) |
# Project contributors

# License
This project is licensed under the MIT License.
