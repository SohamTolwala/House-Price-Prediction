# House-Price-Prediction
Want to predict the future? Try our local server-powered house price predictor! Just input your flat's area, BHK, bathrooms, and location, and let our algorithm do the crystal ball gazing for you. Who needs a fortune teller when you have data?

Firstly, the project uses Python programming language along with popular libraries like NumPy, Pandas, and Scikit-learn. These libraries help in data processing, visualization, and machine learning tasks.

The dataset used in the project is pre-processed and cleaned to ensure data quality. Then, it is divided into two parts: training and testing data using the ShuffleSplit module from Scikit-learn. The training data is used to train the machine learning model, while the testing data is used to evaluate its performance.

Next, the project uses several regression algorithms to predict the house prices. The first algorithm is Linear Regression, which is a basic machine learning algorithm used to predict continuous values. The project also uses Lasso regression, which is a regression technique that uses L1 regularization to prevent overfitting.

The Decision Tree Regressor algorithm is used to create a decision tree model that predicts the prices based on a set of decision rules. The GridSearchCV module is used to fine-tune the hyperparameters of the decision tree model.

To evaluate the performance of the machine learning models, the project uses cross-validation techniques like K-Fold and Stratified K-Fold cross-validation. These techniques help in reducing the variance of the evaluation score.

In summary, the project uses various machine learning algorithms and techniques like Linear Regression, Lasso regression, Decision Tree Regressor, GridSearchCV, ShuffleSplit, and cross-validation to predict house prices based on input variables like area, BHK, bathrooms, and location.
