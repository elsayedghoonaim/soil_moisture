# Soil Moisture Analysis and Prediction

## Project Overview

This project focuses on analyzing and predicting soil moisture levels using machine learning techniques. We utilize a dataset containing information about soil composition, geographical location, and moisture levels to build a predictive model.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Data](#data)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Installation

To run this project, you'll need Python 3.7+ and the following libraries:

```
pip install numpy pandas matplotlib seaborn folium scikit-learn tensorflow
```

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/soil-moisture-analysis.git
   ```
2. Navigate to the project directory:
   ```
   cd soil-moisture-analysis
   ```
3. Open and run the Jupyter notebook:
   ```
   jupyter notebook soil_moisture_analysis.ipynb
   ```

## Data

The dataset (`updated_data.csv`) includes the following features:
- Time
- Latitude
- Longitude
- Clay content
- Sand content
- Silt content
- Auxiliary soil moisture measurement
- Target soil moisture measurement

## Methodology

1. Data Preprocessing: Cleaning and preparing the dataset for analysis.
2. Exploratory Data Analysis (EDA): Visualizing data distributions and relationships.
3. Feature Engineering: Creating new features and selecting relevant ones.
4. Model Development: Building and training a deep learning model using TensorFlow.
5. Model Evaluation: Assessing the model's performance using various metrics.

## Results

Our model achieves a Mean Absolute Error (MAE) of approximately 0.0576 on the test set, indicating a reasonably accurate prediction of soil moisture levels.
