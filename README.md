<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,0,30&height=220&section=header&text=Yash%20Patil&fontSize=70&fontColor=ffffff&fontAlignY=40&desc=Building%20things%20that%20shouldn%27t%20exist%20yet%20%C2%B7%20Nashik%2C%20India&descAlignY=62&descSize=15&descColor=aac8f0" width="100%"/>

<div align="center">

![MasterHead](https://user-images.githubusercontent.com/10498744/210012254-234538ff-d198-48aa-8964-37e6fd45d227.gif)

![Role](https://img.shields.io/badge/Role-Student%20%26%20Builder-4C8EDC?style=flat-square)
&nbsp;
![Status](https://img.shields.io/badge/Status-Actively%20Building-22c55e?style=flat-square)
&nbsp;
![Open To](https://img.shields.io/badge/Open%20To-Collabs%20%26%20Internships-f59e0b?style=flat-square)
&nbsp;
![Location](https://img.shields.io/badge/📍-Nashik%2C%20India-ef4444?style=flat-square)

</div>

<br/>



## 🚀 &nbsp;What I'm Building

### **[AltairGO Intelligence](https://github.com/yash-dev007/AltairGo-Intelligence)** &nbsp;·&nbsp; AI Travel Planning Platform

> Most AI travel apps hallucinate costs, invent attraction names, and produce geographically random routes. I'm fixing that.

AltairGO uses **Google Gemini 2.0** to generate hyper-personalized, budget-accurate, day-by-day itineraries — grounded in real destination data, not LLM guesswork. It's a full-stack platform: React 19 frontend, Flask backend with 8 API blueprints, SQLAlchemy ORM, JWT auth, affiliate monetization, and a custom 5-source image pipeline.

| The problem | My fix |
|---|---|
| LLMs hallucinate costs | `ItineraryValidator` auto-scales overbudget plans within ±5% tolerance |
| Generic attraction names | Regex-based quality checks catch lazy AI output before it reaches the user |
| No real images | 5-source chain: Cache → Wikipedia → Wikidata → Pexels → SVG fallback |
| Black-box AI output | Gemini forced into structured JSON via Pydantic `responseSchema` |

`React 19` `Flask` `Gemini 2.0` `SQLAlchemy` `Flask-JWT` `Leaflet` `Framer Motion` `Pydantic`

<br/>

---

### **[KIBO](https://github.com/yash-dev007/KIBO)** &nbsp;·&nbsp; Desktop AI Companion

> Not a chatbot widget. A character that lives on your screen, listens for your voice, and actually remembers you.

KIBO is a frameless, transparent animated desktop companion powered by voice and long-term memory. It runs Groq cloud LLM at ~6,000 tokens/second with automatic Ollama fallback — no API key required. Vector RAG via `sqlite-vec` means it finds *"user likes espresso"* when you ask *"what's my favourite drink?"* without keyword overlap.

| | KIBO | Typical AI widget |
|---|---|---|
| **Voice round-trip** | ~1.2 s | 3–8 s |
| **Memory** | Vector RAG (semantic kNN) | Session-only |
| **Animation** | VP9 alpha WebM via WMF — zero CPU | PNG sequences or canvas |
| **Privacy** | Cloud-fast or fully local, your choice | Cloud-dependent |
| **Tests** | 254 passing | — |

`Python 3.11` `Electron` `React` `TypeScript` `Groq` `Ollama` `FastAPI` `sqlite-vec` `Piper TTS` `faster-whisper`

<br/>

---

## 📚 &nbsp;Currently Learning

```python
my_journey = {
    "foundation":   ["Python ✅", "OOP ✅"],
    "data_science": ["NumPy ✅", "Pandas ✅", "Matplotlib ✅", "Sklearn  ← here"],
    "frontend":     ["React 19 ✅", "CSS Modules ✅", "Vite ✅"],
    "building":     ["AltairGO Intelligence", "KIBO  ← shipping in parallel"],
}

```

<br/>

---

## 🛠️ &nbsp;Tech Stack

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
&nbsp;
![Vite](https://img.shields.io/badge/Vite_7-646CFF?style=flat-square&logo=vite&logoColor=white)
&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
&nbsp;
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
&nbsp;
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
&nbsp;
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)

**Backend & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
&nbsp;
![Gemini](https://img.shields.io/badge/Google_Gemini_2.0-4285F4?style=flat-square&logo=google&logoColor=white)
&nbsp;
![Groq](https://img.shields.io/badge/Groq-F54F29?style=flat-square&logoColor=white)
&nbsp;
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
&nbsp;
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data & DevOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
&nbsp;
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
&nbsp;
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
&nbsp;
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
&nbsp;
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
&nbsp;
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Learning Next**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
&nbsp;
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

</div>

<br/>

---

## 📊 &nbsp;GitHub Stats

<div align="center">

<a href="https://github.com/yash-dev007">
  <img width="49%" src="https://streak-stats.demolab.com?user=yash-dev007&theme=dark&hide_border=true&background=0D1117&ring=4C8EDC&fire=4C8EDC&currStreakLabel=4C8EDC&sideLabels=aac8f0&dates=6B8DB5&sideNums=FFFFFF&currStreakNum=FFFFFF" alt="GitHub Streak"/>
</a>
<a href="https://github.com/yash-dev007">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yash-dev007&layout=compact&hide_border=true&bg_color=0D1117&title_color=4C8EDC&text_color=aac8f0&langs_count=8" alt="Top Languages"/>
</a>

</div>

<div align="center">

<a href="https://github.com/yash-dev007">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=yash-dev007&theme=react-dark&hide_border=true&bg_color=0D1117&color=4C8EDC&line=4C8EDC&point=ffffff&area=true&area_color=4C8EDC" alt="Contribution Graph"/>
</a>

</div>

<br/>

---

## 🔥 &nbsp;What's Next

**AltairGO** — OSM data ingestion for 80+ Indian cities · real-time pricing via Booking.com + Skyscanner · 5-agent QA layer · public launch on Vercel

**KIBO** — Full data export lifecycle · Windows installer + auto-update · macOS support · custom character SDK · `pip install kibo`

<br/>

---

## 📫 &nbsp;Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yash-patil)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yash-dev007)
&nbsp;
[![AltairGO](https://img.shields.io/badge/AltairGO_Intelligence-View_Project-4C8EDC?style=for-the-badge&logoColor=white)](https://github.com/yash-dev007/AltairGo-Intelligence)
&nbsp;
[![KIBO](https://img.shields.io/badge/KIBO-View_Project-22c55e?style=for-the-badge&logoColor=white)](https://github.com/yash-dev007/KIBO)

<br/>

<img src="https://komarev.com/ghpvc/?username=yash-dev007&color=4C8EDC&style=flat-square&label=Profile+Views" alt="Profile Views"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,0,30&height=120&section=footer" width="100%"/>
