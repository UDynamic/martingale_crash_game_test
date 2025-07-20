# 🎲 martingale_crash_game_test

> ⚠️ **WARNING: This simulation demonstrates a betting strategy with a negative expected return.**  
> The Martingale system is mathematically guaranteed to fail over the long term in games like Crash. This project exists **strictly for educational and analytical purposes**. Do not use this system in real gambling environments expecting profit — unless you're the casino.

---

## ❓ What Is This?

This repo simulates the classic **Martingale betting strategy** within a **rising index "Crash" game** environment.

**Crash games** (e.g. Aviator, Bustabit) tempt players with the illusion of beatable odds. Martingale tempts them with the illusion of recovery. This repo throws both illusions into a Python blender and lets you watch them explode.

---

## 🎯 Why Build This?

Despite its eventual failure, the Martingale system is:
- A **useful tool** for understanding exponential betting logic
- A **fantastic cautionary tale** for bankroll management
- A way to **visualize risk of ruin** in games with continuous multipliers
- An entry point to studying **negative expected value systems**

This project explores what happens when you apply Martingale logic to a game that:
- Isn’t binary (you choose your own cashout multiplier)
- Crashes unpredictably
- Still gives off "I can beat this" vibes

---

## 📦 Features

- 📊 Full Martingale simulator for rising index games
- 🔧 Configurable parameters:
  - Starting bankroll
  - Base bet
  - Target cashout multiplier (e.g. 2x, 1.5x, etc.)
  - Max consecutive loss tolerance (or max bet cap)
- 📈 Outputs:
  - Bankroll over time
  - Drawdowns and risk curves
  - Loss streak tracking
- 🧪 Batch simulations for Monte Carlo-style testing
