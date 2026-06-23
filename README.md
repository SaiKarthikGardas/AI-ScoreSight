<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0d1117,50:0a2a4a,100:1e3a5f&amp;height=220&amp;section=header&amp;text=AI-ScoreSight&amp;fontSize=46&amp;fontColor=ffffff&amp;animation=fadeIn&amp;fontAlignY=35&amp;desc=EPL%20Match%2C%20Points%20%26%20League%20Winner%20Prediction%20System&amp;descSize=17&amp;descAlignY=52&amp;descColor=7dcfff" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=21&amp;duration=2800&amp;pause=900&amp;color=58A6FF&amp;center=true&amp;vCenter=true&amp;multiline=true&amp;repeat=true&amp;width=760&amp;height=80&amp;lines=Predicting+Match+Winners+%7C+Final+Points+%7C+League+Champions;Streamlit+UI+%2B+Flask+API+%2B+XGBoost+Engine;Built+%26+Presented+at+Infosys+Springboard+%E2%80%94+Top-Performing+Team" alt="Typing SVG" />

<br/><br/>

<a href="https://sai-karthik-gardas-epl.streamlit.app">
  <img src="https://img.shields.io/badge/Live%20Demo-FF4B4B?style=for-the-badge&amp;logo=streamlit&amp;logoColor=white" />
</a>
<a href="https://github.com/SaiKarthikGardas/AI-ScoreSight/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/License-MIT-7dcfff?style=for-the-badge" />
</a>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" />
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&amp;logo=flask&amp;logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-0d1117?style=for-the-badge&amp;logo=xgboost&amp;logoColor=white" />

<br/>

<img src="https://img.shields.io/github/stars/SaiKarthikGardas/AI-ScoreSight?style=flat-square&amp;color=58A6FF&amp;labelColor=0d1117" />
<img src="https://img.shields.io/github/last-commit/SaiKarthikGardas/AI-ScoreSight?style=flat-square&amp;color=7dcfff&amp;labelColor=0d1117" />
<img src="https://img.shields.io/github/repo-size/SaiKarthikGardas/AI-ScoreSight?style=flat-square&amp;color=a8d5ff&amp;labelColor=0d1117" />
<img src="https://img.shields.io/badge/status-active-2ea043?style=flat-square&amp;labelColor=0d1117" />

</div>

<br/>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&amp;color=0:0d1117,100:0d1117&amp;height=2" />
</p>

<br/>

## ⚽ Overview

**AI-ScoreSight** is a full-stack machine learning system built to answer three questions about the English Premier League before the data tells you the answer itself:

> *Who wins the next fixture? Where does each club finish? Who lifts the title?*

It pairs a tuned **XGBoost** model layer with years of historical match data, wraps the inference logic in a **Flask API**, and surfaces everything through a clean **Streamlit** interface — so predictions are one click away, not a notebook scroll away.

