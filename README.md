# Medical Diagnostic Tool for Alzheimer's Disease Analysis

## Overview

This repository contains a comprehensive analysis of medical data aimed at identifying patterns and predictive indicators related to Alzheimer's disease and cognitive decline. The project utilises machine learning algorithms to assess cognitive performance through the Mini-Mental State Examination (MMSE) scores.

## About the Dataset

The dataset comprises medical records from 436 participants, including:
- **Demographic information**: Age, gender, handedness, education level
- **Socioeconomic data**: Socioeconomic status (SES)
- **Cognitive assessments**: Mini-Mental State Examination (MMSE) scores
- **Clinical measures**: Clinical Dementia Rating (CDR) scores
- **Brain imaging metrics**: 
  - Estimated Total Intracranial Volume (eTIV)
  - Normalised Whole Brain Volume (nWBV)
  - Atlas Scaling Factor (ASF)

## Machine Learning Approach

The project implements and compares five different regression algorithms to predict MMSE scores:

1. **Linear Regression** - A straightforward baseline approach
2. **Random Forest Regressor** - Ensemble method with feature importance analysis
3. **Gradient Boosting Regressor** - Advanced boosting technique
4. **Support Vector Regressor** - Non-linear regression with kernel methods

Each model is evaluated using standard regression metrics including Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared values.

## Key Features

- **Data preprocessing**: Handles missing values through median imputation for numerical features
- **Feature scaling**: Standardises features for optimal model performance
- **Hyperparameter tuning**: Implements GridSearchCV for model optimisation
- **Model comparison**: Comprehensive evaluation across multiple algorithms
- **Visualisation**: Clear charts and graphs for data exploration and results presentation

## Getting Started

### Prerequisites

Ensure you have Python 3.7 or higher installed on your system.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/OllyC1/Medical_Diagnostic_tool.git
   cd Medical_Diagnostic_tool
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook "AI assesment.ipynb"
   ```

2. Run all cells sequentially to:
   - Load and explore the dataset
   - Preprocess the data
   - Train multiple machine learning models
   - Compare model performance
   - Visualise results

## Results

The analysis demonstrates that different machine learning algorithms show varying effectiveness in predicting cognitive assessment scores. The Linear Regression model achieved the best performance with the lowest Mean Absolute Error, whilst ensemble methods like Random Forest provided valuable insights into feature importance.

## Contributing

We welcome contributions to improve this medical diagnostic tool. Please feel free to submit issues, feature requests, or pull requests.

## Licence

This project is licensed under the terms specified in the LICENSE file.

## Acknowledgements

This research contributes to the ongoing efforts in understanding cognitive decline and Alzheimer's disease progression through data-driven approaches. The work aims to support medical professionals in early detection and assessment of cognitive impairment.
