# B.TECH-Project
Hello All here I share insights into my B.Tech final year project which I have done in the team of 3, I was team lead for my project

Our project is motivated by the critical need to enhance the performance and service life of solar panels, addressing challenges associated with preventive and active maintenance, problem detection, and real-time monitoring. The approach lies in the innovative use of IoT, remote monitoring system for solar plants.

Central to our methodology is the integration of IoT to enable seamless monitoring of solar panel performance. This not only facilitates preventive and active maintenance but also allows for the identification of issues in real time. Through the use of wireless monitoring, powered by new-generation instrumentation and an Arduino Uno module, we aim to empower stakeholders with the ability to take proactive steps to maintain and boost energy production and efficiency.

Our project features a monitoring system implemented with Arduino and web server-based software. The Smart Monitoring display system provides a daily breakdown of renewable energy usage, empowering users to study and optimize their energy resources. This real-time analysis has a direct impact on the utilization of renewable energy, aligning with the global shift towards sustainable practices.

Problem Statement:

The main objectives of our proposed health monitoring system for solar power systems are as follows:

Eliminate Physical Maintenance: Our system aims to eliminate the need for physical or in-person maintenance for solar panels, reducing operational costs and enhancing efficiency.

Wireless Measurement and Transmission: Automatic measurement of current, voltage, and efficiency is achieved, and this data is wirelessly transmitted through a GSM module, providing real-time insights into the solar panel's performance.

Time-Based Automation: The system features an automatic on/off mechanism based on the time of the day, ensuring optimal power utilization and energy efficiency.

Anomaly Detection: Our system is designed to detect unusual readings from the solar panels, providing an early warning system for potential issues or malfunctions.

IoT Data Transmission and Analysis: Data collected is transmitted and analyzed through an IoT module on the network carrier (GSM), enabling remote monitoring and control of the solar power system.

Working Principle:

At the core of our system is the micro-controller, acting as the brain orchestrating all hardware operations. The voltage and current sensors measure output values from the solar panel, providing crucial data for our analysis. A battery connected to a relay facilitates power production during nighttime hours. Additionally, a DC motor visually represents the power generated from the panel, while an RTC (Real-Time Clock) automates relay switching based on the time of day. All operations are displayed on an LCD and monitored via IoT. The system fetches initial values from the solar panel's voltage and current sensors, tracking their gradual reduction to monitor and display the decrease in the solar panel's lifespan through IoT.

The heart of our project lies in the calculation and evaluation of direct influences of contact thermal resistances using the Open-Circuit Voltage (OCV) method for Maximum Power Point Tracking (MPPT). MPPT, an algorithm embedded in charge controllers, plays a crucial role in extracting maximum power from Photovoltaic (PV) modules under various conditions. The open-circuit voltage, representing the potential difference when a device is disconnected from any circuit, serves as a key parameter in this process.
for demo of the project please refer the link below:
https://drive.google.com/file/d/1IsRreDjP3v6pv8dwyE9V2klkEstNAQYP/view?usp=sharing
