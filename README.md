# Modular Simulation of a BBM92 Receiver Subsystem

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Performance Analysis of Entanglement-Based Quantum Key Distribution Protocols**

---

## 📘 What is this repository?

This repository contains the full code and analysis accompanying the project _Modelling and Performance Analysis of Entanglement-Based Quantum Key Distribution Protocols_. The primary objective of this study is to develop a modular software simulation of a BBM92 Receiver Subsystem.

The architecture is designed to strictly separate the Source, Channel, and Receiver modules. The simulation employs a hybrid approach—computing valid signal rates directly in Python whilst calculating noise rates analytically—to analyse key performance metrics like the Quantum Bit Error Rate (QBER) and Secret Key Rates. It actively compares the performance of current-generation Silicon Avalanche Photodiodes (Si-APDs) against future Superconducting Nanowire Single-Photon Detectors (SNSPDs). 

📝 **You can read the full report in the repository: [`Simulation_of_a_Modular_BBM92_Receiver_Susbsystem-6.pdf`](Simulation_of_a_Modular_BBM92_Receiver_Susbsystem.pdf)**

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE.txt](LICENSE.txt) file for details.

When using this code, please:  
- Retain the original copyright notice  
- Attribute by linking back to this repository (e.g., `Modular Simulation of a BBM92 Receiver Subsystem by Elizabeth Birch Hardwick`)

---

## 📁 Repository structure

    📄 BB92_receiver_simulation.ipynb              # Core simulation of the receiver subsystem and channel analysis
    📄 Simulation_of_a_Modular_BBM92_Receiver_Susbsystem-6.pdf  # Full project report
    📄 requirements.txt                            # List of required Python packages
    📄 LICENSE.txt                                 # MIT License
    📄 README.md                                   # This file

---

## 📓 Usage

Clone the repository and install dependencies:

    git clone https://github.com/elizabethbirchhardwick/BBM92_receiver_simulation.git
    pip install -r requirements.txt

Launch the Jupyter notebook:

    jupyter notebook BB92_receiver_simulation.ipynb

Inside the notebook, you will find:

- 📈 **A fully modular simulation framework separating Source, Channel, and Receiver components**
- 🧠 **A hybrid Monte Carlo and analytical approach to drastically reduce computation times**
- 🧪 **Hardware comparisons between Si-APDs (60% efficiency) and SNSPDs (>90% efficiency)**
- 🌬️ **An adaptive sampling strategy to optimise performance in high-loss environments (above 45 dB)**
- 📊 **Detailed noise contribution and sensitivity analyses**

All code cells are pre-run for convenience, but you are encouraged to experiment and build complex channel models using this receiver framework!

---

## 💬 Support

For questions or suggestions, feel free to reach out:
📧 **elizabethbirchhardwick@gmail.com**
🚀 Or open an issue on [GitHub](https://github.com/elizabethbirchhardwick/BBM92_reiceiver_simulation/issues)
