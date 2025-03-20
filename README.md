# EmbedCore - BLDC Motor Controller

EmbedCore is a high-power brushless motor controller designed for integration into **Autonomous Mobile Robot** wheel actuators. It can also be used in other applications.  
This BLDC Motor Controller is my final thesis project at **Subotica Tech - College of Applied Sciences**.

---

## Specifications

| Parameter            | EmbedCore BLDC Controller V1.0 |
|----------------------|--------------------------------|
| **Voltage Input**   | 12-44V                         |
| **Peak Electrical Power** | 1.325kW                |
| **Mass**            | TBD                            |
| **Peak Phase Current** | 100A                      |
| **Communication**   | 5Mbps CAN-FD & RS485          |
| **Cooling**         | 12V Fan                        |
| **Positioning**     | Hall Sensor Connector         |
| **Control Rate**    | 15-30kHz                      |
| **PWM Switching Rate** | 15-60kHz                  |
| **MCU**            | STM32G474                      |
| **Dimensions**      | 84.3 x 76.2mm                    |

---

## Directory Structure

```
BLDC Motor Controller
├── Datasheets                     # Datasheets of main components
├── Documentation
│   ├── Schematic                  # PDF Schematic
│   ├── PCB                        # PCB Documentation in PDF
├── Lib                             # Altium Component Libraries
├── Manufacturing
│   ├── Gerber                     # Gerber files
│   ├── BOM                         # Bill of Materials
│   ├── Component Positions         # Component placement files for PCB assembly
├── PCB                             # Altium Designer PCB file
├── Schematic                       # Altium Designer Schematic files
```

---

## Firmware

The associated firmware is available in the [BLDC Motor Controller - Firmware](https://gitlab.com/autonomus-mobile-robot/firmware) repository.

---

## License

This project is licensed under the **Apache License 2.0**.

---

## Support

If you need any help regarding this board, feel free to contact me at:  
📧 **embedcore7@gmail.com**
