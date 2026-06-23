<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a2a4a,100:1e7a5f&height=200&section=header&text=AI-ScoreSight&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=78&desc=EPL%20Match%2C%20Points%20%26%20League%20Winner%20Prediction%20System&descSize=16&descAlignY=58&descColor=7dcfff" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=false&width=720&lines=Predicting+Match+Winners+%7C+Final+Points+%7C+League+Champions;Streamlit+UI+%2B+Flask+API+%2B+XGBoost+Engine;Built+%26+Presented+at+Infosys+Springboard+%7C+Top-Performing+Team" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://sai-karthik-gardas-epl.streamlit.app"><img src="https://img.shields.io/badge/Live%20Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Python-7776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-0d1117?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-7dcfff?style=for-the-badge" />
</p>

<br/>

---

## ⚽ Overview

**AI-ScoreSight** is a full-stack machine learning system that predicts English Premier League outcomes — match winners, final season points, and the eventual league champion — using historical match data and an XGBoost model layer, served through a Flask API and presented through a Streamlit interface.

Built as a 7-person team project during the Infosys Springboard internship (led by [@SaiKarthikGardas](https://github.com/SaiKarthikGardas)), and presented live to a ~7,000-member panel — the team was recognised as **top-performing**.

**🔗 [Live Demo →](https://sai-karthik-gardas-epl.streamlit.app)**

---

## ✨ Features

| Module | What it predicts |
|---|---|
| 🥅 **Match Winner** | Predicts the outcome of a given EPL fixture |
| 📊 **Overall Points** | Projects each team's final season points total |
| 🏆 **League Winner** | Forecasts the eventual league champion |

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="77%">

**Frontend**<br/>
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
<td valign="top" width="77%">

**Backend**<br/>
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6C77?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td valign="top" width="74%">

**ML / Data**<br/>
![XGBoost](https://img.shields.io/badge/XGBoost-0d1117?style=flat-square&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7971E?style=flat-square&logo=scikit-learn&logoColor=white)

</td>
</tr>
</table>

---

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

---

## 🚀 Running Locally

```bash
git clone https://github.com/SaiKarthikGardas/AI-ScoreSight.git
cd AI-ScoreSight
pip install -r requirements.txt
streamlit run Deployment/app.py
```

---

## 👥 Team & Recognition🚀

Led a 7-person team to build and present this project at Infosys Springboard in front of a ~7,000-member panel — recognised as a **top-performing team**.

---

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a2a4a,100:1e7a5f&height=120&section=footer" />
</p>
