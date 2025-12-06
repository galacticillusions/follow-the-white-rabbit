# 🐇 Follow the White Rabbit

> Daily journal prompts from Morpheus, delivered straight to your inbox.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 🎯 Project Overview

Follow the White Rabbit is an email-based journaling platform that delivers thought-provoking prompts from Morpheus to help users develop deeper self-awareness through daily reflection.

**Key Features:**
- 📧 Email-first journaling experience
- ✍️ Reply-to-email functionality  
- ☁️ Cloud sync with Supabase
- 🔐 Google OAuth authentication
- 💰 Stripe subscription tiers
- 🎨 Matrix-inspired Y2K aesthetic

## 🚀 Quick Start
```bash
git clone https://github.com/yourusername/follow-the-white-rabbit.git
cd follow-the-white-rabbit
npm install
cp .env.example .env.local
npm run dev
```

## 📁 Project Structure
```
follow-the-white-rabbit/
├── public/
│   ├── index.html          # Landing page (use the artifact I created)
│   └── app.html            # Journal app interface
├── api/
│   ├── auth.js             # Google OAuth
│   ├── emails.js           # SendGrid integration
│   └── webhooks/
│       ├── stripe.js       # Payment webhooks
│       └── inbound.js      # Email reply parsing
├── .env.example
├── package.json
└── README.md
```

[See full documentation in repo]
