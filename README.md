Patient Health Monitoring System Using IoT

Overview
This project is an IoT-based patient health monitoring system that tracks vital signs such as temperature, heart rate, SpO2, and blood pressure. It is designed to simulate real-time monitoring for remote healthcare use cases and abnormal-condition detection.

Problem
Manual patient checkups are slow, costly, and not continuous, which creates delays in detecting health deterioration. This is especially problematic for elderly patients, chronic patients, and people in rural areas with limited hospital access.

Features
Real-time monitoring of key health parameters.

Abnormal-value detection using threshold-based alerts.

Local display and serial output for live observation.

Simulation-based replication of the base paper using Wokwi.

Graph-based comparison of healthy and diseased conditions.

Tech Stack
ESP32

Wokwi

Python

Matplotlib

Excel

Your Role
The project was replicated and documented by simulating sensor inputs, mapping analog values to biomedical readings, collecting serial data, and generating graphs for analysis. The work also included organizing the presentation, explaining the workflow, and comparing healthy versus diseased modes.

Setup / How to Run
Open the Wokwi project in the browser.

Load the ESP32 circuit and simulated sensor inputs.

Run the simulation in healthy or diseased mode.

Observe the values on the OLED display and serial monitor.

Export the readings to Excel or Python for plotting and analysis.

Results
The simulation successfully showed different output patterns for healthy and diseased states. The threshold logic worked as expected, and the graphs supported the idea that IoT-based monitoring can help detect abnormal conditions early.

Future Scope
Add a smart pillbox for medication adherence.

Add a smart cup module for intake tracking.

Add fall detection using motion sensors and machine learning.

Integrate all modules into one dashboard.
