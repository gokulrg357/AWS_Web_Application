# Serverless Web Application on AWS

This repository contains the code and configuration for a serverless web application deployed on AWS. The application utilizes various AWS services to create a scalable, secure, and efficient architecture.

## Architecture Overview

The application consists of the following components:

- **S3 Bucket**: Hosts the static web content (HTML, CSS, and JavaScript files).
- **API Gateway**: Exposes RESTful API endpoints to trigger Lambda functions.
- **Lambda Functions**: Handle backend logic and interact with DynamoDB for data storage.
- **DynamoDB**: NoSQL database used to store application data.
- **CloudFront**: Content Delivery Network (CDN) used for secure and optimized content delivery over HTTPS.

## Features

- Static web hosting with S3
- RESTful API with API Gateway
- Serverless backend with Lambda functions (Python)
- DynamoDB for data storage and CRUD operations
- Secure content delivery with CloudFront over HTTPS

## Setup Instructions

1. **Create S3 Bucket**: Set up an S3 bucket to host your static files.
2. **Configure API Gateway**: Create endpoints for your Lambda functions.
3. **Create Lambda Functions**: Write Lambda functions in Python for data handling.
4. **Set Up DynamoDB**: Create a DynamoDB table and define the schema.
5. **Configure CloudFront**: Secure your application using CloudFront.

## Usage

Once deployed, the web application will be accessible via the CloudFront distribution URL. The API endpoints will handle user requests for data retrieval and storage through Lambda and DynamoDB.
