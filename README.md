# CodeTech-Task-2
Name: BHASKAR SIGNH BISHT

Company: CODTECH IT SOLUTIONS

Id: CT08DS6286

Domain: Cloud Computing

Duration: Augest to september 2024

Overview of the Project:

In this project, you developed a serverless web application by leveraging AWS services like Lambda, S3, and DynamoDB. The primary goal was to create a scalable, cost-efficient, and highly available application without managing any server infrastructure.

Components:
1.AWS Lambda:
*Used for executing backend logic without the need for managing servers.
*Functions were triggered by HTTP requests (through API Gateway) or events in S3/DynamoDB.
*Handled tasks such as processing user input, interacting with the database, and returning responses to the client.

2.Amazon S3:
Acted as the storage layer for static assets (HTML, CSS, JavaScript files, images, etc.).
Configured as a static website to host the front-end of your application.
S3’s built-in versioning and lifecycle policies ensured data durability and cost optimization

3.Amazon DynamoDB:
A NoSQL database service used to store application data.
Offered seamless scalability, high availability, and low-latency performance.
DynamoDB tables were designed with the appropriate partition keys and indexes for efficient querying.

4.Architecture Workflow:
Frontend (S3): Users interact with the static web pages hosted on S3. The frontend sends HTTP requests to the backend via the API Gateway.
Backend (Lambda): API Gateway routes requests to the appropriate Lambda functions, which execute the business logic.
Database (DynamoDB): Lambda functions interact with DynamoDB to perform CRUD (Create, Read, Update, Delete) operations on the application data.
Security: Implemented security best practices using IAM roles, API Gateway authorizers, and data encryption.

Benefits:
*Scalability: Automatically scales with demand without manual intervention.
*Cost Efficiency: Pay only for the compute time used (Lambda) and the storage consumed (S3 and DynamoDB).
*Reduced Complexity: No need to manage server infrastructure, resulting in faster development and deployment.
This overview captures the essence of your project and highlights the key components and benefits of using a serverless architecture.

