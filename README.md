# Image-Editing-Tool

Image-Editing-Tool is a serverless web application that enables users to generate and edit images using Generative AI prompts. The application is built entirely on AWS using managed, scalable services and integrates Amazon Bedrock for AI-powered image generation. This project demonstrates how modern GenAI applications can be built without managing servers or machine learning infrastructure.

---

## 🚀 Features

- AI-powered image generation and editing using text prompts
- Secure user authentication and authorization
- Fully serverless backend architecture
- Scalable REST APIs
- Persistent storage for image metadata and prompts
- Web-based frontend with seamless backend integration

---

## 🧩 Problem Statement

Building AI image editing applications traditionally requires managing servers, scaling infrastructure, and handling complex ML workflows. These challenges increase development time and operational costs, especially for individual developers and small teams.

Image-Editing-Tool addresses this by using a serverless architecture and managed AI services, allowing developers to focus on application logic while AWS handles scalability, security, and reliability.

---

## 🏗️ Architecture Overview

The application follows a cloud-native, serverless architecture using AWS managed services.

![Image-Editing-Tool Architecture Diagram](./ImageEditApp-Architecture.png)

### Architecture Flow

1. Users access the application through a web browser.
2. The frontend (HTML, CSS, JavaScript) is hosted on AWS Amplify.
3. Users authenticate securely using Amazon Cognito.
4. The frontend sends API requests over HTTPS to Amazon API Gateway.
5. API Gateway invokes AWS Lambda functions.
6. Lambda interacts with Amazon Bedrock to generate or edit images using AI prompts.
7. Image metadata and request history are stored in Amazon DynamoDB.
8. Generated results are returned to the frontend in real time.

---

## ⚙️ AWS Services Used

- **Amazon Bedrock** – Generative AI image generation (Titan Image Generator G1)
- **AWS Lambda** – Serverless backend logic
- **Amazon API Gateway** – Secure REST APIs
- **Amazon Cognito** – User authentication and authorization
- **Amazon DynamoDB** – Storage for image metadata and prompts
- **AWS Amplify** – Frontend hosting and deployment
- **AWS IAM** – Secure access control and permissions

---

## 🎥 Demo & Screenshots

### Live Demo
> *(Add your deployed application URL here)*

### Screenshots
> *(Add screenshots showing the UI, authentication flow, and AI-generated image results)*

Example:
- Login & Authentication Screen
- Image Prompt Input Interface
- Generated / Edited Image Output
- Stored Image Metadata View

You can place screenshots inside a `/screenshots` folder and reference them here:
