---
title: "AI Agent-based Framework for Battery Thermal Management *-Click For More Details-*"
collection: publications
category: conferences
permalink: /publication/2026-06-12
date: 2026-06-12
venue: '2026 IEEE Transportation Electrification Conference & Expo (ITEC+EATS), Novi, Michigan, USA'
paperurl: 'https://doi.org/10.1109/ITECEATS66641.2026.11592979'
citation: 'A. Alkadi and R. Ahmed, "AI Agent-based Framework for Battery Thermal Management," in 2026 IEEE Transportation Electrification Conference & Expo (ITEC+EATS), Novi, MI, USA, 2026, pp. 1-6, doi: 10.1109/ITECEATS66641.2026.11592979.'
---



AI Agent-based Framework for Battery Thermal Management
=====

The temperature of the battery cell is one of the main factors that affect its performance, safety, and life span, while the internal temperature of the cell can't be measured directly in the electric vehicle. In this paper, an agent-based AI framework is proposed that combines physics-based modeling, deep learning, and large language model (LLM) orchestration for battery thermal prediction and management. <br/>

The paper was published at the IEEE Transportation Electrification Conference & Expo (ITEC 2026) in Novi, Michigan, USA. The full paper is available on [IEEE Xplore](https://doi.org/10.1109/ITECEATS66641.2026.11592979). <br/>


The Research Overview
=====
Research objectives:<br/>
1. Build a high-fidelity electro-thermal model for an LG M50T 21700 NMC cylindrical cell, and validate it against experimental measurements.<br/>
2. Use the validated model to augment the existing driving profiles with the internal thermal data of the cell.<br/>
3. Train deep learning models to predict the internal temperature distribution of the cell from the current profile.<br/>
4. Build an AI agent powered by an LLM to run the prediction, evaluation, visualization, and reporting tasks.<br/>


The Electro-Thermal Model
-----
- PyBaMM Doyle-Fuller-Newman (DFN) electrochemical model coupled with a 2D axisymmetric finite difference method (FDM) thermal model, solved with the Crank-Nicolson scheme.
- The model was validated against the experimental measurements with RMSE between 0.51 °C and 1.21 °C. <br/>
<img width="264" height="462" alt="image" src="https://github.com/user-attachments/assets/96294748-5733-4764-868c-737ae208b44f" />


The Deep Learning Models
-----
- LSTM, GRU, RNN, and 1D-CNN models were trained to predict the temperature at 30 internal points of the cell (6 axial x 5 radial nodes) from the current profile.
- The GRU model gave the best results, with an average RMSE of 0.07788 °C on the driving profiles and 0.03218 °C on 1C charging. <br/>


The AI Agent
-----
The LLM orchestrator drives five tools:
1. Cycle predictor.
2. Cycle segment investigator.
3. Prediction evaluator.
4. Results summarizer.
5. Results visualizer.
<img width="539" height="532" alt="image" src="https://github.com/user-attachments/assets/0ff03f72-a1c1-4c7b-bbce-38b67bbec682" />




My roles in the research work
=====
1. Build the electro-thermal model and validate it against the experimental data.<br/>
2. Generate the thermal dataset for the driving profiles.<br/>
3. Train and compare the deep learning models.<br/>
4. Build the AI agent and its tools, and benchmark the LLM backends.<br/>
5. Write the paper and present it at ITEC 2026.<br/>
