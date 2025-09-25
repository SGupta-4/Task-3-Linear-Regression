# Linear Regression on Housing Dataset

## Objective
Implement and understand **Simple & Multiple Linear Regression** using the Housing Dataset.  
The project demonstrates data preprocessing, model training, evaluation, and visualization.

## Dataset
Columns used in the dataset:
- **price** (Target variable)
- **area**
- **bedrooms**
- **bathrooms**
- **stories**
- **mainroad**
- **guestroom**
- **basement**
- **hotwaterheating**
- **airconditioning**
- **parking**
- **prefarea**
- **furnishingstatus**

## Steps
1. **Import and Preprocess Data**  
   - Load dataset using Pandas  
   - Encode categorical variables using one-hot encoding  

2. **Train-Test Split**  
   - Split dataset into 80% training and 20% testing  

3. **Model Training**  
   - Fit a `LinearRegression` model from `sklearn.linear_model`  

4. **Evaluation Metrics**  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  

5. **Visualization**  
   - Scatter plot of actual vs predicted prices  
   - Regression line for prediction fit  

## Results
- **MAE:** Lower values indicate better predictions  
- **MSE:** Penalizes large errors more strongly than MAE  
- **R²:** Proportion of variance explained by the model (closer to 1 is better)  

## Tools Used
- **Python**  
- **Pandas, NumPy**  
- **Scikit-learn**  
- **Matplotlib**
