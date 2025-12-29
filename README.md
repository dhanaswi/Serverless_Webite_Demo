# Serverless Website Using AWS Lambda and API Gateway

This project demonstrates how to build and deploy a serverless website using AWS Lambda, API Gateway, and Amazon S3.
It shows how backend logic can be executed without managing servers while S3 hosts the static frontend efficiently.


## Prerequisites

- An AWS account
- Basic knowledge of AWS Console
- Static website files (index.html, error.html, Lambda Python code)
- Internet access


## Step 1: Create an AWS Lambda Function

1. Sign in to the **AWS Management Console**
2. Search for **Lambda** and open the service
3. Click **Create function**
4. Select **Author from scratch**
5. Enter a function name (example: Serverless-function)
6. Choose **Python** (latest version) as runtime
7. Select **x86_64** architecture
8. Select **Create a new role with basic Lambda permissions** in Execution role
9. Click **Create function**
<br>
<p align="center">
<img src="1.png" width="500">
