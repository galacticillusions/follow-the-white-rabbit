cat > README.md << 'EOF'
# 🐇 Follow the White Rabbit

> Daily journal prompts from Morpheus, delivered straight to your inbox.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 🎯 About

Follow the White Rabbit is an email-based journaling platform that delivers thought-provoking prompts from Morpheus to help users develop deeper self-awareness through daily reflection.

## ✨ Features

- 📧 **Email-First Experience** - Prompts delivered directly to inbox
- ✍️ **Reply-to-Journal** - Users respond by replying to emails
- ☁️ **Cloud Sync** - All responses automatically saved and organized
- 📊 **Monthly Summaries** - Track growth patterns over time
- 🎨 **Matrix Aesthetic** - Y2K-inspired green-on-black design
- 🔐 **Google OAuth** - Secure authentication
- 💰 **Subscription Tiers** - Free trial, Rabbit Hole ($7), and Red Pill ($15)

## 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/follow-the-white-rabbit.git
cd follow-the-white-rabbit

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env.local

# Add your API keys to .env.local

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 📁 Project Structure
```
follow-the-white-rabbit/
├── public/
│   ├── index.html              # Landing page
│   ├── app.html                # Journal app interface
│   └── assets/
├── api/
│   ├── auth.js                 # Authentication logic
│   ├── emails.js               # Email sending/parsing
│   ├── subscriptions.js        # Stripe integration
│   └── webhooks/
│       ├── stripe.js           # Payment webhooks
│       └── inbound.js          # Email reply parsing
├── src/
│   ├── components/
│   ├── lib/
│   └── utils/
├── supabase/
│   └── migrations/             # Database migrations
├── .env.example
├── .gitignore
├── package.json
├── vercel.json
└── README.md
```

## 🔧 Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Matrix aesthetic)
- **Backend**: Vercel Serverless Functions
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Google OAuth
- **Email**: SendGrid
- **Payments**: Stripe
- **Hosting**: Vercel

## 🗄️ Database Schema

See [docs/DATABASE.md](./docs/DATABASE.md) for complete schema.

## 📧 Email Setup

See [docs/EMAIL_SETUP.md](./docs/EMAIL_SETUP.md) for SendGrid configuration.

## 💳 Payment Setup

See [docs/STRIPE_SETUP.md](./docs/STRIPE_SETUP.md) for Stripe integration.

## 🚢 Deployment
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Deploy to production
vercel --prod
```

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 📬 Contact

- Email: morpheus@followthewhiterabbit.com
- BlueSky Social: [@followtheytrabbit.bsky.social](https://bsky.app/profile/followtheytrabbit.bsky.social)
- Website: [https://followthewhiterabbit.blog](https://followthewhiterabbit.blog)

---

*"The answer is out there, Neo, and it's looking for you..."* - Morpheus
EOF
