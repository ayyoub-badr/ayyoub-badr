<h1 align="center">Hi there, I'm Ayoub Badr 👋</h1>

<p align="center">
  <em>"From the sensor to the dashboard — if it can be measured, it can be controlled."</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/ayoub-badr"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ayoub.badr82@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Meknès,_Morocco-3E0097?style=for-the-badge" alt="Location"/>
</p>

---

## About Me

3rd-year Electromechanical Engineering & Industrial Digitalization student at **ENSAM Meknès**, specializing in **industrial automation, cybersecurity and IT/OT integration**. I build the chain that runs from a sensor up to a supervision dashboard — PLC programs and operator HMIs, heterogeneous fieldbus networks, OPC UA and MQTT gateways, time-series historization and alerting. Currently working on multimodal sensor fusion for a contactless machine-control station, and deepening my knowledge in industrial network security.

🔎 **Looking for a 6-month final-year engineering internship (PFE) starting February 2027** — industrial automation and digitalization, supervision, or Industry 4.0 / IIoT.

---

## Tech Stack

**Automation & Control**

![TIA Portal](https://img.shields.io/badge/TIA_Portal-009999?style=for-the-badge&logo=siemens&logoColor=white)
![S7-1200](https://img.shields.io/badge/Siemens_S7--1200-009999?style=for-the-badge&logo=siemens&logoColor=white)
![Schneider TSX](https://img.shields.io/badge/Schneider_TSX_(PL7)-3DCD58?style=for-the-badge&logo=schneiderelectric&logoColor=white)
![GRAFCET](https://img.shields.io/badge/GRAFCET-555555?style=for-the-badge)
![LADDER](https://img.shields.io/badge/LADDER-555555?style=for-the-badge)
![PID](https://img.shields.io/badge/PID_%26_LQR_control-555555?style=for-the-badge)

**Industrial Networks & IT/OT**

![PROFINET](https://img.shields.io/badge/PROFINET-E2001A?style=for-the-badge)
![PROFIBUS DP](https://img.shields.io/badge/PROFIBUS_DP-E2001A?style=for-the-badge)
![AS-i](https://img.shields.io/badge/AS--i-F7941E?style=for-the-badge)
![Modbus](https://img.shields.io/badge/Modbus_RTU%2FTCP-0B6E99?style=for-the-badge)
![OPC UA](https://img.shields.io/badge/OPC_UA-0B6E99?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![ZigBee](https://img.shields.io/badge/ZigBee-EB0443?style=for-the-badge)

**Supervision, Data & Observability**

![WinCC](https://img.shields.io/badge/WinCC_Advanced-009999?style=for-the-badge&logo=siemens&logoColor=white)
![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Programming & Embedded**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=for-the-badge&logo=platformio&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Design & Simulation**

![CATIA](https://img.shields.io/badge/CATIA_V5-005386?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-E31E24?style=for-the-badge)
![ANSYS](https://img.shields.io/badge/ANSYS_Fluent-FFB71B?style=for-the-badge&logo=ansys&logoColor=black)
![KiCad](https://img.shields.io/badge/PCB_design-314CB0?style=for-the-badge)

---

## Current Focus

- 🎯 Multimodal fusion (voice + gesture + gaze) for a contactless machine-control station — rule-based vs. learned fusion, evaluated leave-one-person-out
- 🔐 Industrial cybersecurity: IT / DMZ / OT segmentation, the Purdue model, IEC 62443, gateway hardening
- 📊 Making process data useful: historization, threshold alerting and drift analysis rather than dashboards for their own sake
- ⚙️ Functional safety in machine design — IEC 60204-1, ISO 13850, ISO 13849-1

---

## Highlighted Projects

**🎙️ Contactless Machine Control Station — Voice, Gesture & Gaze**
Expertise project (team of two, ENSAM Meknès). I built the offline voice chain (Vosk, closed grammar), the operative part (ESP32, H-bridge, PID on encoder feedback) and the Node-RED supervision, on a versioned JSON-schema MQTT contract validated in CI. Safety by design: hardwired emergency stop outside the software, 500 ms watchdog, two-modality confirmation for critical commands. Now extended into a research study comparing rule-based and learned sensor fusion.

**🏭 Variable Speed Drive Bench — IT/OT Integration & Supervision 4.0**
Interconnected the three network layers of a drive bench around a Siemens S7-1200: AS-i for sensors and actuators, PROFIBUS DP and PROFINET between devices. Added an OPC UA gateway (KEPServerEX / Prosys) exposing process variables to MES/ERP levels, a WinCC Advanced HMI on a KTP700 panel, and a Node-RED dashboard archiving to SQLite and InfluxDB with threshold alerting and statistical drift analysis.

**🛗 5-Floor Elevator Mock-up — Sequential Control & SCADA Chain**
Functional analysis and full control program (GRAFCET, LADDER) on a Schneider TSX PLC with safety interlocks, then the complete communication chain on top: Modbus RTU master/slave, Modbus-TCP upload, MQTT publishing to the cloud and OPC UA normalization, supervised in real time under Node-RED.

**📡 Connected Electromechanical Test Bench — Secured RF Link**
Sized the complete power chain (motor, PWM drive, protections, cable cross-sections), designed the electrical schematics and a custom acquisition PCB with embedded instrumentation — Hall-effect current sensors, voltage measurement, incremental encoder, PT100 — and an encrypted, authenticated wireless link.

**🤖 Self-Balancing Robot — LQR Control**
State-space modeling of an inverted-pendulum system, then an LQR controller implemented on ESP32 with an MPU6050 IMU for real-time dynamic stabilization. Led end to end: mechanical design and assembly, control study, software.

**🏥 3-Axis Automated Medical Bed — ABBE Technologie**
Technical internship: full mechanical design in CATIA V5 with strength-of-materials verification, DXF preparation for cutting, actuator selection and sizing for the three motorized axes, associated power electronics, and the automated control with its touchscreen operator HMI — through to prototype assembly and commissioning.

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ayyoub-badr&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
</p>

---

<p align="center">
  📫 <a href="mailto:ayoub.badr82@gmail.com">ayoub.badr82@gmail.com</a> · <a href="https://linkedin.com/in/ayoub-badr">linkedin.com/in/ayoub-badr</a>
</p>
