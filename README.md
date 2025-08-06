# Real Estate Price Predictor 🏡

A project that uses machine learning to predict house prices.

---

## ## What This Project Does

This project analyzes real estate data to figure out what makes a property expensive or cheap. It then uses this knowledge to build a model that can predict the price of a house based on its features.

---

## ## Key Features

* **Smart Features:** Instead of just using the raw data, we created new, more helpful features:
    * **Neighborhoods:** Grouped properties into different zones based on their location.
    * **Time Trends:** Used the transaction date to see how prices change over time.
    * **Age Groups:** Put houses into categories like 'New', 'Modern', or 'Old'.
* **Finds the Best Model:** The project tests three different prediction models and proves that **XGBoost** is the most accurate one for this task.
* **Clear Visuals:** Creates simple charts to show what factors are most important for pricing and how accurate the final predictions are.

---

## ## How to Run It

1.  **Get the Code:**
    * Download or clone this project to your computer.

2.  **Install the Tools:**
    * Open your terminal and run this command:
    ```bash
    pip install pandas scikit-learn xgboost matplotlib seaborn
    ```

3.  **Get the Data:**
    * Download the `Real_Estate.csv` file.
    * Make sure the CSV file is in the same folder as the project.

4.  **Start the Project:**
    * Run the Jupyter Notebook to see the code and results.
    

---

## ## Project Results

The final model using **XGBoost** was very successful at predicting house prices.

### ### What Matters Most for the Price?

This chart shows the most important factors for determining a house's price. The distance to the nearest MRT (metro) station is clearly the biggest factor.


### ### How Accurate Are the Predictions?

This plot compares the model's predicted prices to the actual prices. Since most dots are close to the red line, it shows our model is quite accurate.


---

## ## License

This project is shared under the MIT License.
