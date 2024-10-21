# AgroFertilizer Disease Predictor

## Project Overview

**AgroFertilizer Disease Predictor** is a web-based application that predicts the optimal fertilizer for crops and identifies potential crop diseases based on user input. The system leverages machine learning models to provide accurate and helpful insights for farmers and agricultural enthusiasts.

## Features
- **Fertilizer Prediction**: Suggests the best fertilizer for a crop based on the user's input about soil condition and crop type.
- **Disease Detection**: Predicts common crop diseases by analyzing crop images using a deep learning model.
- **User-Friendly Interface**: A simple, intuitive interface for users to input details and receive predictions.
- **Machine Learning Models**: Utilizes trained models such as RandomForest and CNN (Convolutional Neural Network) for disease prediction.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/AgroFertilizer-Disease-Predictor.git
    cd AgroFertilizer-Disease-Predictor
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python app.py
    ```

4. Open a browser and go to:
    ```
    http://127.0.0.1:5000/
    ```

## Usage

1. **Fertilizer Prediction**: Go to the "Fertilizer" section and input the necessary details such as soil type and crop. The system will return the recommended fertilizer.
2. **Disease Prediction**: Upload a clear image of the crop in the "Disease Detection" section, and the system will predict any potential diseases.

## Models Used

- **RandomForest Model**: Used for fertilizer prediction.
- **Plant Disease Model (CNN)**: A Convolutional Neural Network model trained on crop images to detect diseases.


## Future Improvements

- Expand the dataset for disease detection.
- Incorporate more crop types for fertilizer recommendations.
- Improve the UI for a better user experience.
