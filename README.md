# Sentiment-Analysis-Project
Project Instructions
The deployment project will be done using Amazon's SageMaker platform. Construct your own Neural Network using Pytorch 
Note: Please note that on of the main difference between PyTorch and XGboost is that you will provide your Own code. Follow the instructions in the notebook and complete the independent code outside the Notebook. 
The project is composed of a train.py folder which you will use to train the model. You will need to make some changes to the serve folder in order to deploy the model. 
Last, create a website that will react with the an endpoint that yoyu will set up. 

##Summary 
1Preparing and Processing Data
2Build and Train a PyTorch Model
3Deploy a Model for Testing
4Use the Model for Testing
5Deploying a Web App

###Instructions to set up a Notebook Instance 

Setting up a Notebook Instance
The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

If you have not yet done this, please see the beginning of Lesson 2 in which we walk through creating a notebook instance and cloning the deployment repository. Alternatively, you can follow the instructions below.

First, start by logging in to the AWS console, opening the SageMaker dashboard and clicking on Create notebook instance.

You may choose any name you would like for your notebook. Also, using ml.t2.medium should be all that is necessary for the project. In addition, an ml.t2.medium instance is covered under the free tier.

Next, under IAM role select Create a new role. You should get a pop-up window that looks like the one below. The only change that needs to be made is to select None under S3 buckets you specify, as is shown in the image below.

Create an IAM role dialog box
Once you have finished setting up the role for your notebook, your notebook instance settings should look something like the image below.

Notebook instance settings
Note that your notebook name may be different than the one displayed and the IAM role that appears will be different.

Next, scroll down to the section labelled Git repositories. Here you will clone the https://github.com/udacity/sagemaker-deployment.git repository.

Once you have filled in all of the required values, the settings should look as so:


You're done! Click on Create notebook instance.

Your notebook instance is now set up and ready to be used!

Once the Notebook instance has loaded, you will see a screen resembling the following.
You can access your notebook using the Action "Open Jupyter".
