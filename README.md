# GESTURE-RECOGNITION
Real-time Gesture Recognition on ESP32 + MPU6050 using Edge Impulse. Captures motion data, trains ML models, and classifies gestures for smart IoT and automation.
# ✋ Gesture Recognition Project

This project demonstrates **real-time hand gesture recognition** using an **ESP32 + MPU6050 motion sensor** and **Edge Impulse**. The system captures motion data, trains ML models, and classifies gestures instantly on embedded devices.  

---

## 🚀 Features
- Captures gesture data with MPU6050 sensor.  
- Uses **Edge Impulse** to train ML models on motion data.  
- Deploys trained models as Arduino libraries for ESP32.  
- Recognizes and classifies gestures in real time.  

---

## 🔧 Workflow
1. **Setup**  
   - Connect ESP32 with MPU6050 sensor.  
   - Install **Edge Impulse CLI** on your computer.  

2. **Data Acquisition**  
   - Forward live motion data from ESP32 to Edge Impulse.  
   - Record gestures (e.g., *up-down, side, rest*).  
   - Collect at least 3 minutes per gesture.  

3. **Impulse Design**  
   - Add **Spectral Features** (processing block).  
   - Add **Classifier** (learning block).  

4. **Feature Generation**  
   - Autotune parameters.  
   - Generate features from gesture data.  

5. **Model Training**  
   - Train classifier with ~30 cycles.  
   - Analyze training accuracy.  

6. **Testing**  
   - Validate with 80/20 train-test split.  
   - Test predictions with Model Testing tab.  

7. **Deployment**  
   - Deploy as Arduino Library.  
   - Import library in Arduino IDE.  
   - Upload deployment + classification code.  
   - Run → gestures detected in Serial Monitor.  

---

## 🌍 Real-World Applications
- 🖐️ **IoT Control** – Trigger devices using gestures.  
- 🎮 **Gaming** – Use hand motions as inputs.  
- 🧑‍🏫 **Education** – Teach interaction via gestures.  
- 🤖 **Robotics** – Control robots with simple motions.  
- ♿ **Accessibility** – Alternative input for disabled users.  

---

## 📂 Repository Structure
