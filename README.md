# Loan_Default_Prediction_Spark
Use Spark to Analyze 1.5 GB Data of 2 Million Loans

# Goal
1. Analyze 1.5GB of loan data with 2 million clients from Lending Club
2. Build predictive model for loan default
3. Discover useful features for predicting loan default
4. Assess current interest rate policy of Lending Club

# Key Findings and Business Insights
##### 1. The decision of Leading Club on interest rate is working well in general.
##### 2. The decision of the Lending Club on the loan grades works well on the clients with low credit risk.
##### 3. The clients show self-selection behavior. This finding is helpful to decrease the cost on information acquisition.
##### 4. Based on the finding of the self-selection behavior, Lending Club could increase the long-term interest rate as the premium for higher default risk.
##### 5. The number of mortgage is a good predictor.
##### 6. The threshold for the model should be properly tuned according to the estimated profit from correct predictions and the estimated cost of wrong predictions.
##### 7. Extension: In the use case of building a predictive model for Lending Club to make loan decision, the same methodology can be applied on the same dataset without endogenous features (interest rate and loan grades).
