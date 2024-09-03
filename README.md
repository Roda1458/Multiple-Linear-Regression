# Multiple-Linear-Regression

## Description

This repository contains code and datasets for performing linear regression analyses. The project includes two primary use cases:

1. **Predicting Profit for Startups**: Using the 50_Startups dataset, this analysis applies single and multiple linear regression to predict profits based on various features.
2. **Predicting Car Prices**: Using the ToyotaCorolla dataset, this analysis focuses on predicting car prices based on features such as age, mileage, and horsepower.

## Datasets

### 50_Startups.csv

- **Description**: This dataset contains information about startups with features including R&D Spend, Administration, Marketing Spend, and State. It is used to predict the Profit of the startups.
- **Columns**:
  - `R&D Spend`: Amount spent on research and development.
  - `Administration`: Amount spent on administration.
  - `Marketing Spend`: Amount spent on marketing.
  - `State`: The state where the startup is located (categorical: New York, California, Florida).
  - `Profit`: The profit earned by the startup (target variable).

### ToyotaCorolla.csv

- **Description**: This dataset contains information about Toyota Corolla cars, including various features. It is used to predict car prices.
- **Columns**:
  - `Price`: Price of the car (target variable).
  - `Age_08_04`: Age of the car.
  - `KM`: Kilometers driven.
  - `HP`: Horsepower.
  - `cc`: Engine capacity.
  - `Doors`: Number of doors.
  - `Gears`: Number of gears.
  - `Quarterly_Tax`: Quarterly tax.
  - `Weight`: Weight of the car.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Roda1458/Multiple-Linear-Regression.git
   ```

2. **Install Required Libraries**:
   Make sure you have the following Python libraries installed:
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `matplotlib`
   - `seaborn`

   You can install these using pip:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run the Jupyter Notebook**:
   - Open the notebook `single_and_multiple_regression.ipynb` in Google Colab or any Jupyter environment.
   - Follow the cells in the notebook to perform data preprocessing, apply regression models, and evaluate the results.

## Files

- **`single_and_multiple_regression.ipynb`**: Jupyter notebook containing the code for performing single and multiple linear regression on the provided datasets.
- **`50_Startups.csv`**: Dataset for startup profit prediction.
- **`ToyotaCorolla.csv`**: Dataset for car price prediction.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please contact [Roda1458](rodachinthapalli@gmail.com).
