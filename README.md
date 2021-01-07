# Deploying Models to Production with Mlflow and Amazon Sagemaker !!

* Data Scientists develop and fine tune the Machine Learning Models and then pass on these models to the Engineering team for productization. Traditionally model 
  deployment are handeled by Engineering Team. MlFlow - Open Source machine learning platform helps to bridge the gap and can also work seemlessly with the Amazon   
  SageMaker or AzureML services. 

## Environment Setup Required
We require the following environment setup
* An AWS account CLI
* Docker installed on your local machine
* Python 3.6 with mlflow>=1.0.0 installed

### Configure Amazon CLI
* We need to first install AWS Cli on local system so that we can intract with the AWS Console programatically.
* Create the root account on Amazon console, Log in as the root user and create the new IAM user. Log-off and log-in using the new user account.
* Create an account here if you haven’t already, then run the commands below from a terminal.
```
pip install awscli --upgrade --user
aws configure

```


## Links
* https://allcloud.io/blog/organise-your-ml-experiments-with-mlflow-on-aws/
* https://dev.to/aws/deploying-machine-learning-models-with-mlflow-and-amazon-sagemaker-2hdm
* https://towardsdatascience.com/deploying-models-to-production-with-mlflow-and-amazon-sagemaker-d21f67909198
