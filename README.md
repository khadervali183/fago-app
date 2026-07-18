index.html
# FAGO — Farmers Agri Global Organization

**Empowering Farmers Through AI, Innovation & Global Connectivity**

Submitted for **MSME Idea Hackathon 6.0**
Sector: Agriculture, Agro-Processing & Allied Industries

**Author:** S. Khader Vali
**Roll No:** 25F71A0574
**Email:** vkhadar077@gmail.com
**Mobile:** 9121494438

---

## 💡 Problem Statement

Farmers face low income due to middlemen-driven trade, unpredictable weather, poor soil knowledge, late-detected crop/livestock diseases, limited market access, and lack of technology guidance. Farming families' students often struggle to continue their education because of unstable income.

## 🌾 Solution — FAGO

FAGO is an AI-powered mobile platform that unifies every farming service — smart agriculture, direct commerce, education, and expert support — into a single app, built around the farmer's real-world needs (including low literacy and language barriers).

## ✨ Key Features

| Feature | Description |
|---|---|
| 🌱 AI Soil & Disease Detection | Instant soil analysis, weather forecasts, photo-based crop disease detection |
| 🎙️ Bilingual Voice Assistant | Speaks answers aloud in English & Telugu — built for farmers who may not read comfortably |
| 🛒 Crop & Livestock Marketplace | Peer-to-peer trade, cutting out selling-side middlemen |
| 🧺 Kisan Mart | Direct e-commerce for seeds, fertilizer, and equipment — cutting out buying-side middlemen |
| 🎓 Learn & Scholarships | Courses in modern farming + scholarships tied to registered farmer income |
| 🏛️ Schemes, Payments & SOS | Government scheme access, secure digital payments, emergency support |

## 🌟 Newness & Uniqueness

- **Dual marketplace model** — fairness on both the selling and buying side, not just one
- **Bilingual voice-first AI** — accessibility-first design, not an afterthought
- **Diagnostics linked directly to the marketplace** — insight turns into income, not just information
- **Income-linked education** — scholarships tied to a farmer's own platform activity
- **Global-ready architecture** — designed for multi-region, multi-language scaling from day one

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (3D transforms, custom animations), Vanilla JavaScript
- **Voice:** Web Speech API (Speech Recognition + Speech Synthesis)
- **Fonts:** Google Fonts (Fraunces, Space Grotesk, Inter)
- **Prototype scope:** Front-end interactive demo with mock data. A production build would add a backend (Node.js / Python + FastAPI), a database (Firebase / MongoDB), and trained AI models for soil & disease analysis.

## 🚀 Setup Instructions

This is a static front-end prototype — no build step or dependencies required.

**Run locally:**
1. Clone the repository:
   ```bash
   git clone https://github.com/khadervali183/fago-app.git
   cd fago-app
   ```
2. Open `index.html` directly in any modern browser (Chrome recommended for full Voice Assistant support), **or** serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

**Deploy live:**
- Drag-and-drop this folder onto [Netlify Drop](https://app.netlify.com/drop), or
- Import the repo into [Vercel](https://vercel.com/new), or
- Enable **GitHub Pages** in repo Settings → Pages → set source to `main` branch, root folder.

## 📂 Project Structure

```
fago-app/
├── index.html                  → Main interactive app demo
├── docs/
│   ├── presentation.html       → 3D animated pitch deck
│   ├── hackathon-pitch.html    → MSME Hackathon 6.0 submission deck
│   ├── block-diagram.html      → System architecture / flow chart
│   └── block-diagram.pdf       → Block diagram (PDF)
└── README.md
```

## 📱 App Screens

Home Dashboard · AI Tools (Soil Scan, Disease Detection, Chatbot) · Voice Assistant · Marketplace (P2P Trade + Kisan Mart) · Learn (Courses & Scholarships) · Profile (Schemes, Payments, SOS)

## 📄 License

Submitted as an academic hackathon project for MSME Idea Hackathon 6.0.
