ReadMe File

Group 7: Aaron Pogrin, Oren Joffe, Ryan Rakusin

Notes: The main model is the Random Forest and that is the one that is used for predictions.
We have also attached the other 3 models although they may have various metrics left off as we went for random forest.
There is also a file used to write to the csv, it is not very important to read. 
Make sure to just add your relative path to the train and test data sets to run the notebooks.
Also ignore the blocks for gridsearch as they are just included for hyperparam tuning but now that our random forest has optimal params aleady included you can skip that block or it will take too long. 

Our group was inspired to work on a project that could provide value to the hospitality industry by predicting hotel cancellations. We learned the importance of data preprocessing, feature engineering, and model selection to build an accurate machine learning model. We started by exploring the dataset and performing necessary data cleaning, encoding categorical variables, and scaling numeric variables. We then split the data into training and test sets and built several classification models, including logistic regression, decision trees, MLPs, and Random Forests, using the Scikit-Learn library in Python. We evaluated the models using various metrics, such as accuracy, precision, recall, and F1-score, and tuned the hyperparameters using Grid Search Cross-Validation to obtain the best-performing model. One of the challenges we faced was dealing with imbalanced classes in the target variable, as the data had significantly more non-cancelled bookings than cancelled bookings. We addressed this issue by using oversampling techniques and adjusting the classification threshold. Overall, this project allowed us to gain hands-on experience in machine learning and apply it to a real-world problem.