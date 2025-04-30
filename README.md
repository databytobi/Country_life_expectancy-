# Country Life Expectancy Prediction

This project aims to predict a country's life expectancy (in years) using a set of metrics and machine learning models. By analyzing various factors, the project provides insights into how different metrics influence life expectancy.

---

## Overview

The project leverages multiple regression models to predict life expectancy based on a dataset of country-specific metrics. The following machine learning models are used:
- **Linear Regression**
- **K-Nearest Neighbors Regressor (KNeighborsRegressor)**
- **Decision Tree Regressor**
- **Support Vector Regressor (SVR)**

The performance of each model is evaluated using the **Mean Absolute Error (MAE)** metric.

---

## Libraries and Tools Used

The project makes use of the following Python libraries:
- **Modeling**:
  - `LinearRegression`
  - `KNeighborsRegressor`
  - `DecisionTreeRegressor`
  - `SVR`
- **Error Metric**:
  - `mean_absolute_error`
- **Data Manipulation**:
  - `pandas`
  - `numpy`
- **Visualization**:
  - `matplotlib`
  - `seaborn`

---

## Features

- Preprocess the data to handle missing values and normalize features.
- Train and test various regression models to predict life expectancy.
- Evaluate the models using **Mean Absolute Error (MAE)**.
- Visualize the results and performance of each model for comparison.

---

## Installation

### Prerequisites

Ensure you have Python installed along with the required libraries. Install the dependencies using the following command:

```bash
pip install -U scikit-learn pandas numpy matplotlib seaborn
```

---

## Usage

1. Clone the repository to your local system:
   ```bash
   git clone https://github.com/databytobi/country-life-expectancy.git
   ```
2. Run the script to train and evaluate the models:
   ```bash
   python main.py
   ```

---

## Project Structure

```
country-life-expectancy/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for exploration and visualization
├── src/                   # Source code
│   ├── data_processing.py # Data preprocessing scripts
│   ├── model_training.py  # Scripts for training models
│   └── evaluation.py      # Evaluation scripts
├── tests/                 # Unit tests
├── main.py                # Main script to run the project
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## Evaluation Metrics

The models are evaluated using **Mean Absolute Error (MAE)** to measure prediction accuracy.

---

## Contributing

Contributions are welcome! If you have ideas for improvements or additional features, feel free to submit a pull request or open an issue.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Scikit-learn for providing the tools to build and evaluate regression models.
- Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualization.
