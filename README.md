# 🧭 Markov Decision Process (MDP) — Value Iteration & Simulation  
> **Gridworld + Reinforcement Learning + Policy Visualization + Simulation Analytics**

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Value%20Iteration-1E90FF?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-Matplotlib-FF5733?logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Category-Reinforcement%20Learning-8A2BE2" />
  <img src="https://img.shields.io/badge/Simulation-Agent%20Policy-green" />
  <img src="https://img.shields.io/badge/Visualization-Seaborn-yellow" />
</p>

---

## ✨ Overview

This project demonstrates a complete **Markov Decision Process (MDP)** simulation using **Value Iteration** to find optimal policies in a **stochastic Gridworld environment**.  
It provides deep insights into **decision-making under uncertainty** and showcases **beautiful visualizations** for learning and analysis.  

💡 **Goal:** Train an agent to navigate a grid with rewards, penalties, and obstacles while maximizing cumulative reward through Value Iteration.

---

## 🚀 Features

- 🧮 **Full MDP Implementation**
  - States, actions, rewards, transitions, and terminal states  
- ⚙️ **Value Iteration Algorithm**
  - Computes optimal value functions with convergence visualization  
- 🧭 **Policy Extraction**
  - Generates and visualizes the best possible moves (arrows)  
- 🔁 **Agent Simulation**
  - Runs both greedy and ε-greedy trajectories across the grid  
- 📊 **Visualization Suite**
  - Heatmaps, reward plots, policy maps, and convergence curves  
- 📈 **Dynamic Comparative Analysis**
  - Compare learning across different discount factors (γ)  

---

## 🧠 Algorithmic Insight

**Value Iteration** iteratively refines the state-value function until convergence, following the **Bellman Optimality Equation**:

\[
V_{k+1}(s) = \max_a \sum_{s'} P(s'|s, a) [R(s,a,s') + \gamma V_k(s')]
\]

After convergence, the **optimal policy** is derived as:

\[
\pi^*(s) = \arg\max_a \sum_{s'} P(s'|s, a) [R(s,a,s') + \gamma V^*(s')]
\]

---

## 📈 Visualizations

🎨 The notebook generates rich, intuitive plots for understanding agent behavior:

- 🗺️ **Value Function Heatmap** – visualizes learned state values  
- 🧭 **Optimal Policy Map** – arrows show the best move per cell  
- 📉 **Convergence Graph** – shows max Δ per iteration (log scale)  
- 🔥 **State Visit Heatmap** – highlights frequently visited areas  
- 🧩 **Trajectory Path Visualization** – step-by-step navigation  
- 📊 **Reward Progression Plot** – running average of episodic rewards  

---

## 💻 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-FFDD00?logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Data-Numpy%20%7C%20Pandas-blue" />
  <img src="https://img.shields.io/badge/Progress-tqdm-00C853" />
</p>

---

## 🧩 How It Works

1️⃣ Define the **Gridworld MDP** (states, actions, transitions, rewards).  
2️⃣ Apply **Value Iteration** until convergence.  
3️⃣ Extract the **Optimal Policy** from the value function.  
4️⃣ Simulate multiple **agent trajectories** (greedy and ε-greedy).  
5️⃣ Generate **visual reports** and performance insights.  

---

## 🧠 Key Learnings

- **Discount Factor (γ)** controls long-term vs. short-term rewards.  
- **Exploration (ε-greedy)** ensures non-deterministic exploration.  
- **Convergence rate** depends on grid design and γ value.  
- **Visualization** is crucial for interpreting policy efficiency.  

---

## 🧪 Future Enhancements

- 🔄 Implement **Policy Iteration**, **Q-Learning**, and **SARSA**  
- 🧩 Extend environment to **continuous state space**  
- 🧱 Add **OpenAI Gym compatibility**  
- 🎞️ Create **animated trajectories (GIF/MP4)**  
- 🧾 Export **automated analytical reports (PDF)**  

---

## 👨‍💻 Author

**Sam Dennis**  
🎓 MSc AI & ML — Christ University  
💼 Research Focus: Reinforcement Learning & IoT Security  
🌐 [LinkedIn](https://www.linkedin.com/in/samdennis) • [GitHub](https://github.com/your-username)

---

> “Learning is not about immediate reward, but about understanding the long game.” 🧠
