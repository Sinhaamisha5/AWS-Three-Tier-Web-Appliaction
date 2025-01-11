# Build a Three-Tier Web App | AWS Project Demo


This project demonstrates how to build a Three-Tier Web Application using a variety of AWS services. It integrates Lambda, DynamoDB, CloudFront, API Gateway, and S3 to create a fully functional, scalable web application with dynamic data processing.

Key Features:

Lambda: Used for serverless backend logic to handle requests and interact with DynamoDB.

DynamoDB: A NoSQL database used to store and retrieve user data efficiently.

API Gateway: Exposes the Lambda functions via RESTful APIs for seamless communication.

CloudFront: Acts as the CDN to deliver static content faster to end-users globally.

S3: Used for storing and serving static web assets (HTML, CSS, JavaScript files).

This application showcases how to seamlessly connect various AWS services to build a powerful, cost-effective web app. You can interact with the app by sending HTTP requests to an API Gateway endpoint, where Lambda functions process the data and return responses based on the DynamoDB contents.