Built as a 7-person team project during the **Infosys Springboard** internship (led by [@SaiKarthikGardas](https://github.com/SaiKarthikGardas)), and **presented live to a ~3,000-member panel**, where the team was recognized as a **top-performing team**.

<div align="center">

### 🔗 [**Launch the Live Demo →**](https://sai-karthik-gardas-epl.streamlit.app)

</div>

<br/>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&amp;color=0:0d1117,100:0d1117&amp;height=2" />
</p>

<br/>

## 📊 By the Numbers

<div align="center">

<table>
<tr>
<td align="center" width="25%">

### 🥅
**3**
<br/>
<sub>Prediction Modules</sub>

</td>
<td align="center" width="25%">

### 👥
**7**
<br/>
<sub>Team Members</sub>

</td>
<td align="center" width="25%">

### 🎤
**3,000+**
<br/>
<sub>Panel Audience</sub>

</td>
<td align="center" width="25%">

### 🏆
**Top**
<br/>
<sub>Performing Team</sub>

</td>
</tr>
</table>

</div>

<br/>

## ✨ What It Predicts

<table>
<tr>
<td width="33%" valign="top">

### 🥅 Match Winner
Feed in any two EPL clubs and a matchday context — the model returns a predicted outcome for that fixture based on historical form, head-to-head trends, and engineered match features.

</td>
<td width="33%" valign="top">

### 📊 Final Points
Projects where every club lands at the end of the season, translating mid-season form into a full points table — not just a single match call.

</td>
<td width="33%" valign="top">

### 🏆 League Winner
Rolls the points projections forward into a single forecast: who's most likely to be standing at the top of the table when the season ends.

</td>
</tr>
</table>

<br/>

## 🧠 How It Fits Together

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/SaiKarthikGardas/AI-ScoreSight/main/assets/architecture.svg" alt="Architecture diagram" />
</p>

<details>
<summary><b>Prefer text? Click to expand the flow</b></summary>

<br/>

```
┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
│   Raw EPL Data    │ ──▶ │  Feature Pipeline │ ──▶ │   XGBoost Models  │
│  (data_raw/)      │      │  clean · encode   │      │  3 task-specific   │
└──────────────────┘      └──────────────────┘      └────────┬──────────┘
                                                                │
                          ┌──────────────────┐                 │
                          │     Flask API      │ ◀───────────────┘
                          │  serves inference   │
                          └────────┬─────────┘
                                   │
                          ┌──────────────────┐
                          │  Streamlit UI       │
                          │  user-facing app     │
                          └──────────────────┘
```

</details>

<br/>

## 🛠️ Tech Stack

<table align="center">
<tr>
<td align="center" valign="top" width="33%">

### 🎨 Frontend
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&amp;logo=streamlit&amp;logoColor=white" />

</td>
<td align="center" valign="top" width="33%">

### ⚙️ Backend
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&amp;logo=flask&amp;logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/REST%20API-FF6C37?style=flat-square&amp;logo=fastapi&amp;logoColor=white" />

</td>
<td align="center" valign="top" width="34%">

### 🤖 ML / Data
<img src="https://img.shields.io/badge/XGBoost-0d1117?style=flat-square&amp;logo=xgboost&amp;logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&amp;logo=pandas&amp;logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&amp;logo=scikit-learn&amp;logoColor=white" />

</td>
</tr>
</table>

<br/>

## 📂 Project Structure

```
AI-ScoreSight/
├── data_raw/                   # Raw historical EPL datasets
├── match_winner_model/         # Trained XGBoost model for match outcomes
├── Final_Project_Files/
│   ├── League_winner_Folder/   # League winner prediction logic
│   └── Overall_Points_Folder/  # Final points prediction logic
├── Deployment/
│   └── app.py                  # Streamlit + Flask app entry point
└── LICENSE
```

<br/>

## 🚀 Running Locally

```bash
git clone https://github.com/SaiKarthikGardas/AI-ScoreSight.git
cd AI-ScoreSight
pip install -r requirements.txt
streamlit run Deployment/app.py
```

The app will spin up locally and open in your browser — no extra config needed for a first run.

<br/>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&amp;color=0:0d1117,100:0d1117&amp;height=2" />
</p>

<br/>

## 👥 Team & Recognition

<div align="center">

Led a **7-person team** to build and present this project at **Infosys Springboard**, in front of a **~3,000-member panel** — recognized as a **top-performing team**.

<br/>

<a href="https://github.com/SaiKarthikGardas">
  <img src="https://img.shields.io/badge/Team%20Lead-SaiKarthikGardas-58A6FF?style=for-the-badge&amp;logo=github&amp;logoColor=white" />
</a>

</div>

<br/>

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](https://github.com/SaiKarthikGardas/AI-ScoreSight/blob/main/LICENSE) file for details.

<br/>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0d1117,50:0a2a4a,100:1e3a5f&amp;height=120&amp;section=footer" />
</p>
