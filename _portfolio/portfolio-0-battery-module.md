---
title: "Battery Module Thermal Test Rig (Ongoing Research)"
excerpt: "The present research at McMaster University aims to build an instrumented 12-cell parallel battery module with liquid cold-plate cooling, to study the thermal behavior of the cells under high C-rate charging, discharging, and drive cycles. The test rig provides the experimental data for thermal models and AI-based battery thermal management."
collection: portfolio
permalink: /portfolio/battery-module-test-rig/
---

## Project Overview:

I am currently building a 12-cell parallel (12p) battery module test rig at the McMaster Automotive Research Centre (MARC), under the supervision of Dr. Ryan Ahmed. The module is cooled by a ribbon cold plate, and every cell is instrumented with thermocouples to measure the cell-to-cell temperature distribution during operation.

## Research Work Objectives:

1. Build an instrumented 12p module with ribbon cold-plate cooling.
2. Study the temperature distribution between the cells of a parallel module under CC-CV charging, high C-rate discharging, and drive cycles.
3. Study the effect of programmable coolant temperature profiles on the module temperature and performance.
4. Build an experimental dataset to develop and validate thermal models and AI models for battery thermal management.

<img width="445" height="373" alt="image" src="https://github.com/user-attachments/assets/4d02b3ea-d4d4-4900-9193-7e527e40b846" />


## The Module Design:

- 12 LG INR21700 M50T NMC cylindrical cells (4.85 Ah, 18.2 Wh nominal) connected in parallel.
- Ribbon cold plate in contact with the cells, connected to a recirculating chiller.
- Copper bus bars designed and fabricated for the high-current connections.
- Two thermocouples on each cell: one on the ribbon side and one on the opposite side.

<img width="559" height="325" alt="image" src="https://github.com/user-attachments/assets/9a3935a3-24f4-4172-a5bd-fd6e984405a5" />


## Test Setup and Instrumentation:

- **Battery cycler:** Digatron BTS-600, with test programs for CC-CV charging and discharging, US06 drive cycles, and OCV-SOC characterization.
- **Temperature measurement:** NI cDAQ-9189 with NI 9213 thermocouple module, logged with FlexLogger.
- **Cooling:** PolyScience recirculating chillers controlled through RS-232 serial communication. I upgraded one of the lab chillers with a DB9 serial port, so the coolant temperature can follow programmable cooling profiles.
- **Impedance:** Galvanostatic electrochemical impedance spectroscopy (EIS) of the module with a Gamry Interface 5000.
- **Safety system:** Arduino Due based safety monitoring, with a leak sensor (Blue Robotics SOS) and PT100 RTDs (MAX31865) switched through a relay circuit.

<img width="1498" height="855" alt="image" src="https://github.com/user-attachments/assets/4e096c7e-a13c-4905-8acb-d4b1abbcf08e" />


## Software Development:

- **Chiller control application:** A Python desktop application (PySide6) that loads a cooling profile, interpolates between the profile points, sends the set-points to the chiller over serial, plots the live temperatures (pyqtgraph), and logs the data to CSV. The application is packaged as a Windows executable.
- **Safety firmware:** Embedded firmware for the Arduino Due safety monitoring system.
- **Cycler programs:** Digatron test programs for the charging, discharging, and drive cycle tests.

<img width="398" height="288" alt="image" src="https://github.com/user-attachments/assets/b4a77da1-a307-4ddd-9ac1-49727e50ad7d" />



## Next Steps:

- A larger test campaign with different C-rates, dynamic load profiles, and cooling profiles, to build the dataset for data-driven thermal models.
- Use the measured cell temperatures to validate the thermal models of the module.

## My roles in the project:

1. Build and assemble the 12-cell module, including the copper bus bars.
2. Install the thermocouples and commission the thermocouple DAQ.
3. Establish the serial control of the chillers and develop the chiller control application.
4. Design, wire, and program the Arduino Due safety monitoring system.
5. Write the Digatron test programs and run the tests.
6. Troubleshoot the test setup (DAQ communication, EIS current path, chiller faults) and analyze the test data.
