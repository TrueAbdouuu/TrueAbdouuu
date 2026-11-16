# Abderrahmane El Felsoufi

**Embedded systems & robotics → machine learning.**
I build complete instruments: the mechanics, the PCB, the firmware, and the model that makes
sense of the data coming off them. Most ML work starts with a dataset someone else collected —
mine usually starts with a sensor I had to design first.

🎓 M.Sc. Computer Science (Artificial Intelligence), Université Laval (2026–2027) ·
📍 Québec, Canada
🔗 [LinkedIn](https://www.linkedin.com/in/abderrahmane-el-felsoufi) · ABELF14@ulaval.ca

---

## Featured work

### 🐁 Autonomous behavioural rig for mouse string-pulling
*Mitacs Globalink Research Internship — Douglas Research Centre, McGill University (May–Aug 2026)*

A complete experimental apparatus for automated rodent string-pulling studies, built end to end:
mechanics, electronics, software, and the model that reads the resulting video.

- **Mechanical** — adjustable-resistance pulling mechanism, cage, pulley and shaft designed in
  Shapr3D/SolidWorks and 3D-printed through several revisions.
- **Electronics** — custom PCB; HX711 load cell for pull force, quadrature encoder for string
  displacement, RFID for automatic per-animal identification.
- **Software** — headless autonomous operation on Raspberry Pi. Multi-process Python architecture
  so acquisition, video capture and the reward state machine run concurrently without dropping
  samples; live GUI for supervision, CSV logging per trial.
- **Modelling** — recorded the video dataset with a Pi camera and trained a CNN-based
  **DeepLabCut** model for markerless detection and tracking of mouse movement.

`Python` · `Raspberry Pi` · `DeepLabCut` · `PyTorch` · `OpenCV` · `KiCad` · `multiprocessing`

### 🌍 Real-time IoT air-quality monitoring
*ARC AIR Laboratory, UM6P (Apr–Sep 2025) — supervised by Hicham Mastouri*

- Real-time acquisition system integrating CO₂, VOC and particulate-matter sensors over
  **LoRa** with **ESP32** nodes.
- Predictive data pipelines and anomaly detection over large-scale environmental datasets.
- Live dashboards deployed for the 2nd International Conference on Chemical Weather and
  Chemical Climate (**CWCC 2025**).

`ESP32` · `LoRa` · `time series` · `anomaly detection` · `dashboards`

### 👁️ Computer vision for robotics
*ENSEA — 198 h project (Sept 2024 – Apr 2025)*

Object detection and tracking with **OpenCV** and **PyTorch** running on a **Jetson Orin Nano**,
with image preprocessing and feature extraction, plus navigation and object localisation via **A\***.

`PyTorch` · `OpenCV` · `Jetson Orin Nano` · `path planning`

### ⚙️ PWM expander — custom board + firmware
*ENSEA — 150 h project*

Custom PCB and embedded firmware providing **10 independent PWM channels** for servo-motor
control, with real-time control and data acquisition.

`C/C++` · `embedded firmware` · `KiCad` · `PCB design`

### 🔤 NLP — incident report classification
*Université Laval, IFT-4022*

9-class classification of workplace-incident reports on a heavily imbalanced corpus. Naive Bayes
vs. logistic regression over uni+bigram features, hyperparameters selected by 5-fold CV on the
training set only. Best test accuracy **0.714**; macro-F1 of **0.532** quantifies how poorly the
rare classes are served — reported rather than hidden behind the weighted average. All 9 latent
classes interpreted from model weights.

`scikit-learn` · `NLP` · `model evaluation`

### ⚡ Piezoelectric floor tile
*104 h project — energy harvesting from footsteps*

Modelling and simulation of a piezoelectric floor generating electricity from foot traffic;
mechanical deformation and energy-conversion analysis in **MATLAB** and **COMSOL Multiphysics**.

`MATLAB` · `COMSOL` · `energy harvesting`

---

## Toolbox

| | |
|---|---|
| **Languages** | Python, C/C++, MATLAB, VHDL, SQL, Java |
| **ML / CV** | PyTorch, TensorFlow, scikit-learn, OpenCV, DeepLabCut, Transformers |
| **Embedded** | Raspberry Pi, ESP32, Jetson Orin Nano, LoRa, ROS/ROS2, Linux |
| **Hardware** | KiCad, Altium, EasyEDA, LTspice, PSpice, Simulink |
| **Mechanical** | Fusion 360, SolidWorks, Shapr3D, 3D printing, laser cutting |

## Certifications

- **Natural Language Processing Specialization** — DeepLearning.AI
- **Machine Learning / Supervised Learning: Regression and Classification** — Stanford University & DeepLearning.AI

## Beyond the lab

- **Co-founder**, TechBotsMaroc — independent robotics association
- **Communication Manager**, QUANTUUM (quantum computing student association)
- **Communication Manager**, ARES (robotics association)

## Languages

French (fluent) · English (fluent, TOEIC 940) · Arabic (native) · German (beginner)
