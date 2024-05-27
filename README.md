# Vancouver-Airbnb-Price-Prediction
A machine learning project to build a price estimator for Airbnb listings in Vancouver, helping home providers reach an equilibrium price that optimizes profits and affordability. This project includes data preprocessing, model selection (ML/DL), training, evaluation, and deployment.


Data Description:
1. Accommodates: Maximum number of renters
2. Bathrooms: Number of bathrooms
3. Neighborhood: Name of the neighborhood
4. Num_beds: Number of beds provided
5. Property_type: The type of the property e.g. houses and apartments
6. Price: Rental cost per night per person


Project Steps:
1. Data Preprocessing:
    * Handle missing values ✨
    * Remove duplicates 🗑️
    * Encoding the Output Data 📊
    * Checking if the dataset contains any NULL values 🧐
    * Feature Scaling 📏
        * ML model: Not necessary since the linear regression package in the ‘sklearn library’ does it internally.
        * DL: Necessary
2. Model Selection:
    * Multiple Linear Regression ( we have more than one input variable) 📊
    * ANN Model  🧠
        * ‘mean squared error' loss is minimized.
        * The output layer must have a single node.

1. Model Training:
    * Split data into training and testing sets 🧩
    * Train selected models on training data 🚀
2. Model Evaluation:
    * Evaluate model performance using regression metrics (RMSE, R Square) 📊
    * Plotting the Learning Curve 📈
<img width="832" alt="Screen Shot 2024-05-27 at 12 18 26 PM" src="https://github.com/ZTECH10/Vancouver-Airbnb-Price-Prediction/assets/53150477/2af8f561-658a-41f0-b8d5-f057e740a68a">


