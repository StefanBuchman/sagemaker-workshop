# Customer Churn Prediction with XGBoost

Losing customers is costly for any business. Identifying unhappy customers early on gives you a chance to offer them incentives to stay. This notebook describes using machine learning (ML) for the automated identification of unhappy customers, also known as customer churn prediction. ML models rarely give perfect predictions though, so this notebook is also about how to incorporate the relative costs of prediction mistakes when determining the financial outcome of using ML.

We use an example of churn that is familiar to all of us–leaving a mobile phone operator. Seems like I can always find fault with my provider du jour! And if my provider knows that I’m thinking of leaving, it can offer timely incentives–I can always use a phone upgrade or perhaps have a new feature activated–and I might just stick around. Incentives are often much more cost effective than losing and reacquiring a customer.

# Directions

1. In your notebook instance, click on the top level folder 'SageMaker Examples'.
2. Navigate to 'xgboost_customer_churn.ipynb' under 'Introduction to Applying Machine Learning'
3. Click 'Use'
4. In the `bucket = '<your_s3_bucket_name_here>'` code line, paste the name of the S3 bucket you created in Module 1 to 
   replace `<your_s3_bucket_name_here>`.  The code line should now read similar to `bucket = 'smworkshop-john-smith'`.
   Do NOT paste the entire path (s3://.......), just the bucket name.
