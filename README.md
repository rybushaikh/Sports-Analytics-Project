# Sports Analytics Project
This repository contains the code and documentation for a sports analytics project focusing on predicting player wages and analyzing the factors that significantly impact a player’s overall rating. This project was developed as part of the ALY6015: Intermediate Analytics course at Northeastern University.

# Table of Contents
Introduction
Project Goals
Data
Methods
Results
Conclusion
Installation
Usage
Contributing
License
# Introduction
In this project, our primary focus is on sports analytics specifically in the context of predicting player wages and analyzing the factors that significantly impact a player’s overall rating. By understanding these aspects, we can gain valuable insights into player valuation and performance evaluation in the sports industry.

# Project Goals
Predicting a Player’s Wage
Develop a predictive model that can estimate a player’s wage using their attributes and personal data.
Analyzing Factors Impacting Player’s Overall Rating
Identify the factors that have the most significant influence on a player’s overall rating.
Data
The data used in this project includes player attributes such as age, overall rating, market value, nationality, position, and other relevant information. The dataset was preprocessed to handle missing values and to select relevant variables for analysis.

# Methods
Predicting Player’s Wage
Model: Ridge Regression
Evaluation Metrics:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared
Analyzing Factors Impacting Player’s Overall Rating
Model: Generalized Linear Model (GLM)
Evaluation Metrics:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared
Results
Predicting Player’s Wage
Best Model Performance:
MSE: 94,985,789
RMSE: 9,746.065
R-squared: 0.729
Analyzing Factors Impacting Player’s Overall Rating
Best Model Performance:
MSE: 9.958295
RMSE: 3.16
R-squared: 0.779
# Conclusion
The project successfully developed models to predict player wages and analyze factors impacting overall player ratings. The Ridge Regression model provided a robust prediction of player wages, while the GLM effectively identified key factors influencing player ratings.

# Installation
To run the code in this repository, you need to have the following dependencies installed:

Python 3.8+
Pandas
Numpy
Scikit-learn
Matplotlib
Seaborn
You can install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/sports-analytics-project.git
Navigate to the project directory:

bash
Copy code
cd sports-analytics-project
Run the data preprocessing script:

bash
Copy code
python preprocess_data.py
Run the model training script:

bash
Copy code
python train_model.py
Analyze the results:

bash
Copy code
python analyze_results.py
Contributing
Contributions are welcome! Please read the contribution guidelines first.

License
This project is licensed under the MIT License - see the LICENSE file for details.
