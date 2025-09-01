# 🚨 Real-Time Violence Detection in Surveillance Systems  

## 📌 Project Overview  
Detection of violent events in surveillance footage plays a **critical role** in law enforcement and city safety.  
This project proposes a **real-time deep learning-based violence detector** that combines **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM)** networks to ensure:  
- ⚡ **Fast response time**  
- 🎯 **High accuracy**  
- 🌍 **Generality across diverse video sources and formats**  

---

## 🎯 Objectives  
- Develop a **real-time system** capable of detecting violent activities in surveillance videos.  
- Ensure **robustness across different video sources** and formats.  
- Balance **speed, accuracy, and generalization** for practical deployment.  

---

## 🧠 Methodology  
The proposed model is based on **Deep Learning architectures**:  
- **CNN (Convolutional Neural Networks)** → Extract **spatial features** from individual video frames.  
- **LSTM (Long Short-Term Memory networks)** → Capture **temporal relations** between consecutive frames to understand ongoing activities.  

📌 This hybrid CNN-LSTM framework enables effective violence detection by combining **visual patterns** (who/what is in the frame) and **temporal patterns** (how actions evolve).  

---

## 🛠 Tools & Technologies  
- **Python**  
- **TensorFlow / Keras** (for deep learning models)  
- **OpenCV** (for video processing)  
- **NumPy, Pandas** (for data handling)  
- **Matplotlib / Seaborn** (for visualization)  

---

## 📂 Dataset  
- The system is trained and tested on publicly available **violence detection datasets** (e.g., Hockey Fight Dataset, Movies Dataset, or CCTV footage datasets).  
- Dataset includes both **violent** and **non-violent** video samples in varying resolutions and formats.  

---

## 🚀 Implementation Workflow  
1. **Data Preprocessing**  
   - Extract frames from video sequences.  
   - Resize and normalize frames for CNN input.  

2. **Feature Extraction (CNN)**  
   - Train CNN to capture **spatial features** from each frame.  

3. **Temporal Modeling (LSTM)**  
   - Feed frame-wise CNN features into LSTM for **sequence analysis**.  

4. **Classification**  
   - Output binary decision: **Violence** ⚔️ or **Non-Violence** 🕊️.  

5. **Real-Time Testing**  
   - Apply the trained model to **live CCTV/surveillance streams**.  

---

## 📊 Evaluation Metrics  
- **Accuracy** → Correct classification rate.  
- **Precision / Recall / F1-score** → Balance between false alarms and missed detections.  
- **Latency (Response Time)** → Speed of model inference in real-time.  

---

## 📚 Applications  
- **City Surveillance Systems** for crime prevention.  
- **Public Transport Safety** (buses, metros, stations).  
- **Event Security** in stadiums, concerts, and gatherings.  
- **Smart Policing Tools** for real-time law enforcement alerts.  

---

✨ This project highlights how **Deep Learning (CNN + LSTM)** can support **real-time violence detection**, helping cities build **safer environments**.  
