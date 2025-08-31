# Genetic Algorithms & Optimization Problems

This repository contains multiple applications of *Genetic Algorithms (GA)* and optimization techniques implemented in Python.  
Each task demonstrates how evolutionary computation can be applied to real-world and simulated problems, including constraint handling, risk management, and survival strategies.

---

## 🚀 Implemented Tasks

### 1. Parking Allocation Optimization
- *Goal:* Allocate parking spaces in a 10x10 lot for:
  - Electric Vehicles (EVs) → near charging stations  
  - Disabled Drivers → near entrance  
  - Regular Cars → remaining spots  
- *Approach:* Genetic Algorithm with weighted fitness function to minimize walking distances and enforce constraints.  
- *Features:*
  - Chromosome representation for parking assignments  
  - GA operators: selection, crossover, mutation  
  - Visualization of final parking allocation grid  

---

### 2. Trading Strategy Optimization (30 Days)
- *Goal:* Optimize daily trading strategies across 30 days.  
- *Constraints:*  
  - Penalize strategies with drawdowns below -15%  
  - Avoid consecutive repetition of the same strategy  
- *Approach:* Genetic Algorithm to maximize profit while managing risk.  
- *Features:*  
  - Fitness function considering returns & penalties  
  - GA operators: tournament selection, crossover, mutation  
  - Visualization of performance across generations  

---

### 3. Escape Strategy Simulation (Sharjeel vs Mafia)
- *Goal:* Help Sharjeel escape from the mafia on a grid.  
- *Setup:*  
  - Mafia members randomly placed on ~30% of the grid  
  - Sharjeel must navigate safely to the exit  
- *Approach:* GA-driven movement strategy to avoid mafia and reach safety.  
- *Features:*  
  - Grid-based environment simulation  
  - Fitness based on survival & pathfinding  
  - Visualization of escape attempts  

---

## 🛠 Tech Stack
- *Language:* Python  
- *Libraries:* numpy, matplotlib, random  

---

## 📂 Repository Structure
📦 genetic-algorithms-optimization
┣ 📜 Parking_Optimization.ipynb
┣ 📜 Trading_Strategy.ipynb
┣ 📜 Mafia_Escape.ipynb
┣ 📜 README.md

## 📊 Results
- Parking problem → optimized allocation that respects EV/disabled needs  
- Trading problem → balanced strategy with reduced risk of drawdowns  
- Escape problem → evolved strategies that improve survival chances
