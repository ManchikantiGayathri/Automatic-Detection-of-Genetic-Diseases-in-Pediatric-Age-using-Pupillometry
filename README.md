# Automatic-Detection-of-Genetic-Diseases-in-Pediatric-Age-using-Pupillometry
## Overview
This project presents a machine learning and deep learning based system for the early detection of genetic diseases in pediatric patients using pupillometry. The system analyzes pupil response data collected under controlled lighting conditions and predicts the presence of genetic disorders through automated classification techniques.

The application uses Python with a Tkinter-based GUI and implements multiple algorithms including Support Vector Machine (SVM), Ensemble Learning, Extreme Learning Machine (ELM), LSTM, and BiLSTM for disease prediction. The project focuses on providing a non-invasive, cost-effective, and efficient alternative to traditional diagnostic methods, making it especially suitable for children.

---

## Purpose
The main purpose of this project is to:
- Detect genetic diseases in children at an early stage
- Reduce dependency on invasive and expensive diagnostic methods
- Improve diagnosis accuracy using AI and machine learning
- Provide a quick and user-friendly healthcare support system

---

## Features
- Upload and preprocess pupillometry datasets
- Feature extraction and reduction
- Disease prediction using ML and DL models
- Accuracy comparison graph for different algorithms
- User-friendly graphical interface using Tkinter
- Visualization of pupil diameter and classification results

---

## Tech Stack
- **Programming Language**: Python
- **GUI Framework**: Tkinter
- **Machine Learning**: Scikit-learn, ELM
- **Deep Learning**: TensorFlow / Keras
- **Data Processing**: Pandas, NumPy
- **Visualization** : Matplotlib

---

## Machine Learning & Deep Learning Models Used
- Support Vector Machine (SVM)
- Ensemble Voting Classifier
- Extreme Learning Machine (ELM)
- Long Short-Term Memory (LSTM)
- Bidirectional LSTM (BiLSTM)

---

## Data Source
The project uses pupillometry datasets containing pupil response measurements collected under controlled lighting conditions.
### Dataset Includes:
- Maximum pupil size
- Minimum pupil size
- Pupil dilation variation
- Change rate
- Latency
- Mean constriction velocity
Data from both left and right eyes is used for disease classification.

---

## Project Workflow
1. Upload Dataset
2. Run Data Filtering
3. Extract Important Features
4. Reduce Unnecessary Features
5. Train ML/DL Models
6. Evaluate Accuracy and Performance
7. Generate Graphs and Visualizations
8. Predict Disease from Test Data

---

## System Architecture
The system follows the below process:
- Data Acquisition
- Data Filtering
- Feature Extraction
- Feature Reduction
- Model Training
- Ensemble Classification
- Disease Prediction
- Result Visualization

---

## Output
The system provides:
- Prediction results as:
    - Disease Detected
    - No Disease Detected
- Accuracy scores for all algorithms
- Sensitivity and specificity analysis
- Accuracy comparison graph
- Pupil diameter visualization graph

---

## Advantages
- Non-invasive diagnosis
- Faster disease detection
- Cost-effective approach
- User-friendly interface
- Suitable for pediatric healthcare
- Improved accuracy using ensemble and deep learning models

--- 

## Future Enhancements
- Integration with real-time pupillometry devices
- Deployment as a web application
- Cloud-based disease monitoring
- Improved deep learning models for higher accuracy
- Larger and more diverse datasets for better prediction
