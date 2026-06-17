# ☁️ Cloud AI Chatbot – Serverless Chatbot Using AWS

## 🚀 Project Overview  
This project demonstrates the development and deployment of a serverless AI-powered chatbot using AWS cloud services.

The chatbot provides instant responses to user queries through an interactive web interface. The frontend is hosted on Amazon S3, API requests are managed using API Gateway, AWS Lambda processes the requests, and DynamoDB stores the chatbot knowledge base.

---

## 🧰 Tech Stack  
- GitHub  
- HTML, CSS, JavaScript  
- Python  
- AWS Lambda  
- Amazon API Gateway  
- Amazon DynamoDB  
- Amazon S3 Static Website Hosting  
- AWS IAM  
- Amazon CloudWatch  

---

## 🏗️ Architecture  

User Browser → Amazon S3 Static Website → API Gateway → AWS Lambda → Amazon DynamoDB → Chatbot Response  

The chatbot frontend sends user messages to API Gateway, which triggers a Lambda function. Lambda retrieves the appropriate response from DynamoDB and returns it back to the web application.

---

## ✨ Features  

- Interactive cloud-themed chatbot interface  
- Serverless backend architecture  
- Real-time communication using REST APIs  
- DynamoDB-based knowledge retrieval system  
- Static website hosting with Amazon S3  
- Secure access management using AWS IAM  
- API monitoring and logging using CloudWatch  

---

## 📸 Screenshots  

<img width="1918" height="990" alt="Screenshot 2026-06-17 182728" src="https://github.com/user-attachments/assets/9b0f7501-e986-4b6a-81ea-8ae2a141f12b" />
<img width="1918" height="985" alt="Screenshot 2026-06-17 182805" src="https://github.com/user-attachments/assets/83693133-b759-4dc5-8be2-3021413dd4f4" />
<img width="1917" height="986" alt="Screenshot 2026-06-17 182748" src="https://github.com/user-attachments/assets/c173c44c-3d61-4e62-b91f-9003c0df3883" />
<img width="1918" height="1093" alt="Screenshot 2026-06-17 182443" src="https://github.com/user-attachments/assets/532935c5-d60d-4e7c-a893-93a632ccb3ba" />

---

## 🧠 What I Learned  

- Building serverless applications using AWS services  
- Integrating frontend applications with cloud APIs  
- Creating and managing REST APIs using API Gateway  
- Developing backend logic using AWS Lambda and Python  
- Storing and retrieving data using DynamoDB  
- Configuring CORS, IAM permissions, and CloudWatch logs  
- Hosting static websites using Amazon S3  

---

## ⚙️ Deployment Steps  

1. Create a DynamoDB table to store chatbot questions and answers.

2. Create an AWS Lambda function and connect it with DynamoDB.

3. Configure API Gateway and create a POST endpoint for chatbot communication.

4. Enable CORS to allow communication between the S3 hosted frontend and API Gateway.

5. Develop the chatbot frontend using HTML, CSS, and JavaScript.

6. Upload frontend files to Amazon S3 and enable static website hosting.

7. Connect the frontend with the API Gateway endpoint and test the complete application.

---

## ⚠️ Note  

- Ensure IAM roles have appropriate permissions to access DynamoDB and other AWS services.
- Configure API Gateway CORS settings correctly for frontend communication.
- Monitor Lambda execution and troubleshoot issues using CloudWatch logs.
- Use AWS Free Tier resources responsibly to avoid unexpected charges.

---

## 💼 Resume Highlight  

Designed and deployed a serverless Cloud AI chatbot using AWS Lambda, API Gateway, DynamoDB, and Amazon S3. Implemented real-time API communication, NoSQL data management, and static website hosting using cloud-native AWS services.
