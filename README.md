# Home-Automation-Using-HTML
Home Automation Using HTML
Aim: IoT Home Automation using ESP8266 Web Server.
Component used:
1. ESP8266 Node MCU x 1
2. Relay (5v relay) x 2
3. Voltage Regulator IC (LM7805 5V IC) x 1
4. Female DC Power Jack (DCJ0202) x 1
5. Diode (1N4007) x 1
6. Resistor (330ohm) x 1
7. NPN Transistor (BC547) x 1
8. Terminal Block (5mm) x 1
9. LED (5mm LED Any Color) x 1
10.Female Header (2.54mm Female Header) x 1
Software Used:
1. Arduino IDE
IoT Platform: Blynk App
Theory:
ABOUT THIS PROJECT
In this project we learn how to make IoT Based Home Automation using
ESP8266 Web Server. By Home Automation we mean controlling lighting and
appliances without any manual switch but using the system that is connected to
Internet. When connected with the Internet, home devices are an important
constituent of the Internet of Things (“IoT”).
In this project we will be using a Local Web Server. A web server is a device that
runs websites. It’s a program or a bunch of code that distributes web pages as
they are requisitioned. The basic objective of the Web Server is to store, process,
and deliver web pages to the users. This intercommunication is done using
Hypertext Transfer Protocol (HTTP).
In this Home Automation System, we will control 4 home appliances connected
to Relay using Local Web Server. The Wifi Module NodeMCU ESP8266 will
Receive commands from the Web Page.
1.ESP8266 Node MCU:
Node MCU is an open-source Lua-based firmware and development
board specially targeted for IoT-based Applications. It includes firmware that
runs on the ESP8266 Wi-Fi SoC from Express if Systems, and hardware that is
based on the ESP-12 module.
Node MCU ESP8266 Specifications & Features
 Microcontroller: Ten silica 32-bit RISC CPU Extensa LX106
 Operating Voltage: 3.3V
 Input Voltage: 7-12V
 Digital I/O Pins (DIO): 16
 Analog Input Pins (ADC): 1
 UARTs: 1
 SPIs: 1
 I2Cs: 1
 Flash Memory: 4 MB
 SRAM: 64 KB
 Clock Speed: 80 MHz
 USB-TTL based on CP2102 is included onboard, Enabling Plug n Play
 PCB Antenna
 Small Sized module to fit smartly inside your IoT projects

![Screenshot 2022-11-29 203747 1](https://user-images.githubusercontent.com/119427824/204775011-1f3fafab-2e69-4f93-92fa-4f3b3bae8d35.png)

Power Relay
IoT Power Relay is a controllable power relay equipped with four outputs that
help to create an Internet of Things project with safe, reliable power control. With
the IoT Power Relay you can easily control the power going to a device with an
Arduino, Raspberry Pi or other single-board computer or microcontroller. It
provides an alternative to the Power Switch Tail.
The IoT Power Relay is designed to allow to safely control an outlet device that
operates at 3–48VDC or 12–120VAC. Each IoT Power Relay features a single
input (from the included C13 power cable) to four outputs: one normally on, one
always on, and two normally off. The durable SPDT control relay is rated at
30/40A, for 400,000 operations.
Features of Iot Power Relay
 Universal control voltage 3-60VDC or 12-120VAC
 A single input signal switches four outlets: one normally on, one always
on, two normally off.
 Optical isolation, relay hysteresis and de-bounce protection add safety.
 A large MOV clamps surges for clean 90-140VAC power.
 The durable SPDT control relay is rated at 30/40A, >400,000 operations at
12A or 2 million+ operations at 5A.
 A 12A thermal safety circuit breaker switch prevents overloads.
 Mounting tab with two screw holes


![Screenshot 2022-11-29 203913 2](https://user-images.githubusercontent.com/119427824/204775056-94bbf9c6-0e6a-4267-aa3a-3413c0e62b2c.png)

Circuit Diagram:
![Screenshot 2022-11-29 204000 3](https://user-images.githubusercontent.com/119427824/204775088-69334582-5fa1-40ee-8790-36b0a8d6629b.png)




Output:
When you on a serial monitor, after uploading the code, you will
get the Ip address on the serial monitor.
![Screenshot 2022-11-30 160439 4](https://user-images.githubusercontent.com/119427824/204775141-732aaca2-5f98-4c20-bbe9-624ece2a8a91.png)



Then after copying the Ip address to the to a webserver of web
browser (like google chrome or Firefox) then you will get to know
the Ip address of the host in which it is connected. Then you can
control the appliance accordingly.
![Screenshot 2022-11-30 160523 5](https://user-images.githubusercontent.com/119427824/204775195-b3ad6014-951f-45c4-812d-5891415f5ba4.png)


When GPIO 5 is off then light is off.
![Screenshot 2022-11-30 160612 6](https://user-images.githubusercontent.com/119427824/204775311-fdc52053-51d7-43b7-af86-95187d48f547.png)
![Screenshot 2022-11-30 160638 7](https://user-images.githubusercontent.com/119427824/204775333-ebe74eb0-2f8b-4ed0-bcc1-ad094169e085.png)



When GPIO 5 is on then light is on.
![Screenshot 2022-11-30 160707 9](https://user-images.githubusercontent.com/119427824/204775368-0db3526a-659a-4212-beb7-56cc6df7d8f8.png)
![Screenshot 2022-11-30 160738 10](https://user-images.githubusercontent.com/119427824/204775380-2b0fa48d-bf4a-45f8-86c1-455ca0944028.png)


