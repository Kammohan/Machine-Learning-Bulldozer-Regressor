# Machine-Learning-Bulldozer-Regressor

This project leverages historical sales data of bulldozers sold at auctions, along with Python-based machine learning and data science libraries, to build a predictive model that estimates the sale price of bulldozers based on their characteristics.

## Features
- **Data Exploration:** Analyzing the dataset to identify key factors influencing bulldozer prices.
- **Data Preprocessing:** Implementing data cleaning, feature engineering, and transformation to prepare data for modeling.
- **Model Building:** Constructing a predictive model using `RandomForestRegressor`.
- **Evaluation:** Measuring model performance using metrics like Mean Squared Logarithmic Error (MSLE), R² score, and Mean Absolute Error (MAE).
- **Feature Importance Assessment:** Evaluating the importance of different attributes in the prediction to understand their impact on the model.

## Technologies Used
- **Python 3:** Primary programming language.
- **Pandas & NumPy:** For data manipulation and numerical computations.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For building and evaluating the machine learning model.

## Dataset
The project uses data from the "Blue Book for Bulldozers" competition, which includes various attributes of bulldozers such as model type, year of manufacture, usage hours, and many others. The dataset's primary aim is to predict the auction sale price of a bulldozer.

## Model Training
The model employs the `RandomForestRegressor` from scikit-learn, with parameters optimized using techniques like `RandomSearchCV` to enhance performance.

## Evaluation
The model's performance is evaluated using metrics such as MSLE, R² score, and MAE, which help quantify prediction accuracy and error margins. Additionally, feature importance graphs provide insights into which attributes are most influential in determining bulldozer prices.
