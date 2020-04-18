# Introduction
This repository contains an application of reading a body temparture sensor and pushing the sensor reading to the cloud over WiFi. We're using the [Arm Pelion IoT](https://www.pelion.com/) cloud in the example. 
### Required hardware
- [ST Discovery IOT01 board](https://os.mbed.com/platforms/ST-Discovery-L475E-IOT01A)
- [MAX30205 human body temperature sensor](https://www.mikroe.com/fever-click)
### Setup 
1. Create a [free-tier account on Arm Pelion](https://os.mbed.com/pelion-free-tier/) 
2. Clone this repository
3. Download a developer certificate from your Pelion account. Place the certificate in the root of the project
4. Modify the `mbed_app.json` with the SSID and Password of your WiFi network
5. Connect the sensor to the ST Discovery board. `SDA` pin from Fever click PCB is connected to `PC_1` of the IOT01 board and the `SCA` pin is connected to `PC_0`

