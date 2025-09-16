
# Network Security Project: Phishing Website Detection

 This project focuses on building a Machine Learning pipeline to detect phishing websites and enhance network security. Phishing attacks are one of the most common cyber threats,and     this project leverages data analysis, feature engineering, and classification models to identify phishing attempts effectively.

## Objectives

   Perform Exploratory Data Analysis (EDA) on phishing website dataset.

   Build an end-to-end ML pipeline for preprocessing, feature engineering, model training, and evaluation.

   Compare multiple machine learning algorithms for phishing detection.

   Provide a reproducible and scalable solution for real-world deployment.


### Network Security Projects For Phising Data

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu


newgrp docker
