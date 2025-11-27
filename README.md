# 🧠 AI-AHP Decision Agent  
### Guiding Where B2B Innovation Should Go Next  

🏆 **1st Place – T.L. Saaty Decision-Making for Leaders Hackathon (University of Pittsburgh, 2025)**  
Built an AI-powered decision support system that helps **B2B companies** identify which market or innovation to prioritize — using **AHP (Analytic Hierarchy Process)** and **AI-assisted research automation**.

You can explore the full analysis and presentation below:
- **AHP Model Notebook** — core logic, pairwise matrices, sensitivity tests, and Monte Carlo simulation  
  👉 [Open Notebook](<[INSERT LINK](https://github.com/Timothy0324/ai-decision-agent-ahp-anp/blob/main/Hackathon_AI%20DECISION%20AGENT_AHP.ipynb)>)

- **Final Presentation (PDF)** — our 1st-place winning presentation  
  👉 [View Presentation](<[Where B2B Innovation Should Go_compressed.pdf](https://github.com/Timothy0324/ai-decision-agent-ahp-anp/blob/main/Where%20B2B%20Innovation%20Should%20Go_compressed.pdf)>)

---

## Project Overview  
The **AI-AHP Decision Agent** integrates structured decision logic (AHP) with AI-assisted data collection to deliver fast, explainable, and scalable recommendations for strategic market entry and investment decisions.

**Key Objectives:**  
- Transform qualitative market insights into quantitative decision models.  
- Automate research data input using AI tools.  
- Ensure model transparency, stability, and repeatability.  

---

## Features  
**AI-Driven Research** – Uses large language models (e.g., Gemini, GPT) to summarize industry data and extract key metrics.  
**AHP Engine (Python)** – Performs pairwise comparisons, weight calculations, and consistency validation.  
**Monte Carlo Sensitivity Test** – Runs 5,000+ simulations to ensure model robustness.  
**Visualization** – Includes matrix heatmaps, rank-reversal charts, and stability plots.  
**Decision Report** – Generates ranked alternatives with stability and ROI insights.  

---

## Methodology  

### Step 1: Define the Decision Hierarchy  
**Goal:** Select the best AI market or application to invest in.  
**Criteria:** ROI Potential, Market Demand, Implementation Cost, Technical Feasibility, Scalability & Adoption  
**Alternatives:**  
- AI Quality Inspection  
- Predictive Maintenance  
- Energy Optimization  
- Adaptive Machining  
- Supply Chain Forecasting  

### Step 2: Pairwise Comparison (AHP)  
- Built criteria and sub-criteria matrices in Python.  
- Calculated weights using eigenvalue method.  
- Verified consistency ratio (CR < 0.1).  

### Step 3: Sensitivity Analysis  
- Tested three “what-if” scenarios (Cost↑1.5, Demand↑1.3, ROI↑1.2).  
- Performed **Monte Carlo simulation (n=5000)** — *AI Quality Inspection ranked #1 in 4,592 runs (>95% consistency).*  

### Step 4: Decision Output  
- Generated final scores and visualizations.  
- Built a draft report with AI-summarized financials and risk metrics.

---

## 📊 Results  

| Alternative | Final Score |
|--------------|--------------|
| **AI Quality Inspection** | **0.2523** |
| Predictive Maintenance | 0.2306 |
| Energy Optimization | 0.1923 |
| Adaptive Machining | 0.1782 |
| Supply Chain Forecasting | 0.1466 |

**Model Consistency:** 0.048 (Acceptable)  
**Stability:** >95% ranking consistency across 5,000 Monte Carlo runs  

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, SciPy  
- **Optional Tools:** Gemini Deep Research / Perplexity / GPT for research  
- **Visualization:** Jupyter Notebook, Matplotlib  

---

## 📂 Repository Structure  

