# Classification-Project
In this data science project, the goal was to predict the quality of wines on a scale of 1 to 10. Two datasets are included, related to red and white vinho verde wine samples, from the north of Portugal.
Downloaded them from this site: https://archive.ics.uci.edu/dataset/186/wine+quality
The classes are ordered and not balanced - there are many more normal wines than excellent or poor ones.
The project involved the following steps:
### 1. Data Exploration:
Explored the dataset by checking the head, value counts, and descriptive statistics of the features.
Checked for missing data using a heatmap visualization.
Explored linear dependencies between features using pair plots and correlation matrix.
### 2. Data Visualization:
Visualized the distribution of each feature using histograms and count plots.
Calculated skewness and kurtosis of the features to assess their distributions.
### 3. Outlier Analysis:
Performed outlier analysis using the confidence interval method.
Identified and visualized outliers using scatter plots.
Removed outliers from the dataset.
### 4. Data Preprocessing:
Converted the multi-class classification problem into a binary classification problem by mapping quality values.
Standardized the independent variables using the StandardScaler.
### 5. Model Building and Evaluation:
Split the dataset into training and testing sets.
Built a Logistic Regression model and evaluated its performance using classification reports and confusion matrix.
Further built and evaluated other models like K-Nearest Neighbors (KNN), Decision Tree, Random Forest, Support Vector Classifier (SVC), and performed hyperparameter tuning using GridSearch.
### 6. Model Comparison:
Combined the classification reports of all models.
Compared the performance metrics of different models to determine the most effective model for wine quality prediction.
