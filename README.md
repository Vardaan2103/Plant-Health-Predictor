# Plant Health Predictor

A comprehensive web application developed using Streamlit to assist in plant health management. This tool provides insights into leaf disease classification, soil water requirements, soil acidity levels, and disease risk predictions using machine learning models.

## Features

1. **Leaf Disease Classification**: Identifies whether a plant leaf is "Healthy," affected by "Powdery Mildew," or affected by "Rust" using a pre-trained deep learning model.
2. **Soil Water Requirement Prediction**: Predicts watering needs based on soil moisture, temperature, rainfall, and air humidity using an SVM model.
3. **Soil Acidity Prediction**: Determines soil acidity levels using a KNN model based on soil nutrient values.
4. **Disease Risk Assessment**: Predicts potential disease risk using a Random Forest model, based on environmental factors like soil humidity and temperature.
5. **Batch Prediction**: Supports CSV batch uploads for bulk predictions and provides downloadable results.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Plant-Health-Predictor.git
   cd Plant-Health-Predictor
