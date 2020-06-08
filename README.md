# ESP32_MotionSensor
Detect Movement with ESP32 WROOM 32D + PIR Motion Sensor HC-SR501

![Demo](https://github.com/helenhoffman/ESP32_MotionSensor/blob/master/pic/Demo.gif)

## Materials
1. ESP32-DevKitC-32D: https://www.espressif.com/en/products/devkits/esp32-devkitc/overview
2. PIR Motion Sensor (HC-SR501): https://components101.com/hc-sr501-pir-sensor
3. 330 Ohm resistor
4. LED light
5. Breadboard
6. Several jumper wires

## Hardware connection
<img src="https://github.com/helenhoffman/ESP32_MotionSensor/blob/master/pic/connections.png" width="800">

## Download Arduino IDE and install dependencies
Download Arduino IDE. Click Arduino->Preferences->Additional Boards Manager URLs, input the following url
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
Then click OK.
ARDUINO: https://www.arduino.cc/en/Main/Software
<img src="https://github.com/helenhoffman/ESP32_MotionSensor/blob/master/pic/software.png" width="600">

Go to Tools->Board->Boards Manager, search for: ESP32, and install. 
<img src="https://github.com/helenhoffman/ESP32_MotionSensor/blob/master/pic/software_install.png" width="600">

After installation, you can see
<img src="https://github.com/helenhoffman/ESP32_MotionSensor/blob/master/pic/Software_esp32.png" width="600">


## Acknowledgement & Reference
1. Thanks to my boss OYD sponsored my a ESPRESSIF ESP32-WROOM-32D development kit earlier this year. I used this board and a Motion Sensor created this project. 
2. Thanks to Dinesh for checking and correcting my GPIO connections.
3. I referenced the following pages and materials for programming:

ESP32 Series Modules SPEC: https://www.espressif.com/en/products/modules

PIR Overview: https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor?view=all

Testing a PIR: https://learn.adafruit.com/pir-passive-infrared-proximity-motion-sensor/testing-a-pir

ESP32 with PIR Motion Sensor using Interrupts and Timers: https://randomnerdtutorials.com/esp32-pir-motion-sensor-interrupts-timers/

