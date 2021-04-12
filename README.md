# machine-learning
A ML project

**Problem statement:** https://www.hackerearth.com/practice/machine-learning/machine-learning-algorithms/beginners-guide-regression-analysis-plot-interpretations/practice-problems/machine-learning/predict-the-price-5-fe7f8735/


**Tool used:** Jupiter Notebook, python
**Libraries:** Sklearn, numpy, pandas

**Approach**
1. Data with Nan values were removed
2. "Product_id","Customer_name" columns are removed
3. "Loyalty_customer", "Product_Category" are mapped to one hot encoding
4. Extract year and month and drop instock_date column
5. Used RandomForestRegression model to tarin with test data od 1/3rd.
6. Predict 

**Further Improvement:**
 * Add new features like average price, time of selling etc
 * Hyper parameter tuning of model
 * Train model using entire dataset
