# Direct Marketing with Amazon SageMaker XGBoost and Hyperparameter Tuning

Direct marketing, either through mail, email, phone, etc., is a common tactic to acquire customers. Because resources and a customer's attention is limited, the goal is to only target the subset of prospects who are likely to engage with a specific offer. Predicting those potential customers based on readily available information like demographics, past interactions, and environmental factors is a common machine learning problem.

This notebook will train a model which can be used to predict if a customer will enroll for a term deposit at a bank, after one or more phone calls. Hyperparameter tuning will be used in order to try multiple hyperparameter settings and produce the best model.

We will use SageMaker Python SDK, a high level SDK, to simplify the way we interact with SageMaker Hyperparameter Tuning.

# Directions

1. In your notebook instance, click on the top level folder 'SageMaker Examples'.
2. Navigate to 'hpo_xgboost_direct_marketing_sagemaker_python_sdk.ipynb' under 'Hyperparameter Tuning'
3. Click 'Use'
4. In the `bucket = '<your_s3_bucket_name_here>'` code line, paste the name of the S3 bucket you created in Module 1 to 
   replace `<your_s3_bucket_name_here>`.  The code line should now read similar to `bucket = '<bucket-name>'`.
   Do NOT paste the entire path (s3://.......), just the bucket name.
