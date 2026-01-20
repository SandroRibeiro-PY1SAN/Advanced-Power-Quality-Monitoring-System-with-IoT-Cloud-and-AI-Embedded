# Advanced-Power-Quality-Monitoring-System-with-IoT-Cloud-and-AI-Embedded
Manuscript ID: IEEE LATAM Submission ID: XXXXX

Authors:
Sandro Carneiro Ribeiro
Leonardo de Carvalho Vidal

Real-time analyzer for managing the electrical variables of an installation connected to a power distributor. This equipment consists of several modular hardware modules and dedicated software.
This project has an electronic interface to support auxiliary voltage (J1) and current (J2) measurement boards, and the microcontroller (U2). The electrical design was developed using KiCad software version 8.0.

The microcontroller used is a 30-pin ESP-WROOM32 from Espressif. This model features the Xtensa® Dual-Core 32-bit LX6 microprocessor, with a maximum clock speed of 240 MHz, 520 KBytes of RAM and 4 MB of Flash memory, a 12-bit ADC, and Wi-Fi and Bluetooth Low Energy (BLE) 4.2 connectivity.

The designed board used 12-bit analog ADC inputs to receive signals from the voltage and current acquisition boards from the mains. Other inputs were reserved for future expansions.

MainBoard SCH:

<img width="631" height="527" alt="SCH_MAIN" src="https://github.com/user-attachments/assets/33ff991b-7e2c-41f7-9c48-634ffe1cfcb1" />

MainBoard PCB Top:

<img width="1139" height="539" alt="TOP" src="https://github.com/user-attachments/assets/6b6a99c7-fb46-49a2-84ef-85edd112bf3e" />

MainBoard PCB Botton:

<img width="1147" height="537" alt="Bottom" src="https://github.com/user-attachments/assets/efe8474c-4c04-4562-b41b-be23279c8ea5" />

VAC Probe:

<img width="477" height="185" alt="ZMPT101B" src="https://github.com/user-attachments/assets/874bae04-560d-4f36-ae6e-2304bdb24ee7" />

ACA Probe:

<img width="410" height="196" alt="ZMCT103C Current Transformer 2b" src="https://github.com/user-attachments/assets/80e14f50-5550-41cd-8160-af30ec4c74d8" />

