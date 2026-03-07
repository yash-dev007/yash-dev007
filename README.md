<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Yash%20Patil&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Building%20the%20future%20of%20AI-powered%20travel&descAlignY=58&descSize=18&descColor=a78bfa" width="100%"/>

</div>

---

<div align="center">

### 🛫 Founder & Lead Engineer — [AltairGO Intelligence](https://github.com/yash-dev007/AltairGo-Intelligence)
*Hyper-personalized, AI-generated travel itineraries — powered by Google Gemini*

[![AltairGO](https://img.shields.io/badge/AltairGO_Intelligence-Live_Project-6d28d9?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com/yash-dev007/AltairGo-Intelligence)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yash-patil)
[![Location](https://img.shields.io/badge/📍_Nagpur,_India-FF6B35?style=for-the-badge)](https://github.com/yash-dev007)

</div>

---

## 🚀 What I'm Building

> **AltairGO Intelligence** — An AI travel platform that uses **Google Gemini 2.0** to generate day-by-day, budget-accurate itineraries with real images, drag-and-drop customization, and affiliate monetization.

```
User selects destinations → Gemini generates itinerary (structured JSON)
→ ItineraryValidator auto-corrects budget → 5-source image pipeline
→ Drag-and-drop day customization → Affiliate booking links
```

**What makes it different:**
- 🧠 Structured AI output via Pydantic `responseSchema` — not free-text generation
- ✅ Post-generation `ItineraryValidator` catches budget overruns & generic AI names
- 🖼️ Image pipeline: Cache → Wikipedia → Wikidata → Pexels → SVG fallback
- 🗺️ Real POI discovery via OpenStreetMap Overpass API with relevance scoring
- 💰 Complete affiliate revenue layer (MakeMyTrip, Booking.com)

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-CC2927?style=for-the-badge&logo=databricks&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet_Maps-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![Framer](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📐 Architecture Snapshot

```
React 19 (Vite) ──────► Flask Backend (8 Blueprints)
     │                         │
     │                    ┌────┴─────┐
     │                    ▼          ▼
     │             Gemini 2.0    SQLite/PostgreSQL
     │             (LLM Engine)  (10 SQLAlchemy Models)
     │                    │
     │              ┌─────┴──────┐
     │              ▼            ▼
     │        Image Pipeline   OSM / Overpass
     │        (5-source chain)  (POI Discovery)
     │
     └── JWT Auth · Drag-and-Drop · Leaflet Maps · Affiliate Links
```

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=yash-dev007&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=ffffff" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yash-dev007&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=ffffff" />

</div>

---

## 🌱 Currently

- 🔨 Shipping AltairGO Intelligence to production on **Vercel + Gunicorn**
- 🧪 Building out the AI Destination Architect + admin control plane
- 📖 Deep-diving into **LLM prompt engineering** and structured output schemas
- 🤝 Open to collaborations on AI-powered products

---

<div align="center">

*"Ship fast. Validate with AI. Iterate with data."*

![Visitor Count](https://komarev.com/ghpvc/?username=yash-dev007&color=6d28d9&style=flat-square&label=Profile+Views)

</div>
