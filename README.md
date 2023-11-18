# Student Enrollment Prediction Model

## Overview

This Python script builds a machine learning model to predict student enrollment status based on various features. The model is trained using the RandomForestClassifier algorithm from scikit-learn. Additionally, it includes visualizations such as a confusion matrix and a scatter plot for better understanding.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Running the Code](#running-the-code)
- [Code Structure](#code-structure)
- [Data](#data)
- [Model Evaluation](#model-evaluation)
- [Visualizations](#visualizations)
- [Saved Model](#saved-model)
- [Optional: Loading the Model](#optional-loading-the-model)

## Setup

### Prerequisites

Ensure you have the following software installed:

- Python (>=3.6)
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

### Installation

Install the required dependencies using the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn joblib
```

## Usage

### Running the Code

1. Clone the repository:

```bash
git clone https://github.com/your_username/Student-Enrollment-Model.git
cd Student-Enrollment-Model
```

2. Run the Python script:

```bash
python enrollment_model.py
```

## Code Structure

- `enrollment_model.py`: The main script containing the machine learning model training, evaluation, and visualization code.
- `enrollment_model.pkl`: The serialized RandomForestClassifier model saved for future use.

## Data

The sample data used for model training is provided in the script as a hardcoded string. For real-world scenarios, replace this data with your dataset in CSV or Excel format.

## Model Evaluation

The script outputs the following:

- Confusion matrix
- Classification report

## Visualizations

The script generates visualizations:

- Confusion matrix heatmap
- Scatter plot of age and score

## Saved Model

The trained model is saved as `enrollment_model.pkl` for future use.

## Optional: Loading the Model

If needed, you can load the saved model later using the following:

```python
loaded_model = joblib.load('enrollment_model.pkl')
```
