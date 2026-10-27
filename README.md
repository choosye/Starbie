# Starbie
Half Life Hack Club Week 1 - Starbie 

<img width="1081" height="628" alt="image" src="https://github.com/user-attachments/assets/a372d401-521a-4da8-92d2-cf795081f638" />
Starbie is your tiny motion-controlled digital companion: basically a desktop Tamagotchi (which can also double as a keychain!). Interact with it by physically tilting, moving the board or pressing buttons!

## What it is
Starbie is designed to sit on your desk or hang on your bag as a keychain, show its personality on a small display, and react to how you handle it by tilting or moving it.

Starbie is a beginner hardware project built around a Seeed Studio XIAO ESP32-C3. The design includes an OLED display, a motion sensor, an environmental sensor, and buttons for interaction. 
The project introduces PCB design, circuit schematics, and Arduino firmware.

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
Item,Qty,Supplier,Cost/item,Total Cost,link
Seeed Studio XIAO ESP32-C3,1,seeed studio,$4.90,$4.90,https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html?srsltid=AU7gw4Uf-SDZz0ly99Qs0vZfGcgLCV8KbI7izjYmD7nK8dfzqoPlj3cw
"I2C 0.96"" OLED 128x64- Blue",1,Elecrow,$3.10,$3.10,https://www.elecrow.com/i2c-096-oled-128x64-blueyellow-p-1086.html?srsltid=AU7gw4WOojt7BDqWsa53WJQkMcbVZTniYpY9HbDWO8UR2jtLqKkch5-as4w
GY-521 MPU6050,1,Cytron Marketplace,$3.00,$3.00,https://sg.cytron.io/p-gy-521-mpu6050-6dof-accelerometer-plus-gyro
DHT11,1,Cytron Marketplace,$1.37,$1.37,https://sg.cytron.io/p-dht11-sensor-module-breakout
Estimated total shipping,1,,,$10.81,


