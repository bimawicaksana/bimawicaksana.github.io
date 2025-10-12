## AI-Driven Optimization Models for Voyage Planning

**Author:** Bima Surya Wicaksana  
**Affiliation:** Summer School and Conference in HI! Paris (HEC Paris and Ecole Polythechnique Paris) as Master student of KEDGE Business School  
---
<p style="text-align:center; font-size:13px; color:gray;">
Poster presented at HI! Paris Summer School and Conference, 2025
</p>
---

### Project Overview

Maritime transport moves over 80% of global trade and faces rising **economic and environmental pressures**.  
Fuel can account for up to **60% of voyage expenses**, while IMO 2050 targets demand at least **50% GHG reduction**.  

This project explores how **AI-driven optimization models** can enhance ship voyage planning by balancing:
- Voyage **cost efficiency**
- **Safety** and operational feasibility
- **Emission reduction** targets  

The objective is to find optimal voyage performance across **economic**, **operational**, and **environmental** criteria.

---

### Motivation

Traditional economic optimization using linear regression fails to capture **nonlinear interactions** among:
- Operational constraints (speed, draft, schedule)  
- Weather and sea conditions  
- Port congestion and capacity  
- Bunker fuel price volatility  

AI and machine learning models enable **multi-objective optimization** under uncertainty — producing adaptive, data-driven strategies for sustainable voyage planning.
<img src="/research/ai-voyage-planner-1.png?raw=true" alt="AI Voyage Planning fig 1" class="poster"/>

---

### Methodology & Data

**Dataset:**  
Synthetic dataset of **336 voyage legs**, covering:
- Operational and environmental conditions  
- Top-10 major port capacity and performance metrics  
- Fuel consumption and voyage time indicators  
<img src="/research/ai-voyage-planner-2.png?raw=true" alt="AI Voyage Planning fig 2" class="poster"/>


### Result
<img src="/research/ai-voyage-planner-3.png?raw=true" alt="AI Voyage Planning fig 3" class="poster"/>
**XGBoost** achieved the best trade-off between accuracy and training speed based on R2 value.

---

### Key Insights
<img src="/research/ai-voyage-planner-4.png?raw=true" alt="AI Voyage Planning fig 4" class="poster"/>
- **Distance**, **cargo weight**, and **planned speed** are the most influential determinants of cost and emissions.  
- **Tree-based models** outperform linear baselines by capturing complex relationships between voyage factors.  
- Model rankings remained stable across runs, confirming robust, generalizable performance.  

---

### Impact & Future Directions

- **Dynamic Routing Optimization:**  
  Compute energy-efficient routes in real time, adapting to weather and port congestion.  
- **Reinforcement Learning & Digital Twins:**  
  Enable autonomous adjustment of vessel speed and scheduling during operations.  
- **Economic Relevance:**  
  Integrating intelligent routing supports **supply chain resilience**, reduces costs, and accelerates decarbonization.

---

### Tools & Code Repository

Python · pandas · scikit-learn · XGBoost · Keras/TensorFlow · Tableau  
[🔗 View Code Repository](https://github.com/bimawicaksana/ship-operational-ai)
---

### References

1. Psaraftis, H. N. (2019). *Decarbonization of Maritime Transport*. Springer.  
2. Stopford, M. (2020). *Maritime Economics* (4th ed.). Routledge.  
3. Li, K., Shi, W., & Liu, J. (2022). Deep reinforcement learning for energy-efficient ship operation planning. *Ocean Engineering, 251*, 111109.  
4. Wang, H., & Meng, Q. (2021). Data-driven optimization of ship speed and fuel consumption under uncertainty. *Transportation Research Part E*, 152, 102407.  
5. IMO (2018). *Initial Strategy on Reduction of GHG Emissions from Ships*. IMO, London.  
6. Christiansen, M. et al. (2013). Ship Routing and Scheduling in the New Era of Sustainability. *EJOR*, 228(3), 467–483.  
7. Perera, L. P., & Mo, B. (2016). Machine learning approaches to ship performance prediction and optimization. *IEEE Journal of Oceanic Engineering*, 41(4), 871–883.

---

### 📄 Poster

[📘 Download Project Poster (PDF)](/pdf/Poster_final_print_A1.pdf)  

---

<p style="font-size:11px; color:gray;">
*Disclaimer: All datasets used in this project are synthetic or anonymized for academic demonstration.  
The views expressed are solely those of the author and do not represent any institution or company.*
</p>

[← Back to Research Overview](/research)
