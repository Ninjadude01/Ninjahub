# Ninjahub

My project is a usb hub that uses a usb c as the upstream connector, and 2 usb c + 2 usb a as the downsteam connectors. It has a unqiue 18-sided design, and the pcb contains holes so I can use screws to secure it onto the case. I decided to make this project because I do not have a usb hub, and making one seemed like a fun challenge! I defenetly learned a lot while building this project, so I am glad I did not try to do another simple project like a 3d modeled phone stand.

# Renders 
![1](Pictures_of_Project/Screenshot%202026-04-19%20201134.png)
![1](Pictures_of_Project/Screenshot%202026-04-19%20201148.png)
![1](Pictures_of_Project/Screenshot%202026-04-19%20201203.png)

# Schematic Diagram
![1](Pictures_of_Project/Screenshot%202026-04-19%20194734.png)

# PCB
![1](Pictures_of_Project/Screenshot%202026-04-19%20194744.png)

# PCB 3D
![1](Pictures_of_Project/Screenshot%202026-04-19%20194755.png)

# BOM 
(exported from EasyEDA, this project uses PCBA, 5 boards for $28.33 USD)
|No.|Quantity|Comment              |Designator              |Footprint                       |Value|Manufacturer Part    |Manufacturer   |Supplier Part|Supplier|
|---|--------|---------------------|------------------------|--------------------------------|-----|---------------------|---------------|-------------|--------|
|1  |8       |1uF                  |C1,C2,C3,C4,C5,C6,C8,C10|C0603                           |1uF  |                     |               |             |        |
|2  |3       |100nF                |C7,C9,C11               |C0603                           |100nF|                     |               |             |        |
|3  |6       |5.1K                 |R1,R2,R3,R4,R5,R6       |R0603                           |5.1K |                     |               |             |        |
|4  |1       |SL2.1s               |U1                      |SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL|     |SL2.1s               |CoreChips(和芯润德)|C2684433     |LCSC    |
|5  |3       |TYPE-C 16PIN 2MD(073)|USB1,USB2,USB6          |USB-C-SMD_TYPE-C-6PIN-2MD-073   |     |TYPE-C 16PIN 2MD(073)|SHOU HAN(首韩)   |C2765186     |LCSC    |
|6  |2       |10.0 QHHTZB6.3       |USB4,USB7               |USB-A-TH_10.0QHHTZB6.3          |     |10.0 QHHTZB6.3       |SHOU HAN(首韩)   |C668591      |LCSC    |

