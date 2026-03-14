# House Price Prediction Model

A machine learning project that implements a **linear regression model** to predict house prices based on various property features.

## Overview

This project demonstrates the application of linear regression techniques to build a predictive model for estimating house prices. The model considers multiple factors including:

- **Area** of the house
- **Number of bedrooms**
- **Number of bathrooms**
- And other relevant property features

## Features

- Data preprocessing and exploration
- Linear regression model implementation
- Model training and evaluation
- Price prediction capabilities
- Performance metrics visualization

## Project Structure

```
CODECRAFT_ML_01/
├── README.md
└── house_price_prediction.ipynb
```

### Files

- **house_price_prediction.ipynb** - Jupyter Notebook containing:
  - Data loading and exploration
  - Data preprocessing and feature engineering
  - Linear regression model development
  - Model evaluation and visualization
  - Price predictions

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/daryahussain/CODECRAFT_ML_01.git
   cd CODECRAFT_ML_01
   ```

2. Install required packages
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

### Usage

1. Open the Jupyter Notebook
   ```bash
   jupyter notebook house_price_prediction.ipynb
   ```

2. Run the cells sequentially to:
   - Load and explore the data
   - Preprocess the features
   - Train the linear regression model
   - Evaluate model performance
   - Make predictions on new data

## Model Details

The linear regression model predicts house prices using the equation:

**Price = β₀ + β₁(Area) + β₂(Bedrooms) + β₃(Bathrooms) + ... + ε**

Where:
- β coefficients represent feature weights
- ε represents the error term

## Results

The model's performance is evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score
- Mean Absolute Error (MAE)

## Technologies Used

- **Python** - Programming language
- **Jupyter Notebook** - Interactive development environment
- **Scikit-learn** - Machine learning library
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib/Seaborn** - Data visualization

## Author

[daryahussain](https://github.com/daryahussain)

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request

## Acknowledgments

- Inspired by machine learning best practices
- Built with educational purposes in mind

---

**Happy Learning!** 🚀