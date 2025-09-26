<div align="center">

# 🎲 Martingale Crash Game Simulator  
</div>
⚠️ **DISCLAIMER**  
This project is for **educational and analytical purposes only**.  
It demonstrates the mathematics of exponential betting systems and risk of ruin in rising-index “Crash” games.  
It is **not** intended for real gambling or profit-making use.  

---



<div align="center">

## ❓ What Is This?  

</div>

This repository implements a **Martingale strategy simulator** for **Crash-style games**.  
Instead of pretending Martingale “beats the house,” this app helps you **see the numbers**: how bankrolls grow, collapse, and recover under different strategy configurations.  

---

<div align="center">

## 🎯 Purpose  

</div>

This project is both:  

- A **software engineering exercise** → full-stack app built with **Next.js** + **Django**  
- A **finance/risk analysis tool** → models position sizing, bankroll growth, and exponential recovery  

It bridges **interactive front-end dashboards** with **mathematical back-end models**, letting you experiment with Martingale logic step by step.  

---

<div align="center">

## 📦 Features  

</div>

- **Interactive Strategy Runner**  
  - Enter starting balance  
  - Set base bet, target multiplier (e.g. 1.5x), and max tolerated loss streak  
  - App calculates the *required bet* for each round  
  - Register **Win** ✅ or **Failure** ❌ and watch bankroll + streak update  

- **Core Risk Modeling**  
  - Tracks bankroll changes after each round  
  - Shows bet escalation  
  - Displays risk of ruin when streak limit is hit  

- **Planned Analytics**  
  - Bankroll history charts  
  - Loss streak statistics  
  - Comparative strategies (Reverse Martingale, Flat Betting, Kelly sizing)  

---

<div align="center">

## 🛠 Tech Stack  

</div>

- **Frontend:** Next.js (React, Tailwind/shadcn for UI)  
- **Backend:** Django REST Framework (Python for Martingale logic)  
- **Visualization (roadmap):** Matplotlib / Recharts  
- **Deployment:** Dockerized for reproducibility  
