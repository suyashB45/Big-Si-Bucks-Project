# Multiple Linear Regression on Country Economic Data

## Overview

This project involves performing multiple linear regression on a dataset containing economic indicators for various countries. The aim is to predict the `GNP Spend on Education` based on other features in the dataset.

## Dataset

The dataset includes the following columns:

- `Country`: Name of the country.
- `City`: Name of the city.
- `Population (millions)`: Population in millions.
- `Computer Sales (millions $)`: Sales of computers in millions of dollars.
- `GNP per Head`: Gross National Product per head.
- `Unemployment Rate`: Unemployment rate.
- `GNP Spend on Education`: Gross National Product spend on education.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install them using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. Ensure your dataset is in the correct directory, or modify the script to point to the correct dataset location.

3. Run the regression script:
    ```bash
    python regression_script.py
    ```

### Repository Structure

- `data/`: Contains the dataset.
- `scripts/`: Contains the Python scripts for data analysis and regression.
- `notebooks/`: Contains Jupyter notebooks with exploratory data analysis and regression model development.
- `results/`: Contains results of the regression analysis including plots and model performance metrics.
- `README.md`: This file.

## Analysis

### Exploratory Data Analysis (EDA)

The EDA involves understanding the distribution of each feature, checking for missing values, and visualizing relationships between features using scatter plots, correlation matrices, etc.

### Regression Model

The multiple linear regression model is built using the `scikit-learn` library. The target variable is `GNP Spend on Education`, and the predictor variables are:

- `Population (millions)`
- `Computer Sales (millions $)`
- `GNP per Head`
- `Unemployment Rate`

The regression model is evaluated using metrics such as Mean Squared Error (MSE), R-squared value, and visual inspection of residual plots.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the creators of the dataset and the contributors of the libraries used in this project.
