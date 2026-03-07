<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=200&section=header&text=Yash%20Patil&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Founder%20%C2%B7%20Full-Stack%20Engineer%20%C2%B7%20Nagpur%2C%20India&descAlignY=58&descSize=16&descColor=aac8f0" width="100%"/>

<br/>

<div align="center">

### 👋 Hey, I'm Yash

<table>
<tr>
<td width="50%">

**🚀 Building**
> AltairGO Intelligence
> AI-powered travel planning platform

**📍 Location**
> Nagpur, India 🇮🇳

</td>
<td width="50%">

**🛠️ Stack**
> React 19 · Flask · Python
> AltairGO Engine · PostgreSQL · Redis

**💡 Philosophy**
> *"Ship real data. Let AI polish the language."*

</td>
</tr>
</table>

![](https://img.shields.io/badge/Role-Founder%20%26%20Full--Stack%20Engineer-4C8EDC?style=flat-square)
&nbsp;
![](https://img.shields.io/badge/Status-Actively%20Building-22c55e?style=flat-square)
&nbsp;
![](https://img.shields.io/badge/Open%20To-Collabs%20%26%20Internships-f59e0b?style=flat-square)

</div>

<br/>

---

## 🛫 &nbsp;What I'm Building

### **[AltairGO Intelligence](https://github.com/yash-dev007/AltairGo-Intelligence)**
> *AI-powered travel platform — hyper-personalized, budget-accurate, day-by-day itineraries*

**The problem with every AI travel app:** LLMs hallucinate costs, invent attraction names, and produce geographically random routes.

**My solution:** A **deterministic 5-phase engine** where real scraped data is the foundation — Gemini 2.0 only polishes the language on top. It never touches costs, coordinates, or timings.

```
React 19 (Vite) ──────► Flask Backend (8 Blueprints)
     │                         │
     │                    ┌────┴─────┐
     │                    ▼          ▼
     │          AltairGO Engine  SQLite/PostgreSQL
     │          (5-Phase Core)   (11 SQLAlchemy Models)
     │                    │
     │              ┌─────┴──────┐
     │              ▼            ▼
     │        Image Pipeline   OSM / Overpass
     │        (5-source chain)  (POI Discovery)
     │
     └── JWT Auth · Drag-and-Drop · Leaflet Maps · Affiliate Links
```

**The 5-phase engine at a glance:**

| Phase | Module | What it does |
|---|---|---|
| 1 | `filter_engine.py` | Budget · traveler type · seasonal score · popularity floor |
| 2 | `cluster_engine.py` | H3 hex grouping — ~5km radius per day, zero backtracking |
| 3 | `budget_allocator.py` | Real hotel prices from OTA APIs, tier-demotion fallback |
| 4 | `route_optimizer.py` | Haversine ordering, sunrise-first, timestamps per activity |
| 5 | `assembler.py` | Complete structured JSON — LLM only rewrites 4 text fields |

**Result: ±40% budget error (pure LLM) → ±8% (engine-grounded)**

<br/>

---

## 🛠️ &nbsp;Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
&nbsp;
![Vite](https://img.shields.io/badge/Vite_7-646CFF?style=flat-square&logo=vite&logoColor=white)
&nbsp;
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
&nbsp;
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
&nbsp;
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
&nbsp;
![AltairGO Engine](https://img.shields.io/badge/AltairGO_Engine-0a0d14?style=flat-square&logo=rocket&logoColor=4C8EDC)
&nbsp;
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
&nbsp;
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
&nbsp;
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

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

## 🌱 &nbsp;Currently

- 🔨 &nbsp;Migrating AltairGO from pure LLM → **deterministic data engine** (5 phases)
- 🗄️ &nbsp;Building OSM ingestion pipeline covering **80+ Indian cities**
- 📡 &nbsp;Integrating **Booking.com + Skyscanner** affiliate APIs for real-time pricing
- 🧠 &nbsp;Shipping **5-agent QA layer** — structure · pacing · geography · cost · content
- 🚀 &nbsp;Deploying on **Vercel** (frontend) + **Gunicorn** (Flask backend)

<br/>

---

## 📫 &nbsp;Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yash-patil)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yash-dev007)
&nbsp;
[![AltairGO](https://img.shields.io/badge/AltairGO_Intelligence-View_Project-4C8EDC?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com/yash-dev007/AltairGo-Intelligence)

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=yash-dev007&color=4C8EDC&style=flat-square&label=Profile+Views" alt="Profile Views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=120&section=footer" width="100%"/>
