# pad-screening-device
Arduino-based device, mathematical modeling, and machine learning for Peripheral Arterial Disease screening
# PAD Screening System

🩺 This repository contains code, models, and documentation for my master's degree project on Peripheral Arterial Disease (PAD) screening using a novel, low-cost device and computational analysis.

## 🔧 Components

### 1. Device Hardware (`device-hardware/`)
Arduino-based system to measure blood pressure and pulse with:
- Sensors for pressure and PPG
- Bluetooth connection
- Low-cost components
- Controlled via smartphone

### 2. Smartphone App (`smartphone-app/`)
Android app developed with MIT App Inventor:
- Guides user through ABI measurement
- Displays results and instructions
- Sends data to clinicians

### 3. Mathematical Modeling (`mathematical-model/`)
Bond Graph modeling of blood pressure acquisition:
- Modeled effects of body position and disease
- Simulations in MATLAB/Simulink
- Results help refine device calibration

### 4. ML Analysis (`ml-analysis/`)
Applied ML models to classify cardiovascular disease using public dataset:
- Random Forest, SVM, Naive Bayes
- ROC AUC: up to 0.90 after SMOTE
- Python-based, uses scikit-learn and pandas

## 📄 Dissertation
Full methodology and results available in the original thesis (in Portuguese).

## 🧪 Future Work
- Validate the device post-pandemic
- Integrate ML model into a web dashboard
- Expand clinical dataset
