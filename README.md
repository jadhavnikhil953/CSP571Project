# CSP571Project

# Heart Dataset Analysis

In this project, we have processed the heart dataset, which contains the data of symptoms of the patients. We performed the Exploratory Data Analysis (EDA) to analyze and gain insights into the dataset. We plotted the distplot and countplot for the numerical and the categorical variables, respectively, together with a heatmap to summarize the overall correlation of the variables.

## Exploratory Data Analysis

The EDA process involved the following steps:

- Loading the dataset and checking its basic statistics
- Checking for missing values and handling them appropriately
- Visualizing the distribution of numerical variables using distplot
- Visualizing the frequency of categorical variables using countplot
- Creating a heatmap to display the correlation between the variables

## Model Training

After performing the EDA, we trained models on the 80-20 train to test split using 4 algorithms: Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine. Our goal was to predict the risk of heart disease based on the given symptoms.

## Results

Our results show that the Random Forest model obtains the highest performance with the chest pain type (cp) being the most important factor in determining the risk of heart disease. The accuracy of the model was 100% for training data and 85% for testing data.

## Conclusion

In conclusion, this project provides insights into the heart dataset using EDA and trains machine learning models to predict the risk of heart disease. The Random Forest model performs the best, and the chest pain type (cp) is the most important factor in determining the risk of heart disease.
