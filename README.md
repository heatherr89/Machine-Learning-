# Machine-Learning 

Performed an analysis on mental health data using Random Forest algorithm. 

Linked to Kaggle Data: https://www.kaggle.com/osmi/mental-health-in-tech-survey

# Results
The model predicts 54% accuracy and states that the most important affects that affect the responses of yes,no and maybe are:
- Country
- No of employees
- Whether they have leave
- Consequences of discussing mental health with supervisor 

PCA was used in which it reduced the data into 4 components
Looked at the components attributes coefficients which let us know the most important original features  in the components
  - Country
  - No of employees
  - Leave 
  - Benefits
Then the reduced data  was added to the model with a 42% accuracy
Identified which component was better at predicting the model
- Component 3 
