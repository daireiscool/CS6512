# AWS Workflow Design and ML

Commands to run the second e-tivity for CS6512 in University Limerick.  
In this e-tivity, we are be granted with access to an AWS Academy Learner Lab - Foundation Services, and asked to:  
1. Follow the provided instructions to set up your AWS environment.
2. Implement an Outlier Detector for cryptocurrency rates by using the outlier-detection algorithms covered in class:
        * Enhanced Dixon Q
        * Mean & Standard Deviation
        * Isolation Forest

The outlier detector shall be implemented in Python and run on AWS.

#### Implementation Subtasks

This e-tivity has two distinct subtasks:
1. Detecting outliers among cryptocurrency history rates
2. Detecting outliers among cryptocurrency live-exchange rates

#### Subtask #1: Detecting outliers among cryptocurrency history rates

1. Set up an AWS local environment and AWS S3 storage space.
2. Implement an outlier detector that runs in the local AWS environment and:
        * loads csv data from the AWS S3 storage space and produces an outlier report
        * gets hystory rates from the marketplace CryptoCompare.com and produces an outlier report

#### Subtask #2: Detecting outliers among cryptocurrency live-exchange rates

1. Set up an AWS Lambda function that is invoked on a time basis - every 30 sec. This Lambda function shall trigger the execution of your Outlier Detector.
2. Implement a new feature of your Outlier Detector, so it will:
        1. Get live-exchange cryptocurrency rates from the marketplace CryptoCompare.com.
        2. Store these cryptocurrency rates.
        3. Detect outliers among these cryptocurrency rates.


#### Delivery

The result of all 3 options should be the same: you need to deliver:

    * the code of Assignment #2 (cs6512_assignment_2.py); 
        for Option 3, you are asked to deliver a notebook file (cs6512_assignment_2.ipynb) instead of a python file;
    * the result files as shown in the provided Assignment2.zip archive.
