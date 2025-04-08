# 🧠 Empathetic AI-Powered Emergency Call Center Assistant

A modern, intelligent, desktop-based **Emergency Response Management System** designed to empower emergency call centers with **real-time emotional intelligence, AI-based emergency classification, and dispatch coordination**.

> 🏫 Final Year Project by  
> **Vaishakh Suresh**, **Shereen Rafi**, **Vedika Aneesh**, and **Sooraj U S**  
> 🎓 CSE 2021 Batch – Government College of Engineering, Kannur

---

## 🚀 Project Overview

This system revolutionizes the way emergency service operators handle distress calls. It integrates **fine-tuned Large Language Models**, **emotion analysis**, and **real-time location mapping** to ensure faster, smarter, and more humane responses during disasters and emergencies.

---

## 🔥 Key Features

### 📞 Call Management
- 🎙️ Real-time call **transcription** and **emotion analysis**
- 🤖 AI-powered **emergency type classification**
- 🚨 Automated **severity assessment**
- 📍 Live **location tracking and mapping**
- 📝 Detailed call history and summaries

### 🚨 Emergency Dispatch
- Integrated dispatch system for 10+ emergency services:
  - 🚒 Fire Department  
  - 🚑 Medical Emergency  
  - 🚓 Police Department  
- 🧠 Intelligent service recommendation based on incident
- ✅ Dispatch confirmation and real-time status updates

### 📊 Analytics Dashboard
- Visual insights on:
  - 📈 Call volumes
  - ⏱️ Response times
  - 🧭 Geographic distribution
  - 🗃️ Department-wise load
- 📊 Interactive and intuitive data visualizations

### 🎨 Modern UI
- ✨ Sleek, responsive PyQt5 interface
- 🌓 Dark mode support
- 🖱️ User-friendly controls for operators
- 🗺️ Integrated map using **Google Maps API**

---

## 🧠 Technical Stack

| Component         | Technology                                               |
|------------------|-----------------------------------------------------------|
| Frontend          | PyQt5 (GUI Framework), PyQtWebEngine (for embedded maps) |
| Backend           | Python (Core logic and APIs)                             |
| Database          | SQLite                                                   |
| AI Engine         | Fine-tuned Gemini (via Google GenAI API) + Mistral (via Groq) |
| Emotion Analysis  | Hume AI (EVI - Empathic Voice Interface)                 |
| Mapping           | Google Maps API (via QWebEngineView integration)         |
| Networking        | `requests`, `json`, `threading` for API integration and async handling |


---

## 📋 Requirements

Main dependencies:

PyQt5

PyQtWebEngine

Flask

requests

🚀 Getting Started
Clone this repository:

```bash
git clone https://github.com/vaishakh3/finalproject.git
cd finalproject
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python userinterface.py
```

**Acknowledgements**

💡 Inspired by real-world emergency response challenges

🤖 AI components powered by Google Generative AI and Groq LLMs

🗺️ Mapping powered by Google Maps Platform

🧠 Emotional intelligence powered by Hume AI

📸 Sneak Peek
(Insert UI screenshots, architecture diagram, or GIF demo here if available)

📫 Contact
For queries or collaborations, feel free to reach out to any of the contributors or open an issue on this repository.

Built with ❤️ by passionate engineers from GCE Kannur.
