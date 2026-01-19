# Building a Serverless AI Pipeline with AWS Bedrock

Excited to share my latest project: a full-stack, production-ready application for AI-driven content generation, built using a fully serverless AWS architecture.

Tech Stack:

User Access: S3 Bucket (Static Website) Loads index.html with login/signup interface
LLM: Anthropic Claude 3.5 Sonnet via Amazon Bedrock
Authentication: Amazon Cognito (User Pools & App Clients)
Compute: AWS Lambda (Python 3.12)
API Layer: Amazon API Gateway (REST API)
Security: Custom IAM policies for Bedrock InvokeModel and Cognito GetUser permissions.

🔐 Key Takeaway
By combining Lambda Proxy integration with custom token verification, the application ensures that only authenticated users can access the LLM, helping to control costs, enforce access boundaries, and keep data secure.

#SoftwareEngineering #AWS #AWSLambda #AmazonBedrock #Cognito #ClaudeAI #Serverless #CloudArchitecture #BackendDevelopment #AIEngineering
