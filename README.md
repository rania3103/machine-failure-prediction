# 🦾⚙️🤖🔎M̳a̳c̳h̳i̳n̳e̳ ̳F̳a̳i̳l̳u̳r̳e̳ ̳P̳r̳e̳d̳i̳c̳t̳i̳o̳n̳ ̳u̳s̳i̳n̳g̳ ̳S̳e̳n̳s̳o̳r̳ ̳D̳a̳t̳a̳👨🏻‍💻🖥️🔧🎰

<img src="img.jpg">

## Overview 🔍

This project aims to predict machine failures using sensor data collected from various machines. The goal is to build a robust predictive model that can help in preventive maintenance by identifying potential machine failures before they occur. The project explores different machine learning algorithms and evaluates their performance in predicting machine failures.

## Dataset 🗂️

The dataset contains sensor readings from multiple machines, along with labels indicating whether a machine failed (`fail` = 1) or not (`fail` = 0). The dataset includes the following features:
- `VOC`: Volatile Organic Compounds level
- `AQ`: Air Quality index
- `TempMode`: Temperature mode
- `RP`: Rotation Pressure
- `IP`: Internal Pressure
- `Temperature`: Temperature in degrees Celsius
- `Footfall`: Footfall count
- `CS`: Control System readings
- `USS`: Ultrasonic Sensor readings
- `fail`: Target variable indicating machine failure
The dataset used can be found on Kaggle [here](https://www.kaggle.com/datasets/umerrtx/machine-failure-prediction-using-sensor-data).

## Tools Used 🛠️
<p>  
  <img alt="Python" src="https://img.shields.io/badge/python-306998.svg?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white"/>
  <img alt="Scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img alt="Seaborn" src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=Seaborn&logoColor=white"/>

</p>

- **Pandas:** Data manipulation and analysis.
- **Seaborn:** Statistical data visualization.
- **Matplotlib:** Plotting library for Python.
- **Scikit_learn:**Machine learning library for Python.

## Project Workflow 🎯
- **Data exploration:**
  - Load and inspect the dataset.
  - Visualize feature distributions and check for missing values.
  - Analyze feature correlations.
- **Data preprocessing:** 
  - Standardize features.
  - Split data into training and test sets.
- **Model training and evaluation:**
  - Train multiple machine learning models (Logistic Regression, Random Forest, Gradient Boosting).
  - Perform hyperparameter tuning using GridSearchCV.
  - Evaluate model performance confusion matrix and  classification report.
  - Analyze feature importance.
  
## Findings✨🕵
- The Logistic Regression model achieved an **accuracy of 89%**, with key features such as VOC and AQ showing significant importance in predicting machine failures.
- **Volatile Organic Compounds(VOC) and Air Quality(AQ)** are positively associated with machine failure prediction indicating environmental factors' influence on machine performance..
- **Temperature Mode (tempMode), Reactive Power (RP), and Inductive Power (IP)** do not significantly impact the prediction.
- **Footfall, Cooling System (CS), and Unscheduled Service (USS)** negatively influence failure prediction. 

## 👩‍💻 Author

- GitHub: [@rania3103](https://github.com/rania3103)
- LinkedIn: [LinkedIn](https://linkedin.com/in/rania-abassi-24105a249)
