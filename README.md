# jubsy.io

Modern cloud-native web application stack for jubsy.io, combining a dynamic front-end with a secure, scalable AWS serverless backend.

---

## 📌 Overview

This repository contains the public front-end codebase for jubsy.io.
The application is designed to be framework-flexible — currently implemented in Angular, but adaptable to React, Vue, or other front-end technologies.

The backend is built using AWS serverless services to ensure low operational cost, global scalability, and strong security.

---

## 🏗 Architecture



---

## 🛠 Tech Stack

### Frontend
	•	Angular (current) — SPA framework
	•	TypeScript, HTML, SCSS
	•	Build/deploy pipeline to S3 + CloudFront

### Backend
	•	AWS API Gateway
	•	AWS Lambda (Python / FastAPI)
	•	AWS DynamoDB
	•	AWS Cognito for authentication
	•	AWS CloudFront for global delivery

### Infrastructure
	•	AWS Free Tier
	•	Cloudflare DNS & Email Routing
	•	Future Terraform automation

---

## 🚀 Deployment

### Current
	•	Manual deploy to AWS S3 & CloudFront
	•	API Gateway endpoints connected to Lambda

### Planned
	•	CI/CD pipeline via GitHub Actions
	•	Infrastructure as Code with Terraform

---

## 🔒 Security
	•	API Gateway rate limiting
	•	Cognito authentication & JWT-based authorization
	•	Cloudflare DNS protection

---

## 📧 Contact

### For inquiries about this project:
	•	Public inquiries: support@jubsy.io
	•	Security issues: security@jubsy.io

---

### 💡 This project is currently in active development. Features, architecture, and technologies may evolve over time.

