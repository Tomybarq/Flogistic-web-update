<div align="center">

<img src="https://qtrypzzcjebvfcihiynt.supabase.co/storage/v1/object/public/base44-prod/public/698693974567338469dd516f/538a6a95a_Logo.png" alt="Flogistic Solutions Co" width="120"/>

# Flogistic Solutions Co — Enterprise AI Website

###Transforming Businesses with Artificial Intelligence

[![React](https://img.shields.io/badge/React-18.2-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-6.1-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)
[![Base44](https://img.shields.io/badge/Base44-SDK-0066FF?logo=data:image/svg+xml;base64,&logoColor=white)](https://base44.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![License](https://img.shields.io/badge/License-Proprietary-red)]()

</div>

---

## 📋 نظرة عامة | Overview

**Flogistic Solutions Co** is a premium enterprise AI company website built with React, Vite, and the Base44 ecosystem. The platform showcases cutting-edge AI-powered services including Digital Marketing, Predictive Analytics, and Process Automation. The website features a bilingual interface (Arabic/English), an integrated AI chatbot, animated sections with Framer Motion, and a responsive dark-themed design.

شركة **Flogistic Solutions Co** — موقع مؤسسي احترافي يقدم حلول الذكاء الاصطناعي للشركات. يتميز الموقع بواجهة ثنائية اللغة (عربي/إنجليزي)، شات بوت ذكي مدمج، تصميم متجاوب بألوان داكنة، وحركات أنيقة باستخدام Framer Motion.

---

## ✨ المميزات | Features

| Feature | Description |
|---------|-------------|
| 🌐 **Bilingual Support** | Full Arabic (RTL) & English (LTR) interface with instant language toggle |
| 🤖 **AI Chatbot** | Integrated smart assistant powered by Base44 LLM for customer engagement |
| 🎨 **Modern Design** | Dark-themed UI with gradient orbs, glass-morphism, and smooth animations |
| 📊 **Animated Stats** | Live counters for enterprise metrics (500+ clients, 98% satisfaction, 2.4x ROI) |
| 💬 **Testimonials Carousel** | Auto-rotating client testimonials with navigation controls |
| 📧 **Contact Form** | Direct email integration to `digitalflogistic@gmail.com` via Base44 |
| 📱 **Fully Responsive** | Optimized for mobile, tablet, and desktop with adaptive layouts |
| ⚡ **Fast Performance** | Vite-powered build with code splitting and lazy loading |

---

## 🛠️ التقنيات المستخدمة | Tech Stack

### Core Framework
- **React 18** — UI library with hooks and context
- **Vite 6** — Next-generation build tool with HMR
- **React Router 6** — Client-side routing

### Styling & UI
- **Tailwind CSS 3.4** — Utility-first CSS framework
- **shadcn/ui** — Component library (40+ pre-built components)
- **Radix UI** — Headless accessible primitives
- **Framer Motion** — Production-grade animations
- **Lucide React** — Modern icon library

### Backend & Integrations
- **Base44 SDK** — Backend-as-a-Service (auth, email, LLM, entities)
- **Stripe** — Payment integration (ready)
- **TanStack Query** — Server state management
- **React Hook Form + Zod** — Form validation

### Mapping & Charts
- **React Leaflet** — Interactive maps
- **Recharts** — Data visualization
- **jsPDF + html2canvas** — PDF generation

---

## 📁 هيكل المشروع | Project Structure

```
Flogistic-web-update/
├── src/
│   ├── api/
│   │   └── base44Client.js          # Base44 SDK client
│   ├── components/
│   │   ├── landing/
│   │   │   ├── Chatbot.jsx          # AI-powered chat widget
│   │   │   ├── ContactSection.jsx   # Contact form + info
│   │   │   ├── Footer.jsx           # Footer with social links
│   │   │   ├── HeroSection.jsx      # Hero with animated stats
│   │   │   ├── Navbar.jsx           # Sticky nav with language toggle
│   │   │   ├── ServicesSection.jsx  # 3 service cards
│   │   │   ├── TestimonialsSection.jsx  # Carousel
│   │   │   └── translations.jsx     # AR/EN translations
│   │   └── ui/                      # 40+ shadcn/ui components
│   ├── hooks/
│   │   └── use-mobile.jsx
│   ├── lib/
│   │   ├── AuthContext.jsx          # Authentication context
│   │   ├── NavigationTracker.jsx
│   │   ├── PageNotFound.jsx
│   │   ├── app-params.js            # Base44 app configuration
│   │   └── query-client.js
│   ├── pages/
│   │   └── Home.jsx                 # Landing page (assembles all sections)
│   ├── App.jsx                      # Root app with routing
│   ├── main.jsx                     # Entry point
│   └── index.css                    # Global styles + Tailwind
├── public/                          # Static assets
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

---

## 🚀 التثبيت والتشغيل | Getting Started

### Prerequisites
- **Node.js** 18+
- **npm** or **yarn**
- A Base44 account with an active app

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Tomybarq/Flogistic-web-update.git
cd Flogistic-web-update

# 2. Install dependencies
npm install

# 3. Create environment file
cp .env.example .env.local  # or create manually
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_BASE44_APP_ID=your_app_id
VITE_BASE44_APP_BASE_URL=your_backend_url
```

### Development

```bash
# Start the development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint the code
npm run lint

# Type check
npm run typecheck
```

The app will be available at `http://localhost:5173`

---

## 🎯 الخدمات | Services

The website showcases three core AI-powered enterprise services:

### 1. Digital Marketing Services | خدمات التسويق الرقمي
AI-driven marketing automation that optimizes campaigns, personalizes customer experiences, and maximizes ROI through intelligent data analysis.

### 2. Predictive Analytics | التحليلات التنبؤية
Leverage machine learning to forecast trends, customer behavior, and market opportunities with unparalleled accuracy.

### 3. Process Automation | أتمتة العمليات
Streamline operations with intelligent automation solutions that reduce costs and increase productivity across your organization.

---

## 🤖 الشات بوت الذكي | AI Chatbot

The website includes a built-in AI chatbot (`Chatbot.jsx`) that:
- Greets visitors in their selected language (Arabic/English)
- Answers questions about Flogistic's services
- Encourages visitors to book consultations
- Powered by Base44's LLM integration
- Features a modern floating widget with smooth animations

**Support contact:** `digitalflogistic@gmail.com` | WhatsApp: `+967 738 866 236`

---

## 🌐 الدعم الثنائي اللغة | Bilingual Support

The website supports Arabic (RTL) and English (LTR) with:
- Instant language toggle via the Globe icon in the navbar
- Full RTL/LTR layout adaptation
- Translated content in `translations.jsx`
- Direction-aware animations and spacing

---

## 📞 معلومات التواصل | Contact

| Channel | Details |
|---------|---------|
| 📧 Email | `digitalflogistic@gmail.com` |
| 📱 WhatsApp | `+967 738 866 236` |
| 📍 Location | Hadramaut, Yemen |
| 🔗 LinkedIn | [Flogistic AI](https://www.linkedin.com/company/flogistic-ai/) |
| 📘 Facebook | [Flogistic](https://www.facebook.com/share/1CxWjm1XcN/) |
| 📸 Instagram | [@flogistic_ai](https://www.instagram.com/flogistic_ai) |
| 📝 Blog | [digital-flogistic.blogspot.com](https://digital-flogistic.blogspot.com) |

---

## 📦 النشر | Deployment

This project is deployed via the **Base44 Platform**:

1. Push your changes to the `main` branch
2. Changes are automatically reflected in the Base44 Builder
3. Click **Publish** on [Base44.com](https://base44.com) to deploy

**Documentation:** [Base44 GitHub Integration](https://docs.base44.com/Integrations/Using-GitHub)
**Support:** [Base44 Support](https://app.base44.com/support)

---

## 📄 الترخيص | License

© 2026 **Flogistic Solutions Co**. All rights reserved.

This is proprietary software. Unauthorized copying, modification, or distribution is strictly prohibited.

---

<div align="center">

**Built with ❤️ by [Flogistic Solutions Co](https://github.com/Tomybarq)**

*Empowering enterprises with cutting-edge AI solutions for sustainable growth and innovation.*

</div>
