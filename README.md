A COVID-19 Prediction Model Using Symptoms

   1.Model Predictors and Exact Variable Names (True = 1, False = 0)
   2.Age over 60 - Age_60
   3.Sex - Male (Male=1, Female=0)
   4.Cough - Cough
   5.Shortness of breath - Shortness_of_breath
   6.Fever - Fever
   7.Sore throat - Sore_throat
   8.Headache - Headache
   9.Contact with a confirmed individual - Contact_with_confirmed

Model Outcome :

The probability of being diagnosed with a COVID-19 infection.

Use:
   1.Import lgbm_model_*.txt using LightGBM 2.3.1 on Python 3.6.

   2.Predict using your data.

Files in this repository:
   1.lgbm_model_all_features.txt - The predictor that uses all 8 features
   2.lgbm_model_balanced_features.txt - The predictor that uses only balanced symptoms
   3.hyperparameters.txt - The hyperparameters used by lightGBM
   4.data/corona_tested_individuals_ver_0083.english.csv.zip
   5.data/corona_tested_individuals_ver_006.english.csv.zip 
