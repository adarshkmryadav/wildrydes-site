# Ride-Sharing Application

## Overview 
Wild Rydes is a whimsical, serverless ride-sharing application built using **AWS Amplify** and featuring a unique twist: users can request rides from unicorns! This app allows users to register, log in, and request unicorn rides through an interactive map interface. 
The architecture includes a user-friendly HTML frontend and a robust backend powered by AWS services. 

## Features 
- **Serverless Architecture**: Leveraging AWS Amplify for frontend hosting and AWS Lambda for backend processing.
- **Interactive Map**: Users can request a ride by clicking on the map to select their pickup location.
- **User Authentication**: Managed securely with AWS Cognito, allowing users to create accounts and log in.
- **Real-Time Ride Requests**: Requests are processed in real-time, with ride details stored in a DynamoDB database.

## Architecture 
- **Frontend**: Hosted on AWS Amplify, ensuring seamless updates and deployments from GitHub.
- **Backend**: AWS Lambda functions handle ride requests, with an API built using AWS API Gateway.
- **Database Storage**: User ride requests and data are stored in Amazon DynamoDB.
- **Authentication**: User management is handled via AWS Cognito for secure sign-ups and logins.

## Prerequisites To use or modify this project, you'll need: 
- **AWS account** (with administrator-level access).
- **GitHub account**.

## Conclusion 
Wild Rydes showcases how to build a fun, serverless web application using AWS services. Feel free to explore, modify, and contribute to the project. 
