# Machine Learning Challenge 2023 - GDSC

## Challenge description
Using the [pokemon dataset](https://www.kaggle.com/datasets/alopez247/pokemon), build a ML model (using KNN algorithm) predicting whether a particular Pokemon is a legendary Pokemon or not 

## Implementation Steps
1. **Data Loading** - Importing the necessary libraries along with the pokemon data (.csv file)
2. **Data Exploration** - This step involves getting familiar with the data by knowing the following:
   - Finding the number of attributes and samples present in the data
   - Getting a statistical analysis of the data
   - Checking the presence of null values
   - Checking if the dataset is balanced or not.
   - And finally, listing out the observations about the data.

  3. **Data Preprocessing** - This is one of the most important steps in Machine Learning, as it involves converting the raw data into a format which the machine can understand and learn patterns.

     To preprocess the pokemon data, I have performed the following steps: <br>
     1. Creating the balanced dataset (Provided the data is imbalanced)
     2. Handling the missing/null values
     3. Creating Features and Labels from the dataset
     4. Handling categorical features (One-Hot encoding for nominal categorical features, Label encoding for ordinal categorical features)
     5. Handling numerical features (Normalization/Standardization)
     6. Creating Training and Testing splits

4. **Implementing the KNN Algorithm**
5. **Evaluating the model** - Since it is binary classification problem, I have used the following evaluation metrics to evaluate the KNN model created :
     - Accuracy
     - Precision
     - Recall
     - F1 score
     - Confusion Matrix
     - ROC curve
  
## Results
After going through the above mentioned steps, following results were observed:<br>
**Accuracy - 96%** <br>
**Precision - 93%** <br>
**Recall - 100%** <br>
**F1 score - 97%** <br>

## Guide to run the code
Download the dataset from [here](https://www.kaggle.com/datasets/alopez247/pokemon). Then replace the path in 'pd.read_csv("___")' with the actual path of your downloaded dataset. After that, you are good to go!. You can run all the cells.
