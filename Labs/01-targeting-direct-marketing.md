# Targeting Direct Marketing with Amazon SageMaker XGBoost

Direct marketing, either through mail, email, phone, etc., is a common tactic to acquire customers. Because resources and a customer's attention is limited, the goal is to only target the subset of prospects who are likely to engage with a specific offer. Predicting those potential customers based on readily available information like demographics, past interactions, and environmental factors is a common machine learning problem.

This notebook presents an example problem to predict if a customer will enroll for a term deposit at a bank, after one or more phone calls. The steps include:

    1. Preparing your Amazon SageMaker notebook
    2. Downloading data from the internet into Amazon SageMaker
    3. Investigating and transforming the data so that it can be fed to Amazon SageMaker algorithms
    4. Estimating a model using the Gradient Boosting algorithm
    5. Evaluating the effectiveness of the model
    6. Setting the model up to make on-going predictions

# Directions

1. In your notebook instance, click on the top level folder 'SageMaker Examples'.
2. Navigate to 'xgboost_direct_marketing_sagemaker.ipynb' under 'Introduction to Applying Machine Learning'
3. Click 'Use'
4. In the `bucket = '<your_s3_bucket_name_here>'` code line, paste the name of the S3 bucket you created in Module 1 to 
   replace `<your_s3_bucket_name_here>`.  The code line should now read similar to `bucket = 'smworkshop-john-smith'`.
   Do NOT paste the entire path (s3://.......), just the bucket name.
