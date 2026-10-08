# 🚀 HelpDock

### AI-Powered Customer Support, Anywhere.

**HelpDock** is an AI-powered, customizable customer support chatbot that can be seamlessly embedded into any website.

It helps businesses provide instant AI-powered support to their website visitors without having to build a customer support system from scratch.

---

## ✨ Features

- 🤖 AI-powered customer support
- 🌐 Easily embeddable into any website
- 💬 Interactive conversational chat
- 🔐 Secure authentication with Scalekit
- 🗄️ MongoDB database
- ⚡ Built with Next.js & TypeScript
- 🎨 Customizable chatbot experience
- 📱 Responsive UI
- 🚀 Vercel-ready deployment
- 🔧 Easy website integration

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Next.js** | Full-stack React framework |
| **TypeScript** | Type-safe development |
| **MongoDB** | Database |
| **Scalekit** | Authentication & Authorization |
| **Vercel** | Deployment |
| **AI API** | AI-powered customer support |

---

## 🏗️ Architecture

```text
                    ┌─────────────────────┐
                    │   Customer Website  │
                    │                     │
                    │   Any Website       │
                    └──────────┬──────────┘
                               │
                               │ Embed
                               ▼
                    ┌─────────────────────┐
                    │      HelpDock       │
                    │                     │
                    │   AI Support Bot    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      Next.js        │
                    │                     │
                    │   API & App Logic   │
                    └──────┬────────┬─────┘
                           │        │
                  ┌────────▼───┐ ┌──▼────────┐
                  │  MongoDB   │ │ Scalekit  │
                  │  Database  │ │   Auth    │
                  └────────────┘ └───────────┘