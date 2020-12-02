# DSN-KOWOPE-MALL

# ABOUT KOWOPE:
  Kowope Mart is a Nigerian-based retail company with a vision to provide quality goods, education and automobile services to its customers at affordable price and reduce if not eradicate charges on card payments and increase customer satisfaction with credit rewards that can be used within the Mall.
## OBJECTIVE: 
  To develop a predictive model that determines the likelihood of a customer defaulting loan payment.
### MY APPROACH:
 1. Cleaned the dataset by filling missing values with -999. Some of the columns had missing values >50%, didn't want to drop so as not to miss important features. 
 2. Created few features, although these features had little effect in prediction, I guess the main work is in tuning the hyperparameters
 3. Used two ensemble model in making my predictions. Used a 15fold Catboost and Xgboost Model
 4. Blended the results of both and used it as my Final prediction.
 
Leaderboard Score: 0.8448...

Link to Hackathon:https://zindi.africa/hackathons/dsn-ai-bootcamp-qualification-hackathon
