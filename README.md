# salary_ml_model
### Pyspark project for predicting salary with xgboost regressor


### Requirements
#### Databricks Runtime Version 12.2 LTS MS (includes Apache Spark 3.3.2, Scala 2.12)  
- dython==0.7.3  
- jdc==0.0.9  
- missingno>=0.5.2  
- missingpy  
- numpy==1.20.3  
- pycaret==3.0.0


### Data

Stack Overflow salary survey for 2021 . csv file

### Content - main steps
- Configuration
- Getting the data
- EDA - exploring the data
- Preprocess/Prepare the data
- Feature selection - filtering columns, running correlations
- Feature engineering - OneHotEncoder, Yeo-johnson, parameters tuning
- ML experiments - XGBRegressor, RandomForestRegressor
- Evaluation

### Runs folder
- run_preprocess
- run_feature_selection
- run_feature_engineering
- run_ml
- run_pycart

