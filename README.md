# Demo
https://github.com/juggernaut09/wildrydes-site/assets/25864009/845f9ea4-2875-46e0-a4b9-ce5d02ac6af7

# SAM Architecture
![Screenshot 2024-05-28 182547](https://github.com/juggernaut09/wildrydes-site/assets/25864009/eca4897a-ba58-4246-bc36-7bf291633d4c)

# Wild Rydes Serverless Web Application
Welcome to the Wild Rydes serverless web application project! This application allows users to request unicorn rides from the Wild Rydes fleet. The project includes an HTML-based user interface for indicating a pick-up location and a RESTful web service on the backend to submit requests for dispatching a unicorn. Additionally, it provides user registration and login functionalities to ensure a secure and personalized experience.

The Wild Rydes serverless web application leverages AWS cloud services to deliver a scalable and secure platform for requesting unicorn rides. Users can sign up, log in, and specify their pick-up locations via a user-friendly web interface. The backend processes these requests and dispatches unicorns accordingly.

## The application consists of the following components:

> Static Web Hosting: Hosted on AWS Amplify, providing HTML, CSS, JavaScript, and image files.
> User Management: Managed by Amazon Cognito for secure authentication and authorization.
> Serverless Backend: Implemented using AWS Lambda for handling business logic.
> RESTful API: Exposed through Amazon API Gateway to interact with the Lambda functions.
> Data Persistence: Utilizes Amazon DynamoDB for storing request data.

## Technologies Used
> AWS Lambda: Executes backend code in response to events.
> Amazon API Gateway: Creates and manages RESTful APIs to access Lambda functions.
> Amazon DynamoDB: Provides a NoSQL database for storing application data.
> Amazon Cognito: Manages user registration, authentication, and authorization.
> AWS Amplify: Hosts the static web resources and supports continuous deployment.

# Setup and Deployment

## Hosting the Static Website
> Configure AWS Amplify to host the static resources for your web application, ensuring continuous deployment is set up for easy updates and maintenance.

## Managing Users
> Create an Amazon Cognito user pool to handle user accounts, providing secure registration and login capabilities for the application.

## Building the Serverless Backend
> Develop backend processes using AWS Lambda to handle ride requests from users. These functions will execute the core logic of the application.

## Deploying the RESTful API
> Use Amazon API Gateway to expose the Lambda functions as a RESTful API, allowing the frontend to communicate with the backend seamlessly.

## Terminating Resources
> After completing the project, terminate all resources to prevent any ongoing costs. This step ensures that no unnecessary charges are incurred post-deployment.

## Cost and Time Estimate
> Time to Complete: Approximately 2 hours
> Cost to Complete: Less than $0.25 if you stay within the AWS Free Tier limits and terminate all resources within 24 hours.

## AWS Free Tier
> All services used in this project are eligible for the AWS Free Tier. If you exceed the Free Tier usage limits, the cost of completing this project remains minimal.

> Note: New AWS accounts may not have immediate access to all required resources. Ensure your account is fully set up before proceeding.


