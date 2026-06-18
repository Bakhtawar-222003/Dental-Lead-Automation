# 🦷 Dental Clinic Lead Automation System (Frontend + n8n Workflow)

This project is a **full-stack automation system** designed for dental clinics to manage appointment enquiries efficiently. It combines a modern frontend (Lovable AI website), backend automation (n8n), and CRM storage (Google Sheets), along with automated email notifications.

Users submit appointment requests through a web form, which triggers an automated workflow that validates data, classifies leads, stores them in a CRM, and sends confirmation emails.

---

## 🚀 Live System Overview

**Frontend (Lovable Website)**  
→ User submits dental appointment form

**Backend (n8n Webhook)**  
→ Receives form data in real-time

**Automation Engine (n8n Workflow)**  
→ Processes, validates, and routes data

**CRM (Google Sheets)**  
→ Stores structured lead information

**Email System (Gmail API)**  
→ Sends automated confirmation emails

---

## Live Demo

🔗 View the live website: https://glow-book-appointment.lovable.app/


## ✨ Features

- Modern AI-generated frontend form (Lovable)
- Real-time webhook integration with n8n
- Data normalization using Set node
- Rule-based lead validation using JavaScript
- Lead classification (Genuine vs Fake)
- Google Sheets CRM storage system
- Automated email confirmation system

---

## 🛠️ Tech Stack

- Lovable AI (Frontend)
- n8n (Workflow Automation)
- JavaScript (Validation Logic)
- Google Sheets API (CRM Database)
- Gmail API (Email Automation)
- Webhooks (Backend Integration)

---

## 🔄 Workflow Architecture

1. User fills appointment form on Lovable website  
2. Data is sent to n8n via webhook/form trigger  
3. Data is cleaned and standardized using Set node  
4. JavaScript validates email and Pakistani phone number  
5. Lead is classified as **Genuine** or **Fake**  
6. Data is stored in Google Sheets CRM  
7. Automated confirmation email is sent to user  

---

## 🧠 Validation Logic

### Email Validation
- Uses regex pattern to ensure correct email format

### Phone Validation (Pakistan)
- Supports formats like:
  - 03XXXXXXXXX
  - 923XXXXXXXXX
  - 3XXXXXXXXX
- Removes spaces and special characters before validation

### Lead Classification
- **Genuine Lead:** Valid name, email, and phone number
- **Fake Lead:** Fails validation checks

---

## 📊 Project Highlights

- End-to-end automation system for real-world business use
- Combines frontend + backend + CRM integration
- Demonstrates API/webhook integration
- Shows practical JavaScript validation logic
- Scalable design for clinics and small businesses
- No-code + low-code hybrid system

---

## 🔮 Future Improvements

- WhatsApp / SMS notifications for instant follow-ups
- AI-based lead scoring system
- Appointment scheduling automation
- Admin dashboard for analytics
- Integration with CRM tools (HubSpot / Zoho)

---

## 📌 Note

This project is built for educational and portfolio purposes. All credentials, webhook IDs, and sensitive configuration values have been removed for security.

---

## 👨💻 Author

Built as a full-stack automation portfolio project demonstrating:
- Workflow automation (n8n)
- API integration (Webhooks)
- Frontend development (Lovable AI)
- Backend logic (JavaScript)
- CRM system design (Google Sheets)
