In this project, I analyzed aviation data and built intelligent models to predict flight fuel consumption levels using Machine Learning and Artificial Neural Networks (ANN). I began with comprehensive data preprocessing, where I handled missing values using the median, and created the target variable Fuel_Consumption_Level based on the fuel cost median to classify flights into High or Low consumption. Next, I dropped irrelevant columns, applied One-Hot Encoding to categorical variables, and split the dataset into 80% training and 20% testing sets using stratified sampling to ensure class balance.

For modeling, I developed a custom pipeline to train and evaluate multiple algorithms, including Logistic Regression, Random Forest Classifier,
and K-Nearest Neighbors (KNN). I also built an ANN using Keras, incorporating Dense and Dropout layers to prevent overfitting. 
To evaluate and compare model performance, I relied on strict metrics: Accuracy, Precision, Recall, F1-Score, and the Confusion Matrix for each model.
The entire project was implemented in Python 3, leveraging Pandas and NumPy for data manipulation, Scikit-Learn for machine learning, 
TensorFlow and Keras for deep learning, 
and Matplotlib alongside Seaborn for data visualization.
