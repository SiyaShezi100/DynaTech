# DynaTech AI Chatbot

DynaTech AI Chatbot is an educational AI assistant built using Botpress Cloud.  
The chatbot helps users learn Artificial Intelligence concepts through simple lessons and interactive quizzes.

## Features

- Learn AI topics in simple language
- Interactive multiple-choice quizzes
- Beginner-friendly educational experience
- Quick-reply buttons for easy navigation
- Accessible through a public webchat link
- Covers multiple AI topics including:
  - Machine Learning
  - Deep Learning
  - Natural Language Processing (NLP)
  - Computer Vision
  - Neural Networks
  - AI Ethics
  - Prompt Engineering
  - Generative AI

## Technologies Used

- Botpress Cloud
- Botpress Webchat v3.6
- HTML
- CSS
- JavaScript

## Live Chatbot

Access the chatbot here:

https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/04/23/11/20260423111610-ZUSWV6RD.json

## How the Chatbot Works

1. User opens the chatbot
2. User selects or prompts an AI topic
3. Chatbot provides a short educational lesson
4. User completes a quiz based on the topic
5. Chatbot displays a completion message

## Example Topics

### Machine Learning
- What is Machine Learning?
- Real-world applications
- Types of Machine Learning

### Deep Learning
- Neural networks
- AI image recognition
- Deep learning applications

### NLP
- Language translation
- Chatbots
- Text understanding

## Installation (Optional Website Embed)

Copy and paste the Botpress embed code into your HTML file.

```html
<script src="https://cdn.botpress.cloud/webchat/v3.6/inject.js"></script>
<script>
  window.botpress.init({
    "botId": "YOUR_BOT_ID",
    "configuration": {
      "website": {},
      "email": {},
      "phone": {},
      "termsOfService": {},
      "privacyPolicy": {},
      "color": "#2563eb",
      "variant": "solid",
      "themeMode": "light"
    }
  });
</script>

Project Team

Dynamic Tech Squad

Buthelezi Sinakhokonke
Ntuli Ncamisile
Nota Atsho
Shezi Siyabonga
Zitha Lerato
Educational Purpose

This chatbot was developed as an academic project to demonstrate:

Conversational AI
Educational technology
Quiz-based learning systems
Botpress chatbot development
Future Improvements
Score tracking
User accounts
PDF note downloads
Voice interaction
Advanced AI explanations
Progress analytics
License

This project is for educational purposes only.

---

# Simple Website Embed Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DynaTech AI Chatbot</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
    }

    h1 {
      color: #2563eb;
      margin-bottom: 10px;
    }

    p {
      color: #444;
      margin-bottom: 20px;
      text-align: center;
      width: 80%;
      max-width: 600px;
    }

    .chat-button {
      padding: 12px 24px;
      background: #2563eb;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }

    .chat-button:hover {
      background: #1d4ed8;
    }
  </style>
</head>
<body>

  <h1>DynaTech AI Chatbot</h1>

  <p>
    Learn Artificial Intelligence concepts through interactive lessons and quizzes.
  </p>

  <button class="chat-button" onclick="openChat()">
    Open AI Chatbot
  </button>

  <script>
    function openChat() {
      window.open(
        "https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/04/23/11/20260423111610-ZUSWV6RD.json",
        "_blank"
      );
    }
  </script>

</body>
</html>
