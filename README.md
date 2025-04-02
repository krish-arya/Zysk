# ZYSK - Personalized Fintech Web Platform

ZYSK is a **fintech web platform** developed for **CodeKshetra**, designed to provide personalized financial insights and investment guidance. The platform uses AI and real-time data integration to assess users' financial mindsets and generate customized investment suggestions.

## Overview

ZYSK simplifies financial decision-making by assessing users' financial mindsets through a detailed 15-question questionnaire. Based on the responses, the platform uses AI to generate personalized reports with investment strategies and mindset analysis. Users also receive real-time stock updates through **WhatsApp** notifications and detailed reports via **email**.

## Key Features

- **Financial Mindset Assessment**:  
  Users answer 15 questions to assess their financial mindset and risk profile.
  
- **AI-Generated Reports**:  
  The platform uses a generative AI model to analyze user responses and generate tailored investment strategies and insights.
  
- **WhatsApp Integration**:  
  Users receive real-time stock market updates and trending stock information directly on WhatsApp.
  
- **Email Notifications**:  
  Users get detailed reports of their financial profiles and suggested strategies via email.
  
- **Real-Time Market Updates**:  
  Access to up-to-date information on trending stocks and other relevant market news.

## Tech Stack

### Frontend

- **HTML5**
- **CSS3**
- **JavaScript**

### Backend

- **Python (Flask)**:  
  For backend processes and AI model integration.

### AI Model

- **Generative AI (Gemini)**:  
  Trained to analyze user responses and generate personalized financial insights.
  
- **Model Tuning**:  
  Using libraries like **Transformers** and **scikit-learn** for fine-tuning the model.

### APIs

- **UltraMsg API**:  
  For sending WhatsApp updates.
  
- **SMTP**:  
  For sending email reports.

## Architecture

ZYSK follows a **microservices** architecture with clear separation of concerns between various modules:

- **Frontend**:  
  Collects user responses and displays results.
  
- **Backend (Flask)**:  
  Manages API requests, handles user data, and triggers AI processes.
  
- **AI Service (Python)**:  
  Processes user data and generates financial insights using Gemini AI.

- **Notification Services**:  
  Sends WhatsApp updates using **UltraMsg** and email reports via **SMTP**.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/zysk.git
   cd zysk
