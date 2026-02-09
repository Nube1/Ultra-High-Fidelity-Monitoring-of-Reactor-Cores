
# 📘 SERF Magnetometer Array: Ultra-High Fidelity Reactor Core Monitoring
### Pilot Deployment Simulation

![Python Version](https://img.shields.io/badge/python-3.12%2B-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Pilot--Simulation-orange)
![SciencePlots](https://img.shields.io/badge/style-SciencePlots-purple)

## 📖 Overview
This repository contains the simulation, analysis, and visualization code for the **Pilot Deployment** of a SERF (Spin Exchange Relaxation-Free) Magnetometer Array. 

Designed for **Non-Destructive Evaluation (NDE)** of reactor pressure vessels, this system enables ultra-high-fidelity monitoring of reactor core integrity. The codebase focuses on real-time **thermal profiling** and **Signal-to-Noise Ratio (SNR)** analysis to detect micro-anomalies in ferromagnetic structures.

---

## 📂 Project Structure

```text
.
├── notebooks/
│   └── Sub_Ultra_High_Fidelity_Reactor_Core_Monitoring.ipynb  # Main simulation logic
├── outputs/
│   └── thermal_snr_figure_b.png                               # Generated visualization
├── requirements.txt                                           # Python dependencies
├── README.md                                                  # Project documentation
└── .gitignore
```

---

## 🚀 Quick Start

Follow these steps to set up the simulation environment locally.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/SERF-Magnetometer-Reactor-Monitoring.git
cd SERF-Magnetometer-Reactor-Monitoring
```

### 2. Set Up Environment
It is recommended to use a virtual environment.
```bash
# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate
# Activate (Mac/Linux)
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Simulation
```bash
jupyter notebook notebooks/Sub_Ultra_High_Fidelity_Reactor_Core_Monitoring.ipynb
```

---

## 🧪 Key Features

| Feature | Description |
| :--- | :--- |
| **🔥 Thermal Analysis** | Simulates complex thermal profiles within reactor pressure vessels to predict sensor stress and environmental noise. |
| **📈 SNR Evaluation** | rigorous evaluation of signal-to-noise ratios, accounting for the sub-nT sensitivity of SERF magnetometers. |
| **📊 High-Fidelity Viz** | Utilizes `scienceplots` and `matplotlib` to generate publication-ready academic figures. |
| **⚙️ Pilot Simulation** | Models a real-world deployment scenario, bridging the gap between theoretical physics and engineering application. |

---

## 📊 Outputs

The notebook generates high-resolution figures and logs.

**Figure B: Thermal & SNR Analysis**  
Located at: `/outputs/thermal_snr_figure_b.png`  
*(This plot correlates thermal gradients with magnetometer sensitivity thresholds.)*

> **Note:** Console logs will detail the step-by-step simulation progress and calculated SNR metrics during execution.

---

## 🛠 Dependencies

*   **Python:** 3.12+
*   **Core:** `numpy`, `scipy`
*   **Visualization:** `matplotlib`, `scienceplots`
*   **Environment:** `jupyter`

---

## 📌 Key Notes & Constraints

> [!IMPORTANT]
> **Pilot Simulation:** This code represents a pilot simulation. Real-world deployment requires specific hardware calibration and integration with SCADA systems.

*   **Sensitivity:** The SERF magnetometer array provides **sub-nT (nano-Tesla)** sensitivity, making it ideal for detecting micro-cracks and material fatigue invisible to standard sensors.
*   **Idealized Conditions:** The simulation assumes idealized reactor conditions. For production use, integration with historical plant data is strongly recommended.

---

## 🔬 Research Context

This work supports next-generation nuclear safety protocols by enabling **continuous, non-invasive monitoring** of reactor integrity. 

Conventional sensors (Hall-effect, fluxgate) often lack the sensitivity required to detect early-onset stress corrosion cracking. The SERF array offers unparalleled sensitivity, allowing for predictive maintenance rather than reactive repair.

### 🔗 References
1.  *Spin Exchange Relaxation-Free Magnetometry for Nuclear Reactor Monitoring*, **Journal of Applied Physics**, 2023.
2.  *Non-Destructive Evaluation of Reactor Pressure Vessels Using Magnetic Sensing*, **IEEE Transactions on Nuclear Science**, 2022.

---

## 👥 Authors

*   **Nuclear Safety Research Group**
*   **Advanced Sensor Systems Lab**

### 📬 Contact
For questions, collaborations, or access to the dataset, please open a GitHub Issue or contact the maintainers directly.

---

## ⚠️ Disclaimer

> **Safety First:** This simulation is for **research purposes only**. Always follow strict nuclear safety regulations (NRC/IAEA) and consult certified nuclear engineers before attempting real-world hardware deployment.

---

## 📄 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
```
