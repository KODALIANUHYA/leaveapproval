# leaveapproval
leave request approval application using aws services 

Services Used:
The mechanism you are referring to is the flow of data between various AWS services, such as:

API Gateway
AWS DynamoDB
AWS SES
AWS S3
AWS Lambda

Mechanism:
Here is a brief explanation of how this mechanism works:

1.An HTML form is hosted on a web page and served to the user through a web server. The user fills out the form with their details and submits it.
2.The form data is sent to API Gateway, which is a fully managed service that allows developers to create, deploy, and manage APIs at any scale. API Gateway acts as a front door for the backend services and APIs that power the application, and it is responsible for securely routing the request to the appropriate backend service or function.
3.The request is then forwarded to a Lambda function, which is a serverless compute service that runs code in response to events and automatically manages the underlying compute resources. The Lambda function receives the form data and performs the necessary processing, such as storing the data in DynamoDB and sending an email notification.
4.The Lambda function interacts with DynamoDB, which is a fast and flexible NoSQL database service that provides consistent, single-digit millisecond latency at any scale. DynamoDB is used to store the form data and retrieve it later when needed.
5.The Lambda function also interacts with SNS, which is a highly available, durable, secure, fully managed pub/sub messaging service that enables decoupling and scaling microservices, distributed systems, and serverless applications. SNS is used to send a message to a topic, which can then be delivered to multiple recipients, such as email addresses, mobile devices, and other endpoints.
6.Finally, the Lambda function interacts with SES, which is a highly scalable, cost-effective, and flexible email-sending service that enables businesses to send transactional emails, marketing messages, and other types of high-quality content to their customers. SES is used to send an email notification to the user, confirming that their form submission has been received and processed.Overall, this mechanism leverages the power of multiple AWS services to provide a scalable, reliable, and cost-effective solution for processing HTML form submissions and storing them in DynamoDB while also sending email notifications to the user.

for more : https://www.linkedin.com/pulse/leave-request-approval-application-using-aws-services-anuhya-kodali-lt4xc/?trackingId=V11UC5AkXo1hEUxZddL4Fg%3D%3D

