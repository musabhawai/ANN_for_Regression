# ANN Regression – House Price Prediction

## 🧠 Overview
This project implements an *Artificial Neural Network (ANN) for regression tasks* using Keras and TensorFlow.  
The dataset focuses on *predicting house prices. The pipeline covers **EDA, feature engineering, scaling, train-test split, model creation, training, validation, evaluation, and visualization*.  

## 📖 About ANN for Regression
An *Artificial Neural Network (ANN)* is a powerful deep learning model that can capture complex, non-linear relationships in data.  
For regression problems, the final output layer uses a *linear activation* to predict continuous values (e.g., house price).  

## 🛠 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn (for visualization)  
- Scikit-learn (for preprocessing & metrics)  

## ⚙️ Workflow
1. *Exploratory Data Analysis (EDA)*  
   - Analyzed dataset distribution & correlations.  
   - Visualized feature-target relationships.  

2. *Feature Engineering*  
   - Scaled features using StandardScaler.  
   - Train-test split performed.  

3. *Model Creation*  
   - Keras *Sequential API* with multiple Dense layers and activation functions.  
   - Optimizer: *Adam*  
   - Loss Function: *Mean Squared Error (MSE)*  

4. *Training*  
   - Used *validation data* during training.  
   - Trained with defined *epochs* and *batch size*.  
   - History plotted – *loss & val_loss overlapped closely*, showing good generalization.  

5. *Evaluation*  
   - Evaluated with:  
     - *Mean Absolute Error (MAE)*  
     - *Mean Squared Error (MSE)*  

## 📂 Code Included
- EDA & feature visualization  
- Feature engineering & scaling  
- Train-test splitting  
- ANN creation with Sequential & Dense layers  
- Compilation with Adam optimizer and MSE loss  
- Training with validation & plotting training history  
- Model evaluation with MAE & MSE
