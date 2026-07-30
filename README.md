# 🚀 AI Model Compression Platform

<p align="center">
  <img src="https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/FastAPI-0.95.x-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PostgreSQL-14-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Gemini_API-Google-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini API"/>
  <img src="https://img.shields.io/badge/Docker-24.0-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  <b>Making AI Small, Fast, and Accessible</b>
</p>

<p align="center">
  <i>A full-stack web platform for compressing large language models using Pruning, Quantization, and Distillation, powered by Google's Gemini API</i>
</p>

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Compression Techniques](#compression-techniques)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 Overview

**AI Model Compression Platform** is an intelligent web application designed to compress large language models (LLMs) for deployment on resource-constrained edge devices. The platform leverages three primary compression techniques while utilizing Google's Gemini API to provide intelligent insights and recommendations.

### The Problem We Solve ❗
Modern AI models are becoming increasingly massive:
- GPT-3: **175 billion parameters** (~350GB storage)
- Llama 2: **70 billion parameters** (~140GB storage)
- Running these requires **multiple GPUs** and **expensive hardware**

### Our Solution ✨
- Reduce model size by **70-90%**
- Maintain **95%+ accuracy**
- Deploy on **any device** (mobile, IoT, edge)
- **Cost-effective** and **energy-efficient**

---

## ✨ Features

### Core Features
| Feature | Description | Status |
|---------|-------------|--------|
| 🔪 **Pruning** | Remove unnecessary neural connections | ✅ |
| 📊 **Quantization** | Reduce numerical precision | ✅ |
| 🧪 **Distillation** | Transfer knowledge to smaller models | ✅ |
| 🤖 **AI Recommendations** | Smart compression suggestions via Gemini API | ✅ |
| 📤 **Drag & Drop Upload** | Easy model file uploads | ✅ |
| 📈 **Live Progress Tracking** | Real-time compression monitoring | ✅ |
| 📊 **Visual Comparisons** | Before/after performance charts | ✅ |
| 💾 **One-Click Download** | Download compressed models instantly | ✅ |
| 📜 **History Tracking** | All previous compressions stored | ✅ |
| 🔐 **JWT Authentication** | Secure user management | ✅ |

### User Experience
- 🎨 **Modern UI** - Beautiful dark theme with animations
- 📱 **Responsive Design** - Works on all devices
- ⚡ **Real-time Updates** - Live progress and status
- 🎯 **Intuitive Controls** - Easy to use for everyone

---

## 🛠️ Technology Stack

### Backend
```yaml
Framework: FastAPI 0.95+
Language: Python 3.9+
ORM: SQLAlchemy 2.0+
Database: PostgreSQL 14 (Production) / SQLite (Development)
Authentication: JWT (JSON Web Tokens)
API Documentation: Swagger UI / ReDoc
AI Integration: Google Gemini API
Task Queue: Celery (Optional)
Cache: Redis (Optional)

Framework: React 18
Build Tool: Vite
Styling: Tailwind CSS
Animations: Framer Motion
Routing: React Router v6
API Calls: Axios
State Management: React Query
Forms: React Hook Form
Charts: Chart.js