# ECG Signal Analysis

## 📌 Overview
This project analyzes an ECG signal to detect **R-peaks** and estimate heart rate. It loads real ECG data, processes the signal, and visualizes the results with peak detection.

## 📂 Dataset
- The ECG data is sourced from:  
  [Py-ECG-Detectors Example Data](https://raw.githubusercontent.com/berndporr/py-ecg-detectors/master/example_data/ECG.tsv)
- The dataset contains raw ECG signals sampled at **250 Hz**.

## 📊 Features
✅ Load ECG signal from a dataset  
✅ Detect **R-peaks** using `scipy.signal.find_peaks`  
✅ Estimate **Heart Rate (BPM)**  
✅ **Zoom into a specific time frame (0-20s)**  
✅ Visualize ECG with detected R-peaks  

## 🚀 Installation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-repo/ecg-analysis.git
cd ecg-analysis
```
### **2️⃣ Install Dependencies**
```bash
pip install numpy pandas matplotlib scipy
```

## 📝 Usage
### **Run the Python Script**
```bash
python ecg_analysis.py
```

## 🖼️ Output Visualization
- The script generates a plot showing ECG waveforms with **detected R-peaks (red stars)**.
- The zoomed-in plot focuses on **0-20 seconds** for detailed analysis.

## 📈 Example Output
!ECG Plot![image](https://github.com/user-attachments/assets/67ba0263-3679-4ce4-9e20-5b6ad1371ad4)


## 🏆 Results
- **Heart Rate Calculation** (BPM) using R-peak intervals.
- **Detected Peaks** are marked on the ECG waveform.

## 🤝 Contributions
Feel free to fork this repo and submit a pull request if you have any improvements!

## 📜 License
This project is open-source and licensed under the **MIT License**.

