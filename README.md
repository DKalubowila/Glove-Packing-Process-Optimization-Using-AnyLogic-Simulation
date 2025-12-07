Glove Packing Process Optimization Using AnyLogic Simulation

This project focuses on optimizing a glove packing production line using AnyLogic simulation. Two system models were developed — a manual (current) system and an automated (future) system — to measure performance, identify bottlenecks, and analyze improvements after automation.

📌 Project Overview

The glove packing process includes multiple stages:

Stamping
Separation
Pairing
Inner Packaging
Sealing
Carton Forming & Packing
Box Sealing & Final Dispatch

The goal was to simulate both the existing manual process and a more advanced automated process, compare their performance, and evaluate potential efficiency improvements.

🎯 Objectives
Build two realistic simulation models in AnyLogic:
Before Automation (Manual)
After Automation (Automated)

Add real-world behaviours such as:
Stochastic arrival rates
Machine downtime
Shift schedules
Resource constraints
Queueing and batching

Compare outputs and measure improvement.

📊 Key Results
Manual System
Input: 240,000 gloves
Output: 80,000 gloves
Efficiency: 33.33%

Automated System
Input: 240,000 gloves
Output: 185,000 gloves
Efficiency: 77.08%

Overall Improvement

+43.75% increase in process efficiency
Significant reduction in bottlenecks
More stable flow with realistic queues and machine idle times

🛠 Tools & Technologies
AnyLogic (Process Modeling Library)
Simulation Modeling
Industrial Engineering Concepts
Data Analysis & Optimization
Java (inside AnyLogic blocks)

📁 Repository Structure

/GlovePackingSimulation
│

├── Manual_Model/          # Before Automation (AnyLogic .alp file)

├── Automated_Model/       # After Automation (AnyLogic .alp file)

├── README.md              # Project documentation

└── Outputs/               # Screenshots, reports, graphs (optional)

🚀 How to Run the Simulation

1. Install AnyLogic (University or PLE version).
2. Open the .alp files:
Manual_Model.alp
Automated_Model.alp
3. Click Run under Simulation.
4. Compare output KPIs such as throughput, utilization, and wait times.

📈 What I Learned

Building realistic discrete-event simulations

Handling resource constraints and queues

Modeling shift schedules and machine failures

Evaluating and improving system performance through automation

Presenting results using KPIs and efficiency metrics
