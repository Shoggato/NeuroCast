# NeuroCast: Forecasting Precipitation with AI Insight
## Overview

This repository contains code for building, training, and evaluating a neural network model aimed at predicting weather precipitation types (rain or not). The model leverages TensorFlow and Keras Tuner to achieve accurate predictions based on a diverse set of weather features.

## Dataset

The project utilizes a comprehensive weather dataset ('weatherHistory.csv') with features such as temperature, humidity, wind speed, etc. The dataset has been carefully preprocessed to handle missing values and categorize precipitation types, forming the foundation for robust model training and evaluation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-prediction-neural-network.git
   cd weather-prediction-neural-network
   ```
   
## Usage

1. Execute the `weather_prediction_nn.ipynb` notebook to run the complete pipeline, starting from data loading to model evaluation.
    ```bash
    jupyter notebook weather_prediction_nn.ipynb
    ```

2. For hyperparameter tuning, run the `weather_prediction_tuning.ipynb` notebook using Keras Tuner.
    ```bash
    jupyter notebook weather_prediction_tuning.ipynb
    ```

3. The trained model will be saved as `weather_model_kt.H5`. To load and evaluate the best model, refer to the evaluation section in the notebook.


## Structure
* __weather_prediction_nn.ipynb:__ Jupyter notebook containing the main code for building, training, and evaluating the neural network model.
* __weather_prediction_tuning.ipynb:__ Jupyter notebook for hyperparameter tuning using Keras Tuner.
* __data/weatherHistory.csv:__ Dataset used for training and evaluation.
* __requirements.txt:__ List of required Python packages.

## Results

The model achieves an impressive accuracy of 99% on the test set, showcasing its robust predictive capabilities. A detailed confusion matrix is included to visualize the classification performance, illustrating the model's ability to accurately distinguish between rain or not.

## License
This project is licensed under the MIT License.

## Acknowledgements
* Special thanks to `Keras Tuner` for facilitating hyperparameter tuning.
