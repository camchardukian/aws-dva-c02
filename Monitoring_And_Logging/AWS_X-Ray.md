# AWS X-Ray

We can use AWS X-Ray to analyze and debug production and distributed applications.

Specifically notable is X-Ray’s ability to help us trace user requests through our application while still meeting security and compliance objectives.

This can help us identify bottlenecks and determine where high latencies are occurring (and thus how we can improve performance and the user’s experience). AWS X-Ray supports both real-time and historical analysis.

Apart from helping us improve performance, AWS X-Ray can also help us develop a better conceptual understanding of our application by allowing us to visualize and analyze the dependencies between different components of our application such as microservices, databases, and third-party APIs.

AWS X-Ray does require IAM Permissions in order to get information from different AWS services such as EC2, ECS, Lambda, API Gateway, SNS, SQS, etc.
