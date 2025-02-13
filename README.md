# ECG & PPG Signal Segmentation and Rhythm Analysis  

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)  
[![NumPy](https://img.shields.io/badge/Library-NumPy-orange.svg)](https://numpy.org/)  
[![SciPy](https://img.shields.io/badge/Library-SciPy-lightgrey.svg)](https://scipy.org/)  
[![Pandas](https://img.shields.io/badge/Library-Pandas-green.svg)](https://pandas.pydata.org/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

## 📌 Project Description  
This project focuses on **segmenting ECG & PPG signals, assessing signal quality, and performing rhythm analysis** to identify differences between sinus rhythm and atrial fibrillation. The methods include **non-overlapping/overlapping segmentation, ensemble averaging, time interval computation, and rhythm visualization**.  

## 📂 Features  
✅ **Segment ECG & PPG signals** into 10-second windows (supports overlapping & non-overlapping)  
✅ **Compute ensemble-averaged heartbeats** and visualize them  
✅ **Extract key time intervals** from the ECG & PPG waveforms (T-wave & diastolic peak)  
✅ **Develop a rhythm analysis metric** to differentiate sinus rhythm from atrial fibrillation  
✅ **Visualize rhythm differences** to support atrial fibrillation detection algorithms  

## 📝 Methodology  
1️⃣ **Signal Segmentation:**  
   - Divide signals into **10-second non-overlapping segments**  
   - Allow flexibility for **overlapping segmentation**  

2️⃣ **Ensemble Averaging of Heartbeats:**  
   - Align detected beats from peak maxima  
   - Overlay and compute **sample-wise averaged heartbeats**  

3️⃣ **Time Interval Computation:**  
   - Identify **T-wave from ECG**  
   - Detect **diastolic peak from PPG**  

4️⃣ **Rhythm Analysis for Sinus Rhythm vs. Atrial Fibrillation:**  
   - Develop **a visualization/metric** to distinguish between the two rhythms  
   - Not a full detection pipeline, but a **foundation for AFib detection algorithms**  

## 📊 Visualization  
- **Segmented ECG & PPG signals**  
- **Overlay of ensemble-averaged waveforms**  
- **Time intervals marked on ECG & PPG signals**  
- **Comparison of sinus rhythm vs. atrial fibrillation signals**  
