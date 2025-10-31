# agentic-coffee-ordering-app-with-Firebase-and-Google-Cloud.
Brew wants More: An AI-powered coffee ordering app built with Angular, Firebase Genkit, Vertex AI (Gemini Models), Cloud Run, Firestore, and Cloud Storage.

# ☕🤖 Building an Agentic Coffee App with Firebase & Google Cloud

This comprehensive guide walks you through creating an **agentic AI coffee-ordering app** using **Firebase**, **Vertex AI Gemini models**, and **Google Cloud**.  
Learn how to combine conversational intelligence with real-time data to build delightful, production-ready AI experiences.  

[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![Vertex AI](https://img.shields.io/badge/Vertex_AI-34A853?logo=googlecloud&logoColor=white)](https://cloud.google.com/vertex-ai)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)](https://angular.dev/)
[![Genkit](https://img.shields.io/badge/Firebase_Genkit-FF6D00?logo=firebase&logoColor=white)](https://firebase.google.com/genkit)
[![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?logo=googlecloud&logoColor=white)](https://cloud.google.com/run)

> *“Build agents that don’t just respond — they plan, act, and make your coffee just the way you like it.”* ☕💡  

---

![Hero Image](https://github.com/yourusername/brew-maange-more/assets/hero-banner.png)

---

## 🎬 Demo Video
▶️ [Watch on YouTube](#) *(Coming soon)*  

---

## 📋 Table of Contents
- [Overview](#overview)  
- [Technologies You’ll Learn](#technologies-youll-learn)  
- [Architecture](#architecture)  
- [Setup & Installation](#setup--installation)  
- [Firestore Schema](#firestore-schema)  
- [AI Flow](#ai-flow)  
- [Security Best Practices](#security-best-practices)  
- [Future Improvements](#future-improvements)  
- [License & Credits](#license--credits)  

---

## 🌟 Overview
**Brew Maange More** blends your love for coffee and AI by building an intelligent barista that:  
☕ Chats with you naturally  
🧠 Learns your taste over time  
⚡ Handles orders & payments autonomously  
📲 Syncs everything in real time with Firestore  

Inspired by the movie *Dil Maange More* — because, really, **your heart (and coffee) always want more**.

---

## 🧠 Technologies You’ll Learn
| Technology | Icon | Description |
|-------------|:----:|-------------|
| **Angular** | ![Angular](external-assets/angular.svg) | Build a responsive web UI for the coffee barista chat |
| **Firebase Genkit** | ![Genkit](external-assets/firebase-genkit.svg) | Define and orchestrate your agentic logic |
| **Vertex AI (Gemini Models)** | ![Vertex AI](external-assets/vertex-ai.svg) | Power natural-language reasoning and planning |
| **Cloud Run** | ![Cloud Run](external-assets/cloud-run.svg) | Host secure backend microservices and agent tools |
| **Cloud Firestore** | ![Firestore](external-assets/firebase-firestore.svg) | Store user data, preferences, and order history |
| **Cloud Storage for Firebase** | ![Storage](external-assets/firebase-storage.svg) | Manage images, menu assets, and media files |

---

## ⚙️ Architecture
```
[Angular Frontend] → Firebase Auth + Firestore
↓
[Firebase Genkit Flows]
↓
[Vertex AI Gemini Agent]
↓
[Cloud Run / Cloud Functions APIs]
↓
[Firestore & Cloud Storage]
```

---

## 🛠️ Setup & Installation
```bash
# 1 Clone the repo
git clone https://github.com/yourusername/brew-maange-more.git
cd brew-maange-more

# 2 Install dependencies
npm install

# 3 Run Angular locally
ng serve
# App runs at http://localhost:4200
```

**## 🔁 AI Flow**

User: “Surprise me with something chocolatey.”
Vertex AI Agent → suggestDrink()
Agent creates plan: createOrder → confirmPayment → schedulePickup
Cloud Run executes steps securely & updates Firestore
Angular UI updates in real time

## 🔒 Security Best Practices

- Firebase Auth for user login
- Firestore rules to protect user data
- Sensitive keys stored in Secret Manager
- Cloud Functions with IAM-based roles

## 🌈 Future Improvements

Voice ordering capability
Google Pay integration
Mood-based drink recommendations
Loyalty rewards system

## 🧾 License & Credits

MIT License © 2025 Mansi

“Building agentic experiences, one coffee at a time.” ☕🤖


---

Would you like me to add **matching banner graphics** (e.g., hero image + tech stack icons in a single row like Google’s style)? I can generate those next so your README looks visually identical to the reference.
