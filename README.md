# 🌊 Flood Prediction System using Machine Learning

## Project Overview

Floods are among the most destructive natural disasters, causing severe damage to life, property, agriculture, and infrastructure. Timely prediction of flood events enables governments and disaster management authorities to take preventive actions and reduce losses.

This project develops a **Machine Learning-based Flood Prediction System** that predicts the likelihood of flood occurrence using historical weather data. Multiple supervised learning algorithms are trained and evaluated to identify the best-performing model. The selected model is integrated into a **Flask web application** that allows users to input weather parameters and instantly receive flood risk predictions.

The application is designed to be lightweight, user-friendly, and deployable on cloud platforms such as **IBM Cloud**.

---

# Features

- Predict flood occurrence using weather data
- Multiple Machine Learning models comparison
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier
- Automatic selection of best-performing model
- Flask-based web interface
- Real-time prediction
- Simple and responsive UI
- Ready for IBM Cloud deployment

---

# Problem Statement

Traditional flood forecasting methods often rely on manual analysis and complex simulations, which may not provide timely predictions.

This project uses historical meteorological data to train Machine Learning models capable of predicting flood events with high accuracy, enabling early warning systems and disaster preparedness.

---

# Objectives

- Collect historical flood and weather datasets
- Perform data preprocessing
- Train multiple Machine Learning models
- Compare model performance
- Select the best-performing classifier
- Save the trained model
- Build a Flask web application
- Deploy on IBM Cloud

---

# Technologies Used

## Programming Language

- Python 3.8+

## Machine Learning

- Scikit-Learn
- XGBoost
- NumPy
- Pandas

## Data Visualization

- Matplotlib
- Seaborn

## Web Development

- Flask
- HTML
- CSS
- JavaScript
- Bootstrap

## Deployment

- IBM Cloud
- GitHub

---

# Machine Learning Algorithms

The following supervised learning algorithms are implemented:

### Decision Tree

- Simple and interpretable
- Fast training

### Random Forest

- Ensemble learning
- Reduces overfitting
- Higher accuracy

### K-Nearest Neighbors (KNN)

- Instance-based learning
- Easy implementation

### XGBoost

- Gradient Boosting
- High prediction accuracy
- Best-performing model

---

# Dataset

The dataset contains historical weather observations and flood occurrence information.

### Input Features

- Annual Rainfall
- Seasonal Rainfall
- Cloud Visibility
- Temperature
- Humidity
- River Water Level (if available)
- Other meteorological parameters

### Target

- Flood Occurrence

Values:

- 1 → Flood
- 0 → No Flood

---

# Project Architecture

```
Historical Weather Dataset
            │
            ▼
Data Preprocessing
            │
            ▼
Feature Selection
            │
            ▼
Model Training
            │
            ▼
Model Evaluation
            │
            ▼
Best Model Selection
            │
            ▼
Model Serialization (.pkl)
            │
            ▼
Flask Web Application
            │
            ▼
Flood Prediction
```

---

# Project Structure

```
Flood-Prediction-System/

│
├── dataset/
│   └── flood.csv
│
├── models/
│   └── flood_model.pkl
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── model.ipynb
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Flood-Prediction-System.git
```

```bash
cd Flood-Prediction-System
```

---

## Create Virtual Environment

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Model Training

```bash
python train_model.py
```

The trained model will be saved inside:

```
models/flood_model.pkl
```

---

# Run Flask Application

```bash
python app.py
```

Open browser:

```
http://127.0.0.1:5000/
```

---

# Web Application Workflow

1. Open application
2. Enter weather details
3. Click Predict
4. Model processes data
5. Flood prediction displayed

---

# Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

| Model | Accuracy |
|--------|----------|
| Decision Tree | 91.40% |
| Random Forest | 94.80% |
| KNN | 92.15% |
| XGBoost | **96.55%** |

---

# Sample Prediction

### Input

Annual Rainfall: 1850 mm

Cloud Visibility: Low

Seasonal Rainfall: High

Humidity: 87%

Temperature: 26°C

### Output

```
Flood Likely
```

---

# Use Cases

## Scenario 1

### Early Flood Warning

Meteorologists enter current weather data.

The application predicts a high flood probability.

Authorities issue evacuation alerts.

---

## Scenario 2

### Disaster Resource Allocation

Disaster management teams monitor multiple districts.

Regions with higher flood probability receive priority support.

---

## Scenario 3

### Government Validation

Historical flood records are tested.

The XGBoost model achieves:

**96.55% Accuracy**

---

# Hardware Requirements

- Intel i3 Processor or higher
- 4 GB RAM minimum
- 2 GB Storage
- Internet Connection

---

# Software Requirements

- Windows/Linux/macOS
- Python 3.8+
- Flask
- Jupyter Notebook
- Anaconda (Optional)
- IBM Cloud Account

---

# Future Enhancements

- Live weather API integration
- GIS-based flood visualization
- SMS & Email alert system
- Mobile application
- Satellite image analysis
- Deep Learning models (LSTM)
- IoT sensor integration
- Rainfall forecasting
- Real-time dashboard
- Multi-language support

---

# Team Members

| Name | Role |
|------|------|
| **Pyla Hasitha** | Team Lead |
| Thimmapatruni Lavanya | Member |
| Mokshitha Burle | Member |
| Pydi Sri Vaishnavi | Member |
| Sushma Sajjala | Member |

---

# Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Classification Algorithms
- Model Evaluation
- Flask Development
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- XGBoost
- Python
- HTML
- CSS
- JavaScript
- IBM Cloud Deployment

---

# Future Scope

This project can be extended into a real-time intelligent disaster management platform by integrating live weather APIs, IoT sensors, satellite imagery, and cloud-based alert systems. The solution can support district-level monitoring, automated notifications, and resource planning to improve disaster preparedness and reduce flood-related losses.

---

# License

This project is developed for academic and educational purposes under the IBM SkillsBuild program.

---

# Acknowledgements

- IBM SkillsBuild
- Scikit-Learn
- XGBoost
- Flask
- NumPy
- Pandas
- Matplotlib
- Open Source Community

---
```
