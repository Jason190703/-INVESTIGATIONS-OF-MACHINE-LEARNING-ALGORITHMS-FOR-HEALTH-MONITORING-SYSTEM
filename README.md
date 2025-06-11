## INVESTIGATIONS OF MACHINE LEARNING ALGORITHMS FOR HEALTH MONITORING SYSTEM

This research explores the use of machine learning algorithms—specifically **Decision Tree** and **Support Vector Machine (SVM)**—to predict an individual's health status based on vital signs such as **Temperature (F), SpO2 (%), Heart Rate (bpm), Weight (kg), Gender, and Age**.

The models are evaluated based on prediction accuracy and computation time, achieving up to **98% accuracy with Decision Tree** and **91% with SVM** on a dataset of 10,000+ real-world-style records.

---

## OBJECTIVES

- Predict if a patient is **Healthy**, **At Risk**, or **Unhealthy**
- Compare the performance of **Decision Tree** vs **SVM**
- Support real-time patient input for instant prediction
- Display possible contributing factors for poor health status using model-driven inference (not hardcoded thresholds)

---

## PROJECT STRUCTURE

|              File                       |                Description                |
|-----------------------------------------|-------------------------------------------|
| `health_monitoring_investigation.ipynb` | Jupyter Notebook with full implementation |
| `health_monitoring_dataset_10k.csv`     | Dataset used for training and testing     |
| `README.md`                             | Project documentation                     |

---

## FEATURES

- Data preprocessing and encoding
- Model training, evaluation, and comparison
- Accuracy and prediction time measurement
- Compact visualization of model performance
- Real-time prediction with reason extraction for non-healthy cases

---

## MODEL PERFORMANCE

| Model         | Accuracy | Prediction Time |
|---------------|----------|-----------------|
| Decision Tree | 98%      | Fast            |
| SVM           | 91%      | Slower          |

**Best performing model:** `Decision Tree`

---

## HOW TO RUN

1. Clone the repository:
2. Open `health_monitoring_investigation.ipynb` in Jupyter (download the dataset and change the file path in the code)
3. Run the cell to train models and try real-time prediction.

---
