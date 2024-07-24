## Predictive-Modelling-for-Agriculture-Using-Machine-Learning
**Intoduction**
Farmers must optimize crop yield in modern agriculture to ensure profitability and sustainability. Assessing soil conditions, including nitrogen, phosphorus, potassium levels,
and pH values are crucial in determining the ideal crop for a specific field.

However, this process can be costly and time-consuming, prompting farmers to prioritize
specific soil metrics based on budget constraints. To address this challenge, a machine
learning approach is required to develop very good models capable of accurately predicting
the optimal crop based on soil characteristics.

**Problem Statement**
This project aims to build and compare multiple classification algorithms to predict
crop types using soil metrics and providing farmers with efficient decision-making tools for
crop selection.

**Objectives:**
1. Build and compare five (5) classification algorithms and select the best-performing model
2. Using the identified best model, build an application that helps farmers make
effective and efficient crop selection decisions

**Methods:**
1. **Data collection and Preparation**: The dataset, obtained from DataCamp (https://www.datacamp.com/) containing the soil metrics
and crop types will be loaded and read.
2. **Data Preprocessing**: Missing values were checked, and categorical variables were
encoded using Label Encoder.
3. **Exploratory Data Analysis (EDA)**: Exploratory data analysis was performed to identify relevant patterns, features, correlations, and their importance in
predicting crop types.
4. **Model Selection**: Various classification algorithms, such as Logistic
Regression, Random Forests, Decision Trees, Gradient Boosting, and Support Vector
Machines (SVM), which are suitable for multi-class classification tasks, were used.
5. **Model Training and Evaluation**: Each Algorithm is trained using the training data,
and the performance is evaluated using metrics such as accuracy, precisions,
recall, and F1 score.
6. **Hyperparameter Tuning**: To optimize the models' performance, the parameters of the selected algorithms were fine-tuned using the GridSearch method.
7. **Model Comparison**: The performance of the different algorithms were compared
and the best-performing model for predicting crop types based on the soil metrics in
the dataset was identified
8. **Build a Crop-Predicting App**: Finally, a crop-predicting app is built using the best-performing model.
