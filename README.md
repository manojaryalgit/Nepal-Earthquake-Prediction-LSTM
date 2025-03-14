# Nepal Earthquake Prediction using LSTM

This repository contains a deep learning model using Long Short-Term Memory (LSTM) to predict earthquake occurrences in Nepal based on historical seismic data.

## Features
- **Data Preprocessing**: Cleaning and normalizing earthquake records.
- **LSTM Model**: Deep learning-based time-series forecasting.
- **Evaluation Metrics**: Uses MAE, MSE, and R2 Score for accuracy assessment.
- **Data Visualization**: Graphical insights into predictions vs actual data.

## Repository Structure
- `NepalLSTM.ipynb` - Jupyter Notebook with model training and evaluation.
- `Nepaleqmbdata.csv` - Earthquake dataset used for training.
- `requirements.txt` - List of dependencies.
- `.gitignore` - Files to exclude from Git tracking.
- `README.md` - Project documentation.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/manojaryalgit/Nepal-Earthquake-Prediction-LSTM.git
   cd Nepal-Earthquake-Prediction-LSTM
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter Notebook:
```sh
jupyter notebook NepalLSTM.ipynb
```

## Dataset
The dataset consists of historical earthquake records in Nepal, including features like latitude, longitude, depth, magnitude, and timestamp.

## Model Architecture
- **LSTM Layers**
- **Dense Output Layer**
- **Dropout Regularization**

## Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-Squared Score (R2 Score)**

## Results
The model successfully predicts trends in earthquake occurrences with reasonable accuracy.

## Contributions
Feel free to fork and contribute! Open a pull request if you have improvements.

## License
MIT License

## Author
Manoj Aryal
