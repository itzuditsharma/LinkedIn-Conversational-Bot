---
title: linkedin_conversation
app_file: app.py
sdk: gradio
sdk_version: 5.23.1
---

# 🤖 Personal AI Chatbot for Portfolio Site

This project creates a personalized AI chatbot that acts as a virtual assistant on your personal or portfolio website. The chatbot can:

- Answer questions based on your profile and resume (from a PDF)
- Record unknown questions via Pushover notifications
- Sends those message directly on your mobile app
- Collect user contact details for future communication
- Engage in interactive conversations via a Gradio interface

---

## 📂 Project Structure

![image](https://github.com/user-attachments/assets/ea024261-8527-4103-a9dd-3f1b26acd4ba)

---

## 🧠 Features

- ✅ Uses OpenAI GPT model (`gpt-4o-mini`) to handle chat
- 📄 Parses your PDF resume using `PyPDF`
- 📬 Sends unknown questions and user interest to your Pushover account
- 📧 Encourages users to share their email for future connection
- 🧰 Tool calling is integrated for structured user interactions
- 🌐 Deployed with `Gradio` for simple web-based UI

---

## 🛠️ Requirements

Install the necessary dependencies using pip:

```bash
pip install openai gradio pypdf python-dotenv requests


## 🧰 Tool Functions
- record_user_details
Used to collect the user's email, name, and notes if they're interested in being contacted.

- record_unknown_question
Used to log any question the bot could not answer to help improve the knowledge base.
```

## Screenshots
---
![image](https://github.com/user-attachments/assets/6c7ef9d1-37a1-4911-8df8-000a84159c60)
![image](https://github.com/user-attachments/assets/da47d9e6-9faf-420c-96ec-a4007c3f13fb)
![image](https://github.com/user-attachments/assets/17f01a6f-efaf-49af-95c5-f723a7c45dfa)


