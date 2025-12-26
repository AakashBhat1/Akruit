# Akruit – IT Consulting & Digital Solutions Website

Akruit is a modern, responsive website built for an IT consulting and digital solutions brand. The project includes both a **pre-launch “Coming Soon” landing page** for lead collection and a **full production-ready website** showcasing services, projects, and contact functionality.

This repository demonstrates frontend engineering, UI design, animation integration, and basic backend-as-a-service usage via Firebase.

---

## 📌 Project Purpose

The goal of this project is to:
- Establish an online presence for an IT consulting brand
- Collect early user interest before launch
- Showcase services, projects, and company information
- Demonstrate modern frontend development practices

---

## 📁 Project Structure

akruit-website/
│
├── index.html # Coming Soon / Pre-launch page (default)
├── k.html # Full production website
├── assets/ # Images and static assets (logo, media)
├── README.md
└── .gitignore

yaml
Copy code

---

## 🚀 Pages Overview

### 1. Coming Soon Page (`index.html`)
Used during the pre-launch phase.

**Features:**
- Full-screen Lottie preloader animation
- Particle-based animated background
- Email subscription forms
- Firebase Firestore integration for storing emails
- Responsive UI built with Tailwind CSS

---

### 2. Main Website (`k.html`)
Production-ready business website.

**Features:**
- Animated 3D fractal particle background using Three.js
- Glassmorphism-based UI design
- Smooth scroll and reveal animations
- Responsive navigation with mobile menu
- Sections: Hero, Services, Projects, About, Contact
- Firebase-powered contact form with anonymous authentication

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS**
- **JavaScript (ES Modules)**
- **Three.js** – 3D background animations
- **Firebase**
  - Firestore (data storage)
  - Authentication (anonymous auth)
- **Lottie** – Preloader animation
- **tsParticles** – Particle background effects

---

## ⚙️ How to Use

### Pre-Launch Mode (Current Setup)
- `index.html` → Coming Soon page
- `k.html` → Main website (not live yet)

### Production Mode
1. Rename `k.html` to `index.html`
2. Optionally rename the coming soon page to `coming-soon.html`
3. Deploy to Netlify, Vercel, or any static hosting provider

---

## 🔒 Notes on Firebase

- Firebase configuration is included for frontend demonstration.
- For real production use, sensitive keys should be handled using environment variables and security rules.
- Firestore is used only for basic form submissions.

---

## 📈 Future Improvements

- SEO optimization and meta tags
- Accessibility (ARIA roles, contrast improvements)
- Image optimization and lazy loading
- Environment-based configuration handling
- Backend validation and spam protection

---

## 📄 License

This project is created for educational and portfolio purposes.  
All rights reserved © 2025 Akruit.
