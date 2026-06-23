# ⚽ AI-ScoreSight

**EPL Match, Points & League Winner Prediction System**

A full-stack machine learning system that predicts English Premier League outcomes — match winners, final season points, and the eventual league champion — using historical match data and an XGBoost model, served through a Flask API and presented through a Streamlit interface.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://sai-karthik-gardas-epl.streamlit.app)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0d1117?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-7dcfff?style=for-the-badge)

---

## Overview

Built as a 7-person team project during the **Infosys Springboard internship** (led by [@SaiKarthikGardas](https://github.com/SaiKarthikGardas)), and presented live to a ~3,000-member panel — the team was recognised as **top-performing**.

**[Live Demo →](https://sai-karthik-gardas-epl.streamlit.app)**

---

## Features

| Module | What it predicts |
|---|---|
| 🥅 **Match Winner** | Predicts the outcome of a given EPL fixture |
| 📊 **Overall Points** | Projects each team's final season points total |
| 🏆 **League Winner** | Forecasts the eventual league champion |

---

## Tech Stack

**Frontend** — Streamlit

**Backend** — Flask, REST API

**ML / Data** — XGBoost, Pandas, scikit-learn

---

## Project Structure
AI-ScoreSight/

├── data_raw/                   # Raw historical EPL datasets

├── match_winner_model/         # Trained XGBoost model for match outcomes

├── Final_Project_Files/

│   ├── League_winner_Folder/   # League winner prediction logic

│   └── Overall_Points_Folder/  # Final points prediction logic

├── Deployment/

│   └── app.py                  # Streamlit + Flask app entry point

└── LICENSE

## Team & Recognition

Led a 7-person team to build and present this project at Infosys Springboard in front of a ~3,000-member panel — recognised as a **top-performing team**.

---

## License

This project is licensed under the [MIT License](LICENSE).
This drops every animated/external SVG that was causing the parsing error, keeps the shields.io badges (those render as static images and won't break your page), and tightens the structure with consistent heading levels and spacing throughout. Want me to also save this as an actual README.md file for you to download?
