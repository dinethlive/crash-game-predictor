
# Crash Predictor

Crash Predictor is a Python-based graphical user interface (GUI) application that predicts the next crash value in betting games using various statistical and machine learning models. The application provides multiple prediction models, allowing users to explore different techniques to forecast the crash value.

## Features

- **20 Prediction Models**: Supports a wide range of models, including:
  - Monte Carlo Simulation
  - Linear Regression
  - Random Forest
  - Support Vector Regression (SVR)
  - Simple Moving Average
  - Exponential Moving Average
  - Polynomial Regression
  - Decision Tree
  - Gradient Boosting
  - K-Nearest Neighbors (KNN)
  - Ridge Regression
  - Lasso Regression
  - Elastic Net Regression
  - Bayesian Ridge Regression
  - ARIMA
  - LSTM Neural Network
  - XGBoost Regression
  - LightGBM Regression
  - CatBoost Regression

- **User-Friendly GUI**: Built with `tkinter`, the application offers an easy-to-use interface with checkboxes to select different prediction models.
- **Real-Time Predictions**: Provides accurate predictions based on the latest data, with results displayed in a popup window.
- **CSV Preview Functionality**: Allows users to preview the CSV data directly within the application.

## Installation

### Prerequisites

Ensure you have Python 3.x installed on your system. You'll also need to install the following Python libraries:

```bash
pip install numpy pandas scikit-learn statsmodels xgboost lightgbm catboost keras tensorflow
```

### Clone the Repository

```bash
git clone https://github.com/dinethlive/crash-game-predictor.git
cd crash-game-predictor
```

### Run the Application

Run the script using Python:

```bash
python predict_crash_gui.py
```

## Usage

1. **Select Prediction Models**: Use the checkboxes to choose one or more prediction models.
2. **Predict Next Crash Value**: Click the "Predict Next Crash" button to calculate and display the predictions for the selected models.
3. **Preview CSV Data**: Click the "Preview CSV" button to view the CSV data in a scrollable window.
4. **Exit**: Click the "Exit" button to close the application.

## Screenshots

![Crash Predictor GUI](https://github.com/dinethlive/crash-game-predictor/blob/main/Screenshots/ss.png?raw=true)
![Crash Predictor GUI](https://github.com/dinethlive/crash-game-predictor/blob/main/Screenshots/ss-results.png?raw=true)

## Contributing

Contributions are welcome! If you have ideas for additional features or improvements, feel free to fork the repository and create a pull request. Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of `scikit-learn`, `statsmodels`, `xgboost`, `lightgbm`, `catboost`, `keras`, and `tensorflow` for providing powerful tools for machine learning and data analysis.
- Inspiration from various machine learning models and statistical techniques used in data science.

## Contact

For questions or suggestions, feel free to reach out:

- Dineth Pramodya - [hello@dineth.lk](mailto:hello@dineth.lk)
- GitHub: [dinethlive](https://github.com/dinethlive)


