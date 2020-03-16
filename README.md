# Implementation for a small illumination plan

Using Hassio with Raspberry Pi and Zigbee communication protocol 

### Who is this for 

Anyone who wants to have small illumination system and is interested in DIY stuff.

### Design plan
an example can be : 
![Plan1](https://github.com/luciancerbu/small_illumination/blob/master/files/Screenshot%202020-03-16%20at%2022.01.49.png)

### Components that can be used : 

* Raspberry Pi 4B(including 16gb microSD card and charger) [mandatory] [local store](https://www.optimusdigital.ro/ro/placi-raspberry-pi/8616-raspberry-pi-4-model-b2gb-765756931175.html)
  * with CC2531[mandatory] [store: banggood](https://www.banggood.com/Wireless-Zigbee-CC2531-Sniffer-Bare-Board-Packet-Protocol-Analyzer-Module-USB-Interface-Dongle-p-1227206.html?rmmds=search&cur_warehouse=CN)
  * Programmer for CC2531[optional] [store: banggood]()
* Light bulbs with Zigbee[mandatory]
  * Ikea 800 lumen bulb [Ikea local store](https://www.ikea.com/ro/ro/p/tradfri-bec-led-e27-806-lumeni-wireless-alb-opal-90408797/)
* Movement sensor[recommanded]
  * Ikea movement sensor [Ikea local store](https://www.ikea.com/ro/ro/p/tradfri-senzor-miscare-wireless-alb-70429913/)
  * Xiaomi movement sensor [store: banggood](https://www.banggood.com/Original-Aqara-Zig_Bee-Wireless-Human-Body-PIR-Sensor-Smart-Home-Kit-From-Xiaomi-Eco-System-p-1177007.html?rmmds=search&cur_warehouse=HK)
* Push button[optional]
  * Ikea remote [Ikea local store](https://www.ikea.com/ro/ro/p/tradfri-potentiometru-wireless-alb-00468432)
  * Xiaomi button [store: bangood](https://www.banggood.com/Original-Xiaomi-Mijia-Smart-Home-Zig-bee-Wireless-Smart-Switch-Touch-Button-ON-OFF-WiFi-Remote-Control-Switch-p-1049175.html?rmmds=search&cur_warehouse=HK)
  
### What will it do

* Lights will switch ON when movement is detected on each floor(or only the light bulb from movement detection floor) and will turn OFF after a delay(also decided by used).
* Ligths will be completly OFF during day
* Lights will be set to 10% during night without movement detection





