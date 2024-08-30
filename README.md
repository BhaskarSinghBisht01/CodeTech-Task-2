# CodeTech-Task-2
Name: BHASKAR SIGNH BISHT

Company: CODTECH IT SOLUTIONS

Id: CT08DS6286

Domain: Cloud Computing

Duration: Augest to september 2024

Deploying a Serverless Web Application

Overview of the Project: The goal of this project was to deploy a serverless web application that showcases a simple greeting webpage. The webpage includes a dynamic feature that displays the number of views the site has received, with the count updating automatically.

Key Components:

1.AWS Lambda:
Functionality: AWS Lambda is the core of your serverless architecture. It handles backend logic without the need for server management. In this project, Lambda functions were used to interact with DynamoDB and retrieve/update the view count each time the webpage is loaded.

2.Amazon S3:
Functionality: Amazon S3 (Simple Storage Service) was used to host the static assets of your web application, such as HTML, CSS, and JavaScript files. S3 provides a reliable and scalable way to serve static content to users with low latency.

3.Amazon DynamoDB:
Functionality: DynamoDB is a NoSQL database service that was utilized to store the view count data. The database is highly scalable and managed, making it ideal for serverless applications. Each time the page is accessed, the view count is retrieved from and updated in DynamoDB via the Lambda function.

4.Front-End:
Functionality: The front-end of the application consists of a simple greeting webpage that displays a welcoming message to the user. Additionally, it dynamically shows the number of views the page has received, which is retrieved from DynamoDB. The count is updated in real-time as users visit the page.

5.Architecture:
The application follows a serverless architecture, where the front-end is hosted on S3, and the backend is handled by AWS Lambda and DynamoDB. This architecture eliminates the need for managing servers, reduces costs, and scales automatically based on the number of requests.

6.Deployment Process:
The deployment involved setting up an S3 bucket for hosting the static website, creating a DynamoDB table for storing the view counts, writing a Lambda function to handle the logic of retrieving and updating the view count, and connecting these components using API Gateway or other suitable methods.

7.Outcome:
The final product is a scalable, cost-efficient serverless web application that displays a dynamic greeting page with a live view counter. This project demonstrates the integration of various AWS services to create a fully functional and responsive serverless application.

#OUTPUT

![Screenshot (172)](https://github.com/user-attachments/assets/c31469eb-91d7-4b85-b27a-1f7ce47be536)

