# Insurance Charges Prediction Project

## Overview

This project aims to predict individual medical insurance charges using machine learning techniques. By analyzing demographic and health-related data, the model provides insights into the factors influencing insurance costs, helping both insurers and policyholders make informed decisions.

## Dataset

The dataset (insurance.csv) contains the following features:
- **Age**: Age of the insured person
- **Sex**: Gender of the insured person
- **BMI**: Body Mass Index, a measure of body fat based on height and weight
- **Children**: Number of children/dependents covered by insurance
- **Smoker**: Whether the insured is a smoker
- **Region**: Residential area in the US (northeast, southeast, southwest, northwest)
- **Charges**: Individual medical insurance costs billed by health insurance

## Project Workflow

1. **Data Exploration & Visualization**  
   - Load and inspect the dataset for missing values and outliers.
   - Visualize relationships between features and insurance charges using plots (histograms, scatter plots, box plots).

2. **Data Preprocessing**  
   - Encode categorical variables (e.g., sex, smoker, region).
   - Normalize or scale numerical features if necessary.
   - Split the data into training and testing sets.

3. **Model Building**  
   - Train regression models (e.g., Linear Regression, Random Forest, etc.) to predict insurance charges.
   - Evaluate model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

4. **Model Interpretation**  
   - Analyze feature importance to understand which factors most influence insurance charges.
   - Visualize predictions vs. actual values.

5. **Deployment (Optional)**  
   - Provide a user interface or API for making predictions on new data.

## Results

- The project demonstrates how machine learning can accurately estimate insurance charges based on personal and lifestyle information.
- Insights from feature importance help identify key drivers of insurance costs, such as smoking status, age, and BMI.

## How to Use

1. Open Insurance.ipynb in Jupyter Notebook.
2. Run the cells sequentially to explore the data, preprocess, train models, and view results.
3. Modify the notebook to experiment with different models or parameters.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn (install via `pip install -r requirements.txt` if provided)

## Author

Betheloguguo
