# Predicting House Prices in Iowa 🏡

Welcome to our machine learning model designed to predict house prices for newly listed properties in the Iowa housing market!

## Team Members
- **Victor Floriano**
- **Mahima Masetty**
- **Aneri Patel**
- **Jordan Teman**

## Project Overview
Collaborating as a team, we leveraged a dataset with 1,460 entries from the Iowa housing market to construct a robust machine learning model that predicts property prices.

### Analysis & Preprocessing
- **Multivariate Feature Imputation**: Enhanced the dataset's reliability by imputing missing values.
- **IQR Method**: Removed outliers to ensure a more stable prediction.
- **Correlation Tables**: Identified and understood the relationships between various features.
- **Forward Selection**: Optimized feature selection for our models.
- **PCA Analysis**: Reduced dimensionality while retaining the essential characteristics of the data.

### Model Testing & Tuning
We meticulously explored and optimized several machine learning methods:

- Linear Regression
- Naïve Bayes
- K-Nearest Neighbors
- Decision Trees
- Random Forests
- Regularized Regressions

Our persistent efforts allowed us to achieve an impressively low RMSE of $22,546, ensuring that our model is both accurate and reliable.

## Getting Started

To dive into our project, follow the steps below:

### Prerequisites
Ensure you have a Python environment set up with necessary libraries, preferably via [Anaconda](https://www.anaconda.com/products/distribution) or [Jupyter Notebook](https://jupyter.org/install).

### Data
Our primary dataset for this project is `data.csv`. This dataset was adapted from the original dataset found on Kaggle's [House Prices: Advanced Regression Techniques competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

### Steps to Run the Project

1. **Clone the Repository**
   ```sh
   git clone https://github.com/victor-floriano/predicting-house-prices-iowa.git
   ```

2. **Navigate to the Repository Directory**
   ```sh
   cd path_to_repository
   ```

3. **Open the Main Project Script**
   To view and run the main code, open the `BA305_ProjectCode_Team20.ipynb` file in Jupyter Notebook:
   ```sh
   jupyter notebook BA305_ProjectCode_Team20.ipynb
   ```

4. **Explore Our Presentation**
   To gain deeper insights into our methodology, findings, and conclusions, check out the `BA305_ProjectPresentation_Team20.pdf`.

### Contributing

We welcome contributions! If you find any issues or would like to add enhancements, feel free to create pull requests or open issues.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
