# Employee Support Chatbot

## Project Overview

This project develops an AI-based chatbot designed to assist employees of a large public sector organization. The chatbot uses Natural Language Processing (NLP) and basic deep learning techniques to understand employee queries and provide useful responses.

The chatbot can answer questions related to HR policies, IT support issues, company events, and other organizational information.

---

## Features

### HR and IT Query Support

The chatbot answers common employee questions such as leave policies, password reset procedures, and company announcements.

### Document Processing

Employees can upload documents (8–10 pages). The chatbot can:

* Extract text from documents
* Generate a short summary
* Identify important keywords

### Two Factor Authentication (2FA)

For security, the chatbot uses email-based OTP verification before allowing users to access the system.

### Bad Language Filtering

The chatbot detects inappropriate words using a predefined dictionary and prevents such language in conversations.

### Multi User Support

The system architecture supports at least **5 users interacting simultaneously**.

### Fast Response Time

The chatbot is designed to respond to queries within **5 seconds** under normal conditions.

---

## Technologies Used

* Python
* Natural Language Processing (NLP)
* Flask / FastAPI
* PDF Processing Libraries

---

## System Architecture

The system works in the following steps:

1. The user enters a query in the chatbot interface.
2. The request is sent to the backend server.
3. The NLP module processes the question.
4. The chatbot searches the knowledge base for relevant information.
5. The system generates a response and sends it back to the user.

---

## Modules

* Chatbot Query Processing
* Document Processing
* OTP Authentication System
* Bad Language Filtering
* Multi-user Support

---

## Conclusion

The Employee Support Chatbot helps employees quickly access organizational information without contacting HR or IT teams. By combining NLP, document processing, and secure authentication, the system improves efficiency and communication within the organization.
