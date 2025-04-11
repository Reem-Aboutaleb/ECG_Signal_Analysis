# ❤️ ECG Signal Analysis and Heart Rate Visualization

This project analyzes **ECG signals** and visualizes the corresponding **heart rate** using Python. It demonstrates core biomedical signal processing concepts and extracts key cardiac features such as the **QRS complex**, **intervals**, and **mean heart rate**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reem-Aboutaleb/ecg-signal-analysis/blob/main/ecg_analysis.ipynb)

---

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Platform](https://img.shields.io/badge/Platform-Colab%20%7C%20Jupyter-yellow)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> 🩺 **Keywords**: ECG, QRS Complex, Heart Rate, Python, Biomedical Signal Processing, Cardiac Intervals, Data Visualization

---

## 📚 Table of Contents

- [Overview](#-ecg-signal-analysis-and-heart-rate-visualization)
- [Objectives](#-objectives)
- [Tools Used](#-tools-used)
- [Features](#-features)
- [Results](#-results)
- [How to Run](#-how-to-run)
- [Future Work](#-future-work)
- [Key Takeaways](#-key-takeaways)
- [Author](#-author)

---

## 🧠 Overview

This project focuses on analyzing ECG waveforms and visualizing the heart rate over time. It includes filtering and timing analysis, visualizes beat-to-beat trends, and calculates fundamental cardiac intervals using Python.

---

## 🎯 Objectives

- Extract and analyze ECG waveform components:
  - P wave, QRS complex, and T wave durations/amplitudes  
  - PR, QT, and RR intervals  
  - Mean heart rate
- Visualize clean ECG signals and heart rate variation
- Demonstrate filtering, peak identification, and interval logic

---

## 🛠 Tools Used

- **Programming Language**: Python 3.11  
- **Libraries**: Pandas, NumPy, Matplotlib

---

## ✨ Key Features

- ✅ Custom signal filtering and cardiac interval extraction  
- ✅ Visualization of raw ECG signal + calculated heart rate  
- ✅ PR, QT, and RR interval estimations  
- ✅ Reusable code structure for clinical or wearable ECG analysis

---

## 📊 Results

### 🖼️ ECG Signal and Heart Rate Plot

<img src="images/ECG Signal and Heart Rate.png" alt="ECG Plot" width="600"/>

---

## 🎥 Demo

Here’s a preview of the ECG analysis pipeline in action:

<img src="images/ecg_demo.gif" alt="ECG Signal Demo" width="600"/>

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Reem-Aboutaleb/ecg-signal-analysis.git
cd ecg-signal-analysis
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib
```

3. Open `ecg_analysis.ipynb` in Jupyter or Colab and run the cells in order.

---

## 🔭 Future Work

- Add QRS peak detection with automatic beat segmentation  
- Compute **Heart Rate Variability (HRV)** metrics  
- Apply to real-world ECG datasets (e.g., PhysioNet, MIT-BIH)  
- Compare ECG under resting vs. stress tasks  
- Build a live dashboard with **Streamlit**

---

## 📌 Key Takeaways

- Developed a practical pipeline for clinical ECG analysis  
- Gained hands-on experience with signal filtering and timing  
- Visualized ECG and heart rate data using Matplotlib  
- Prepared foundation for HRV, diagnosis, and real-time ECG tools

---

## 👩‍⚕️ Author

**Reem Aboutaleb**  
Biomedical Engineering M.S. Candidate @ NYU Tandon  
📧 Reemwalid222@gmail.com  
🔗 [GitHub](https://github.com/Reem-Aboutaleb) | [LinkedIn](https://www.linkedin.com/in/reem-aboutaleb)

---

⭐ *“The ECG tells the rhythm of the heart — and the story of the body.”*

