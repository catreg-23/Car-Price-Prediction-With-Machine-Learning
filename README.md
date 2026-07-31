# Car-Price-Prediction-With-Machine-Learning
This project predicts the selling price of a used car using Machine Learning techniques. The dataset is cleaned, preprocessed, visualized, and used to train a Random Forest Regression model. The project demonstrates the complete Machine Learning workflow from data preprocessing to model evaluation.
🎯 Objectives
Load and explore the car dataset.
Clean and preprocess the data.
Handle missing values and duplicate records.
Encode categorical variables.
Perform feature engineering.
Visualize the dataset using various charts.
Train a Machine Learning regression model.
Evaluate model performance.
Predict the selling price of cars.
📂 Dataset
Dataset Name: car data.csv
Dataset Features
Car_Name
Year
Selling_Price (Target Variable)
Present_Price
Kms_Driven
Fuel_Type
Seller_Type
Transmission
Owner
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
📊 Data Preprocessing
The following preprocessing steps were performed:
Loaded dataset
Checked dataset information
Removed duplicate rows
Handled missing values
Converted categorical values into numerical values using Label Encoding
Created a new feature (Car Age)
Removed unnecessary columns
📈 Data Visualization
The project includes the following visualizations:
Histogram
Count Plot
Scatter Plot
Box Plot
Correlation Heatmap
Pair Plot
Feature Importance Plot
Actual vs Predicted Plot
🤖 Machine Learning Model
Algorithm Used
Random Forest Regressor
Why Random Forest?
High prediction accuracy
Handles nonlinear relationships
Reduces overfitting
Works well with tabular datasets
📉 Model Evaluation
The model was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
📁 Project Structure
Car-Price-Prediction/
│
├── car data.csv
├── Cleaned_Car_Data.csv
├── Car_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── heatmap.png
    ├── histogram.png
    ├── scatterplot.png
    ├── boxplot.png
    ├── pairplot.png
    ├── feature_importance.png
    └── actual_vs_predicted.png
▶️ How to Run the Project
Clone this repository.
git clone https://github.com/your-username/Car-Price-Prediction.git
Install the required libraries.
pip install -r requirements.txt
Open the Jupyter Notebook.
jupyter notebook
Run all the cells in Car_Price_Prediction.ipynb.
📦 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
📸 Output
Cleaned dataset generated successfully.
Various data visualizations created.
Machine Learning model trained.
Car selling price predicted.
Model evaluated using regression metrics.
🌍 Real-World Applications
Used car price prediction
Online automobile marketplaces
Car dealerships
Vehicle insurance companies
Car loan valuation
Automobile resale platforms
🚀 Future Enhancements
Build a Streamlit web application.
Deploy the model on Render or Heroku.
Use XGBoost or Gradient Boosting for improved accuracy.
Integrate real-time car price prediction using user inputs.
👩‍💻 Author
Cathrine Regina
Final Year Student
Jeppiaar Engineering College
⭐ Acknowledgement
This project was developed as part of the CodeAlpha Machine Learning Internship (Task 3) to demonstrate data preprocessing, visualization, regression modeling, and machine learning concepts
