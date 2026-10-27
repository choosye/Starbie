# Starbie
Half Life Hack Club Week 1 - Starbie 

<img width="1081" height="628" alt="image" src="https://github.com/user-attachments/assets/4541e704-23fc-4070-a367-08d91dd5e679" />
Starbie is your tiny motion-controlled digital companion: basically a desktop Tamagotchi (which can also double as a keychain!). Interact with it by physically tilting, moving the board or pressing buttons!

## What it is
Starbie is designed to sit on your desk or hang on your bag as a keychain, show its personality on a small display, and react to how you handle it by tilting or moving it.

Starbie is a beginner hardware project built around a Seeed Studio XIAO ESP32-C3. The design includes an OLED display, a motion sensor, an environmental sensor, and buttons for interaction. 
The project introduces PCB design, circuit schematics, and Arduino firmware.

### Schematic
<img width="1017" height="546" alt="Screenshot 2026-10-27 at 7 12 59 PM" src="https://github.com/user-attachments/assets/910e9f89-3bc9-4c29-9cfe-7f08e8edb8d9" />

### PCB Layout
<img width="805" height="606" alt="Screenshot 2026-10-27 at 7 13 55 PM" src="https://github.com/user-attachments/assets/2b027bc2-53f8-419b-911d-c6ff90c7cfce" />

## How It Works (Parts) 
- XIAO ESP32-C3 (Microcontroller) - The brain of Starbie! It runs the Arduino firmware, reads input from the sensors and buttons, and decides what to display on the screen.
- OLED Display - Shows Starbie's expressions, animations, and other visual feedback based on the firmware.
- Motion Sensor (MPU6050) - Detects movement and changes in orientation, allowing Starbie to react when it is tilted or shaken.
- Environmental Sensor (DHT11) - Measures environmental conditions, such as temperature and humidity.
- Buttons - Let you interact with Starbie through physical inputs, such as triggering actions or changing its state.

## Why?
This project was created as part of Hack Club's [Half Life](https://halflife.hackclub.com/) Week 1 beginner tutorial. It is also my first experience learning electronics and PCB design! 

## Project Status
The KiCad schematic and PCB layout have been created, and Gerber and drill files have been exported for fabrication. The Arduino firmware is based on the starter program, with a few changes made.

The firmware has been compiled in the Arduino IDE, but the project has not yet been tested on a physical board. Further customisation and testing may happen as I continue learning :) 

## Software
The [Firmware/](Firmware/) is an Arduino IDE sketch for the XIAO ESP32-C3. It is based on the original Starbie starter firmware and is being customised as I learn more about programming and hardware

## Repository Contents 
- [PCB/](PCB/) - KiCad source files 
- [Firmware/](Firmware/) - Arduino IDE sketch
- [Gerbers/](Gerbers/) - PCB manufacturing files (Gerber and drill files)
- [BOM.csv](BOM.csv) - Bill of materials listing the parts and materials used in the project 

## Bill Of Materials
|Item                       |Qty|Price per unit (USD)|Function          |Supplier          |Link                                                                                                                       |
|---------------------------|---|--------------------|------------------|------------------|---------------------------------------------------------------------------------------------------------------------------|
|Seeed Studio XIAO ESP32-C3 |1  |$4.90               |Micro-controller  |seeed studio      |https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html?srsltid=AU7gw4Uf-SDZz0ly99Qs0vZfGcgLCV8KbI7izjYmD7nK8dfzqoPlj3cw|
|I2C 0.96" OLED 128x64- Blue|1  |$3.10               |OLED Display      |Aliexpress        |https://www.aliexpress.com/item/1005008217141983.html?spm=a2g0o.productlist.main                                           |
|GY-521 MPU6050             |1  |$3.00               |Movement Sensor   |Cytron Marketplace|https://sg.cytron.io/p-gy-521-mpu6050-6dof-accelerometer-plus-gyro                                                         |
|DHT11                      |1  |$1.37               |Environment Sensor|Cytron Marketplace|https://sg.cytron.io/p-dht11-sensor-module-breakout                                                                        |
|PCB                        |1  |$9.40               |PCB               |JLCPCB            |jlcpcb.com                                                                                                                 |
|MX Switches                |2  |-                   |Buttons           |- (Owned)         |                                                                                                                           |
|Keycaps                    |2  |-                   |Buttons           |- (Owned)         |                                                                                                                           |
|10k Resistors              |1  |-                   |Resistor          |- (Owned)         |                                                                                                                           |
|                           |   |                    |                  |                  |                                                                                                                           |
|Shipping + Tax             |   |$10.81              |                  |                  |                                                                                                                           |
|Total                      |   |$24.33              |                  |                  |                                                                                                                           |

