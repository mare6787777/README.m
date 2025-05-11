# 🤖 AI-Powered Customer Insights Platform

## Overview
A serverless, intelligent contact form system that transforms basic customer messages into structured insights using NLP, AWS Lambda, and real-time analytics. Built entirely on AWS Free Tier services.

---

## 🔍 Features

### 🧠 Smart Categorisation with NLP
- Uses Amazon Comprehend to extract sentiment and key phrases.
- Auto-categorizes messages into 'Sales', 'Support', 'Complaint', etc.
- Assigns priority scores based on sentiment and keyword matches.

### 📊 Real-Time Analytics Dashboard
- Stores enriched message data in S3.
- Uses Athena and QuickSight (or custom dashboards) to visualize contact trends.

### ⚙️ Fully Serverless Architecture
- Frontend submits contact messages via API Gateway to Lambda.
- Lambda processes and stores data with S3 + Comprehend.
- All services run on AWS Free Tier (no server management).

---

## 🛠️ Tech Stack
- **Frontend**: HTML + JavaScript + API Gateway
- **Backend**: AWS Lambda (Python)
- **AI/NLP**: Amazon Comprehend
- **Storage & Analytics**: Amazon S3, Athena, QuickSight

---

## 🚀 Use Case
Designed for startups, internal service desks, or customer teams who want fast insight without expensive platforms.

---

## 🔒 Security
- Input validation and basic sanitization
- IAM Roles with least-privilege access

---

## 💡 Future Improvements
- Add chatbot interface
- Include translation via Amazon Translate
- Integrate with CRM platforms (e.g., Salesforce or HubSpot)

