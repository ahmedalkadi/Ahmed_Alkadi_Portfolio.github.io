---
title: "Electric Vehicle Research"
excerpt: "The present research aims to design the managing cooling system for the battery system, manufacture the cooling system, and integrate the (BCS) with the battery pack. The function of this system is to measure the heat dissipated from the batteries in different conditions from discharging, idling charging, and fast charging to deliver the corresponding coolant mass flow rate accordingly."
collection: portfolio 
---

## Research Work Objectives:


1. Choose the suitable cooling method (bottom plate cooling, microchannels, immersed cooling, or corrugated cooling tubes).
2. Design a mathematical representation of the battery heating.
3. Build the computational domain in ANSYS software.
4. Optimize the cooling method to ensure sufficient cooling and uniform battery thermal distribution.
5. Study the effect of changing the cooling fluid mass flow rate, changing the cooling fluid patterns and dimensions.

## Project Insights:


<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture40.png" alt="Project Insights" style="float: right; width: 350px; margin-left: 15px;">

- It is a national project to have the first steps in manufacturing a locally-made Electric vehicle.
- This project is in cooperation with the Military Technical College as well as some other engineering schools.
- This project is sponsored by the Academy of Scientific Research & Technology and the Arab Organization for Industrialization with a budget of 11 million Egyptian pounds (~450K USD).


## The Battery Cooling System Design

The battery cooling system should manage the thermal energy from the battery pack. The refrigeration cycle receives sensing signals (on/off) controlled by the temperature sensor held on the batteries.

<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture52.png" alt="Cooling System Design" style="width: 100%;">

The designed system comprises:
- Refrigeration cycle working with R 134a refrigerant with adjustable expansion valves.
- Heat exchangers to transfer the battery heat to the refrigeration cycle.
- Circulation pump to circulate the coolant through the batteries.
- Control valve to control the pressure drop from the battery pack.
- Coolant reservoir.
- Measuring instruments.
- Temperature sensors for the circulating coolant (T1 and T2).
- Temperature sensors for battery cells.
- Pressure gauge.
- Flow rate meter.

## Cooling Passages General Arrangements


- The battery bank is divided into 16 modules, each with 350 (14x25) cells (18650).
- The outer dimensions of the module are 70cm x 25cm.
- The outer dimensions of the battery pack are 203cm x 140cm.
- The required pressure of the pump is estimated to be 270 pascals with a flow rate of around 5 liters/min.

<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture53.png" alt="Cooling Passages" style="width: 100%;">

## For Simplicity, We Will Only Simulate One Path of the Module to Ensure Alignment Between the Analytical and Simulation Results


<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture42.png" alt="Simulation Path" style="width: 100%;">

## The Pack Arrangement


<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture54.png" alt="Pack Arrangement" style="width: 100%;">

## Simulation Using Ansys Fluent


### Boundary conditions
- **Inlet:**<br/>
  Number of inlet areas: 6 for the side plate.<br/>
  Mass flow: 0.05 kg/s with a temperature of 20°C.

- **Outlet:**<br/>
  Number of outlet areas: 6 for the side plate.<br/>
  Pressure outlet, surrounding temperature: 25°C.
  
- **Heat source:**<br/>
  Battery is subjected to heat generation at a rate of 5C-rate (57,812 W/m³).
  
- **Walls:**<br/>
  All walls are adiabatic except for the upper wall of the battery, subjected to natural convection with a heat transfer coefficient of 5 W/m²K and a surrounding temperature of 25°C.

## Results And Discussion:


### The Following Results Were Obtained When Applying a 5C-rate
-----

### 1. Temperature Contours

- Batteries And Cooling Passages Contours:<br/>
<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture44.png" alt="Temperature Contour 1" style="width: 100%;"><br/>
<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture47.png" alt="Temperature Contour 2" style="width: 100%;">

- The Cooling Passages temperature Contours:<br/>
<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture48.png" alt="Cooling Passages" style="width: 100%;">

### 2. The Cooling Passages Pressure Contours:<br/>
<br/><img src="https://ahmedalkadi.github.io/Ahmed_Alkadi_Portfolio.github.io/images/EV/Picture51.png" alt="Pressure Contour" style="width: 100%;">
