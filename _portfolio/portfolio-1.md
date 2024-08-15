---
title: "Electric Vehicle Research"
excerpt: "The present research aims to design the managing cooling system for the battery system, fabricate the cooling system and integrate the (BCS) with the battery pack. The function of this system is to measure the heat dissipated from the batteries in different conditions from discharging, idling charging and fast charging to deliver the corresponding coolant mass flow rate."
collection: portfolio
---

Research Work Objectives:
=====

1- choose the suitable cooling method (bottom plate cooling, micro channels, immersed cooling or corrugated cooling tubes ) <br/>
2- Design mathematical representation of the battery heating .<br/>
3- build the computational domain in ANSYS software.<br/>
4- optimize the bottom plate internal groves to ensure sufficient cooling and uniform battery thermal distribution. <br/>
5- study the effect of adding multi cooling plates to the battery. <br/>


Project Insights:
=====
![image](../images/EV/Picture40.png){: .align-right width="350px"} 
<br/><img src='../images/EV/Picture40.png'>{: .align-right width="350px"} 

- It is a national project to have the first steps in manufacturing a locally-made Electric vehicle.
- This project is in cooperation with the (Military technical college) as well as some other engineering schools.
- This project is sponsored by (The Academy of Scientific Research & technology) and the ( Arab organization for industrialization ) with budget 11 million Egyptian pounds around 450K US $.
- The prototype of the electric vehicle is planned to get finalized by June 2023.



The Bttery Cooling System Design 
=====

The battery cooling system should manage the thermal energy from Battery pack. The refrigeration cycle receives sensing signal (on / off) controlled, from the temperature sensor hold on the batteries.
![image](../images/EV/Picture52.png) <br/> <br/>

The designed system comprises of:
- Refrigeration cycle working with R 134a refrigerant with adjustable expansion valves.
- Heat exchangers for transfer the battery heat to the refrigeration cycle 
- Circulate pump to circulate the coolant through the batteries 
- Control valve to control the pressure drop from the battery pack.
- Coolant reservoir.
- Measuring instrument
- Temperature sensors for the circulating coolant (T1 and T2).
- Temperature sensors for battery cells.
- Pressure gauge.
- Flow rate meter

Cooling passages general arrangements
=====

- The battery bank is divided into 16 modules each with 350 (14*25) cells (18650) 
- The outer dimension of the module is 70cm * 25cm 
- The outer dimension of the battery pack is 203cm * 140cm
- The required pressure of the pump is estimated to be 270 pascal with flow rate around 5 lit/min

![image](../images/EV/Picture53.png) <br/> <br/>


For The Simplicity Issues We Will Only Simulate One Path of the Module to Assure Alignment Between the Analytical and Simulation Result  
=====
![image](../images/EV/Picture42.png) <br/> <br/>

The Pack Arrangement 
-----

![image](../images/EV/Picture54.png) <br/> <br/>


Simulation Using Ansys Fluent
=====

Boundary conditions 
- Inlet<br/>
  Number of inlet areas are 6 for the side plate 
  Mass flow is 0.05 kg/s with temperature of 20 ℃

- Outlet <br/>
  Number of inlet areas are 6 for the side plate 
  Pressure outlet, surrounding temperature of 25 ℃
  
- Heat source<br/>
  Battery is subjected to heat generation with the rate of 5 c-rate (57812)W/m3
  
- Walls <br/>
  All the walls are adiabatic except for the upper wall of the battery subjected to natural conviction with heat transfer coefficient of (5 W/m2K) and surrounding temperature of 25 ℃.


Results And Discussion
=====

The Following Results Are taken When Applying (5C) rate
-----

1- Temperature Contour <br/>

- The Whole Battery Module <br/>
![image](../images/EV/Picture44.png) <br/> <br/>
![image](../images/EV/Picture47.png) <br/> <br/>


- The Cooling Passages  <br/>
![image](../images/EV/Picture48.png) <br/> <br/>



2- Pressure Contour <br/>
![image](../images/EV/Picture51.png) <br/> <br/>





<!-- excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
