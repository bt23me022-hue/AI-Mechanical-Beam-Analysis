# AI-Based Cantilever Beam Deflection Prediction Using Machine Learning

## 1. Project Overview
This project uses Machine Learning to predict the maximum deflection of a cantilever beam subjected to a point load at its free end.

The project combines Mechanical Engineering principles with Artificial Intelligence to estimate beam deflection using different machine learning algorithms.

## 2. Objectives
- Understand cantilever beam deflection.
- Generate a dataset using the theoretical beam equation.
- Train Machine Learning models.
- Predict beam deflection for new input parameters.
- Evaluate and compare model performance.

## 3. Mechanical Engineering Theory

For a cantilever beam with a point load at its free end:

δ = PL³ / 3EI

For a rectangular cross-section:

I = bh³ / 12

Where:
- P = Applied load (N)
- L = Beam length (m)
- E = Young's modulus (Pa)
- I = Second moment of area (m⁴)
- b = Beam width (m)
- h = Beam height (m)
- δ = Maximum deflection (m)

## 4. Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

## 5. Dataset
A simulated dataset containing 1,000 samples was generated using the theoretical cantilever beam deflection equation.

Input parameters:
- Applied load
- Beam length
- Beam width
- Beam height

Output:
- Maximum beam deflection (mm)

## 6. Machine Learning Algorithms
1. Linear Regression
2. Random Forest Regression

## 7. Model Results

Random Forest Regression:
- Mean Absolute Error (MAE): 0.287921 mm
- R² Score: 0.9609

The Linear Regression model was also evaluated using a physically derived beam factor.

## 8. Sample Prediction

For a beam with:
- Load = 500 N
- Length = 1.0 m
- Width = 0.05 m
- Height = 0.08 m

The Random Forest model predicted approximately 0.4117 mm deflection.

## 9. Project Limitations
The dataset is simulated using classical beam theory and is not based on experimental measurements. Model performance on real beams may differ. The predictions are intended for educational demonstration, not structural safety decisions.

## 10. Conclusion
This project demonstrates how Machine Learning can be applied to Mechanical Engineering problems. It uses beam parameters to predict cantilever beam deflection and evaluates the performance of different regression algorithms.

## 11. Author
Student Name: Ishant and Sameer Kumar Sambhavam 
Roll Number: 230410104009 and 230410104019
Subject: AIMLP-004 – Artificial Intelligence and its Applications
