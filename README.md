# MindMentor
 AI-Powered Mental Health Companion
# 🧠 MindMentor – AI-Powered Mental Health Companion

> **Status:** 🚧 In Progress  
> **Author:** [Omji Tripathi](https://github.com/Omii28-t)  
> **Domain:** NLP · Mental Health · Full-Stack Development · Sentiment Analysis · Secure Web Apps

---

## 📘 Project Overview

**MindMentor** is a full-stack AI-powered web application designed to provide **emotionally aware mental health support** through natural language conversations. By combining **NLP, sentiment analysis, and CBT principles**, it helps users reflect on their emotions, track their mood over time, and securely journal their thoughts — all in a privacy-first environment.

This project is part of my internship preparation journey and showcases my ability to apply NLP in real-world, impactful software systems.

---

## 🌟 Key Features

- 💬 **Emotion-Aware Chatbot**  
  Responds empathetically based on user’s emotional tone using DistilBERT.

- 📖 **Encrypted Journaling System**  
  Users can write private notes, encrypted and securely stored locally or on Firebase.

- 📊 **Mood Tracking Dashboard**  
  Tracks emotional trends over time with beautiful charts powered by Chart.js.

- 🧘 **CBT-based Suggestions**  
  Offers daily mindfulness prompts and self-reflection tips derived from user moods.

---

## 🛠️ Tech Stack

| Layer          | Tools / Technologies                      |
|----------------|--------------------------------------------|
| **Frontend**   | HTML, CSS, JavaScript (or React for v2)   |
| **Backend**    | Python, Flask                             |
| **NLP Models** | Hugging Face Transformers (DistilBERT)    |
| **Database**   | SQLite (Local) or Firebase (Cloud Sync)   |
| **Visualization** | Chart.js                              |

---

## 🧠 NLP Details

- **Sentiment Analysis**: DistilBERT fine-tuned on emotion datasets
- **Intent Detection**: Classifies user messages into mental state categories
- **Response Engine**: Custom prompts + predefined CBT-style templates

---

## 🔒 Security & Privacy

- Journals are stored securely using AES encryption (future integration)
- Data is never shared or sent without user consent
- Designed with privacy-first principles for mental health use

---

## 📸 Screenshots (Coming Soon)

- Chatbot interface  
- Journal editor  
- Mood analytics dashboard  

---

## 🚀 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/Omii28-t/MindMentor.git
cd MindMentor

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate (on Windows)

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
