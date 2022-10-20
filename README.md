# Experiment-tracking
This is for experiment tracking with MLFlow

step-1:
open cmd prompt

Step-2:
# code to create new environment
conda create -n exp-tracking-env python=3.9

Step-3:
# activate the environment
conda activate exp-tracking-env

Step-4:
# install the requirements.txt using the below code
 pip install -r requirements.txt
 
 # to check all the packages installed 
 # pip list
 
 Step-5:
 # Access the mlflow ui run this in terminal but in the same folder where the project is present
 mlflow ui --backend-store-uri sqlite:///mlflow.db
