# **Credit Card Fraud Detection**

This repository contains a complete project for credit card fraud detection using machine learning techniques. The main objective is to develop a model that can identify fraudulent transactions based on a historical dataset of transactions.

## **Project Description**

Credit card fraud is a critical issue in the financial sector, with significant consequences for both financial institutions and customers. This project addresses this challenge by implementing classification models that analyze various transaction characteristics to determine whether they are legitimate or fraudulent.

## **Project Structure**

- **1. Data Import:** The project starts with importing a dataset that contains credit card transactions, with anonymized features to protect user privacy.

- **2. Data Cleaning:** An extensive data cleaning process is performed, including the removal of duplicate values and checking for null values.

- **3. Exploratory Data Analysis:** An exploratory data analysis is conducted to understand the distribution of fraudulent and non-fraudulent transactions, as well as the behavior of the transaction amounts.

- **4. Data Visualization:** Graphs and visualizations are used to illustrate the distribution of transactions and amounts, helping to identify patterns and trends in the data.

- **5. Predictive Modeling:** Classification models, such as Logistic Regression and Random Forest, are implemented and evaluated to predict the likelihood of fraud in new transactions.

- **6. Model Evaluation:** The models are evaluated using key metrics such as precision, recall, and F1-score, aiming to optimize fraud detection while minimizing false positives and false negatives.

## **Results**

- **Logistic Regression:** A baseline model that provides a solid reference for fraud detection with a linear approach.
  
- **Random Forest:** A more complex model that, with a precision close to 100%, provides a more robust and efficient classification, especially in imbalanced datasets.

## **Requirements**

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

## **Usage**

To reproduce this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```
3. Run the notebook `Proyecto final.ipynb` to see the complete steps of the analysis and modeling.

## **Contributions**

Contributions to this project are welcome. If you have ideas to improve the model, new analysis techniques, or visualizations, feel free to submit a pull request or open an issue.

## **License**

This project is licensed under the MIT License.

## **Contact**

If you have any questions or suggestions, feel free to contact me at [engjtsp@gmail.com](mailto:your-emailengjtsp@gmail.com).
