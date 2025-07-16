🏡 House Price Prediction Using Linear Regression
This project uses a Linear Regression model to predict house prices based on various features from a housing dataset.
It includes data preprocessing, feature selection, model training, evaluation, and prediction on a separate test dataset

--------------------------------------------------------------------------------------------------------------------------
📁 Project Structure
LR_HousePricePrediction/
├── LR_HousePricePrediction.ipynb   # Jupyter Notebook with complete code
├── test.csv                        # Test dataset (optional)
├── train.csv                       # Predicted house prices (output)
└── README.md                       # Project documentation

--------------------------------------------------------------------------------------------------------------------------
🚀 Features Used
Some of the key features used for training the model include:-
 FullBath                             TotRmsAbvGrd
 BsmtFullBath                         MasVnrArea
 BsmtUnfSF                            BsmtFinSF1
 BedroomAbvGr                         BsmtFinSF2
 BsmtHalfBath                         WoodDeckSF
 HalfBath                             2ndFlrSF
 GrLivArea                            OpenPorchSF
 GarageArea                           3SsnPorch
 TotalBsmtSF                          LotArea
 1stFlrSF                             PoolArea 
 
 ------------------------------------------------------------------------------------------------------------------------
🧪 Model & Evaluation
Model: Linear Regression (sklearn.linear_model.LinearRegression)

Scaler: StandardScaler for feature normalization

Metric: R² Score

Achieved R² Score: 0.768

Visualization: Residual plots, predicted vs actual, feature correlation

 ------------------------------------------------------------------------------------------------------------------------
🧰 Tools & Libraries
Python

pandas

NumPy

scikit-learn

matplotlib / seaborn (for visualization)

Jupyter Notebook 
 ------------------------------------------------------------------------------------------------------------------------
