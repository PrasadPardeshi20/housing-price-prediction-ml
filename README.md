🏠 California Housing Price Prediction using Linear Regression
This project involves building a machine learning model to predict California house prices using the California Housing Dataset from Kaggle. The model uses linear regression with polynomial features, log transformation, and proper preprocessing to achieve optimal accuracy.

📂 Dataset Information
Source: Kaggle – California Housing Prices

Rows: 20,000+

Features: 9 input features including:

longitude

latitude

housing_median_age

total_rooms

total_bedrooms

population

households

median_income

ocean_proximity

Target: median_house_value

🔧 Technologies Used
Python 3.x

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

PolynomialFeatures

StandardScaler

KaggleHub (to fetch dataset)

✅ Project Steps
Data Importing: Loaded dataset using kagglehub.

Exploratory Data Analysis (EDA): Used .head(), .describe(), null value checks.

Data Cleaning: Filled missing values in total_bedrooms.

Feature Engineering:

Applied log1p to skewed numerical features.

Encoded categorical feature ocean_proximity.

Standard scaling.

Polynomial feature transformation.

Model Building:

Used LinearRegression() from sklearn.

Trained on 80% of the data.

Model Evaluation:

Achieved 74.67% R² score on test data.

New Prediction:

Predicted house prices for new input data after applying the same preprocessing.

📈 Model Accuracy
R² Score: 0.7467

The model performs reasonably well on unseen test data, and can generalize for real-world predictions within similar data distribution.

🧪 Example Prediction Output
python
Copy
Edit
Predicted House Price: $172,779.47
For input features such as:

Longitude: -118.5

Latitude: 34.2

Median Income: 5.2

Total Rooms: 2200
(...after applying same preprocessing pipeline)

📦 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/california-housing-regression.git
cd california-housing-regression
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook LinearRegressionProject.ipynb
🚀 Future Improvements
Try advanced regression models like Ridge, Lasso, Random Forest

Build a Streamlit/Flask app for live house price prediction

Add cross-validation and hyperparameter tuning

📌 Conclusion
This project demonstrates how a well-structured linear regression pipeline — with data cleaning, scaling, transformation, and evaluation — can be used effectively for predicting house prices. The model is now deployable and can make real-time predictions on new data.

📬 Connect
Feel free to connect with me on:

LinkedIn

GitHub

