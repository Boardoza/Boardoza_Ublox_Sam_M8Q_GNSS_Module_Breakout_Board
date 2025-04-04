# UBLOX SAM M8Q GNSS Module Breakout Board

The **Boardoza SAM-M8Q GNSS Breakout Module** is a **high-performance multi-GNSS receiver** designed for **precise positioning applications**. It integrates the **u-blox SAM-M8Q module**, which supports **GPS, GLONASS, and Galileo** satellite constellations for improved accuracy and reliability.  

This module operates with **3.3V or 5V**, making it compatible with a wide range of microcontrollers. It communicates with an MCU via **I<sup>2</sup>C and UART** interfaces, providing flexible integration for various applications, including **navigation systems, asset tracking, drones, and IoT-based geolocation solutions**.  

The **PPS, RST, INT, and SAFE** pins operate at **3.3V**, ensuring seamless interfacing with low-power microcontrollers.  

## [Click here to purchase!](https://www.ozdisan.com/maker-ve-iot-urunleri/boardoza/boardoza-modulleri/BOARDOZA-UBLOX/1206512)

|Front Side|Back Side|
|:---:|:---:|
| ![ Front](./assets/UBLOX_SAM_M8Q%20Front.png)| ![ Back](./assets/UBLOX_SAM_M8Q%20Back.png)|

---

## Key Features

- **Multi-GNSS Support:** Compatible with GPS, GLONASS, and Galileo for enhanced positioning accuracy.  
- **Flexible Power Compatibility:** Operates with **3.3V or 5V**, making it suitable for a variety of MCUs.  
- **Dual Communication Interfaces:** Supports both **I<sup>2</sup>C and UART** for versatile connectivity.  
- **Time Pulse Output (PPS):** Provides precise timing synchronization at **1 pulse per second (default)**.  
- **Low Power Consumption:** Ideal for battery-operated applications such as **wearables and IoT tracking devices**.  
- **Industrial-Grade Performance:** Works reliably in extreme environments with a **temperature range of -40°C to +85°C**.  
- **Future-Proof Design:** Includes a **SAFEBOOT_N** function pin for firmware updates and configuration changes.  

---

## Technical Specifications

**Model:** u-blox SAM-M8Q  
**Input Voltage:** 3.3V - 5.5V  
**Voltage Input Type:** 4-pin 2.50mm header  
**Functions:** I<sup>2</sup>C and UART GNSS Receiver  
**Satellite Support:** GPS, GLONASS, Galileo, BeiDou  
**Time Pulse (PPS) Accuracy:** ±30 ns (typical)  
**Operating Temperature:** -40°C to +85°C  
**Board Dimensions:** 40mm x 40mm  

---

## Board Pinout

### **( J1 ) UART Communication Pins**  

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | TXD | Transmitted Data Pin |
| 3 | RXD | Received Data Pin |
| 4 | VCC | Power Supply (3.3V - 5.5V) |

### **( J2 ) I<sup>2</sup>C Communication Pins**  

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | SDA | I<sup>2</sup>C Serial Data Pin |
| 3 | SCL | I<sup>2</sup>C Serial Clock Pin |
| 4 | VCC | Power Supply (3.3V - 5.5V) |

### **( J3 ) Additional Function Pins**  

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | PPS | Time pulse signal (default: 1 pulse per second). See the u-blox M8 protocol specification for details. |
| 2 | RST | Active LOW reset pin. Internally pulled up to VCC. |
| 3 | INT | Used for time or frequency aiding data input to the receiver. |
| 4 | SAFE | SAFEBOOT_N function pin for firmware updates and reconfiguration (Reserved). |

---

## Board Dimensions

<img src="./assets/UBLOX_SAM_M8Q Dimension.png" alt=" Dimension" width="450"/>

---

## Step Files

[Boardoza UBLOX SAM M8Q.step](./assets/UBLOX_SAM_M8Q%20Step.step)

---

## Datasheet

[Boardoza UBLOX SAM M8Q Datasheet.pdf](./assets/UBLOX_SAM_M8Q%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact <support@boardoza.com>

---

## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
