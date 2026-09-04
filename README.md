# 💬 AWS Serverless Feedback & Contact Form

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Free Tier](https://img.shields.io/badge/Free%20Tier-100%25-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white)
![S3](https://img.shields.io/badge/S3-Frontend-orange?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-Architecture-red?style=for-the-badge)

AWS Serverless Feedback Form is a cloud-native, fully serverless application for collecting and managing user feedback. It uses S3 for frontend hosting, API Gateway and Lambda for backend processing, and DynamoDB & SNS for data storage and real-time email notifications.

---

## 📑 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Architecture](#-architecture)
- [AWS Services Used](#-aws-services-used)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Author](#-author)

---

## 🎯 Overview

FeedbackHub is a production-ready serverless contact form built entirely on AWS. When users fill out a form, their message is saved to DynamoDB, and the site owner receives an instant email notification via SNS — all without managing any servers.

---

## 🚀 Features

- ✅ **Real-time Form Submission:** Responsive UI with dynamic loading state.
- ✅ **Instant Email Alerts:** Automated SNS notifications to site owner.
- ✅ **NoSQL Persistence:** Instant, reliable storage of feedback in DynamoDB.
- ✅ **Least-Privilege Security:** Fine-grained IAM policies for execution roles.
- ✅ **100% Serverless:** Zero server management and high availability.
- ✅ **Free Tier Friendly:** Cost-optimized architecture.

---

## 📐 Architecture

![AWS Architecture Diagram](images/archite.jpeg)

---

## 🛠️ AWS Services Used

| Service | Role | Free Tier Limit |
| :--- | :--- | :--- |
| **Amazon S3** | Hosts static frontend files | 5GB storage |
| **Amazon API Gateway** | REST API endpoints | 1M requests/month |
| **AWS Lambda** | Backend business logic | 1M requests/month |
| **Amazon DynamoDB** | Stores all submitted messages | 25GB storage |
| **Amazon SNS** | Immediate email notifications | 1,000 emails/month |
| **AWS IAM** | Granular execution permissions | Always Free |

---

## 📁 Project Structure

```text
├── Frontend/
│   ├── index.html       # Web form interface
│   ├── style.css        # Responsive design & styles
│   └── script.js        # API integration & dynamic JS
├── Lambda/
│   └── lambda_function.py # Python backend script
```

---

## 📸 Screenshots & Project Proofs

### 1. User Interface
![User Interface](images/user-interface.png)
*Responsive feedback form with dynamic loading state.*

### 2. Lambda & API Gateway
![Lambda Function](images/lambda-function.png)
![API Gateway](images/api-gateway.png)
*Lambda function code and API Gateway endpoint configuration.*

### 3. IAM Least-Privilege
![IAM Policy](images/iam-policy.png)
*Fine-grained IAM execution role with least-privilege permissions.*

### 4. DynamoDB Storage
![DynamoDB Table](images/dynamodb-table.png)
*Submitted feedback messages stored in DynamoDB.*

### 5. Amazon SNS Topic
![SNS Topic](images/sns-topic.png)
*SNS topic configuration for email notifications.*

### 6. Email Notification
![Email Notification](images/email-notification.png)
*Instant email alert received upon form submission.*

---

## 👨‍💻 Author

**Mostafa Mohamed Abdrabo**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mostafa-m-abdrabo/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mostafaabdrabo2022)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mostafaabdrabo4900@gmail.com)

---
