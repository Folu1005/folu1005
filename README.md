All necessary packages like numpy, pandas, matplotlib, and seaborn were imported at the initial point. The train and test data were imported as well. Data preprocessing included the presentation of the data shape, info, columns, and descriptive statistics. 
Data visualizations involved showing the distribution plots of numerical variables and box plots were used to visualize the presence of outliers. 
The histoplots showed that all the variables were not normally distributed. However only variables “px_height” and “fc” had outliers. 
Scaling was performed by first importing the standard scaler. The scaler was fitted on the train data and the same transformation was applied to the test data. 
Algorithms used include K Nearest Neighbor (KNN), Support Vector Classifier (SVC), Decision Tree Classifier (DTC), and Random Forest Classifier (RFC). 
Models were validated using the accuracy score, fi-score, recall score, and confusion matrix. 
Amongst all four algorithms, the SVC proved the best as it recorded the highest F1 score of 95.3% and an accuracy score of 95.3%. 
This was closely followed by the KNN recording an F1 score of 92.5% and an accuracy score of 92.5%. 
