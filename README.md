# Wine_Dataset_Naive_Bayes
Utilizing Naive Bayes Algorithm for the wine data set (Classification).
I analyzed the wine dataset using EDA plots, including pair plots (sns.pairplot) and joint plots (sns.histplot), to visualize feature distributions and relationships with the target variable ('target').
After splitting the data into training and testing sets, I performed hyperparameter tuning for the Gaussian Naive Bayes model (GaussianNB) using GridSearchCV to optimize the var_smoothing parameter for maximizing accuracy. 
The best model was evaluated on the test set using a classification report (classification_report), providing insights into its precision, recall, and F1-score across different wine classes (wine.target_names).
