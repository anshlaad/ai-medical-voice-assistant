
# 🩺 AI Medical Voice Agent

A HIPAA-ready **AI-powered medical voice assistant** designed to help clinics and healthcare providers automate front-desk operations through real-time voice conversations.

This project focuses on **standardizing healthcare data**, reducing administrative workload, and improving patient experience using modern AI and cloud technologies.

---

## 🚀 Features

- 🎙️ **Real-time Voice Conversations** with patients
- 📝 **Live Speech-to-Text (STT)** using AssemblyAI
- 🗣️ **AI-powered Voice Responses (TTS)** via Vapi
- 🔐 **Secure Authentication & RBAC** using Clerk
- 🧾 **Session & Conversation Logging** with NeonDB
- 💳 **Subscription-based SaaS Billing** with Stripe
- 📊 **Role-based Dashboards** for clinics and admins
- 🏥 **HIPAA-conscious Architecture** for healthcare data handling

---

## 🔁 End-to-End Flow

User speaks
→ WebRTC audio stream (Vapi)
→ AssemblyAI (Speech-to-Text)
→ AI Agent (LLM logic)
→ Vapi (Text-to-Speech)
→ User hears response
→ Transcript securely stored in NeonDB
→ Billing & RBAC enforced via Stripe + Clerk


---

## 🧠 Tech Stack

**Frontend**
- Next.js
- TypeScript
- Tailwind CSS

**Backend / Services**
- AssemblyAI (Real-time STT)
- Vapi (Voice + WebRTC)
- NeonDB (PostgreSQL)
- Clerk (Auth & RBAC)
- Stripe (Subscriptions & Billing)

**Architecture**
- SaaS-based
- Real-time streaming
- Secure session-based design

---

## 🛠️ Key Learnings

- Handling **real-time audio streams & latency**
- Designing **HIPAA-aware systems**
- Managing **stateful voice sessions**
- Building scalable **subscription-based SaaS**
- Secure logging and access control

---

## 📌 Use Cases

- Clinic front-desk automation
- Patient intake & triage
- Medical conversation summaries
- Subscription-based healthcare tools

---

## 📄 Status

🚧 Actively evolving — focused on improving conversation accuracy, summaries, and compliance workflows.

---

## 👤 Author

**Ansh Laad**  
B.Tech CSE, Medicaps University  
Full-Stack Developer

