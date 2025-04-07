
# Market Risk Modeling and Validation: A Quantitative Approach to VaR

## 📌 Project Overview

This project presents a comprehensive, model risk-aware framework for estimating and validating Value at Risk (VaR) and Expected Shortfall (ES) using multiple quantitative techniques. It is designed to simulate real-world model validation workflows as expected in Model Risk Governance teams at leading financial institutions.

The goal is not just to estimate VaR, but to **stress-test, compare, and validate** different approaches for robustness, transparency, and risk sensitivity — reflecting the principles of **Basel/ FRTB-aligned model governance**.

---

## 🧠 Key Concepts

- Market Risk & Value at Risk (VaR)
- Model Risk & Governance
- Quantitative Model Validation
- Risk Simulation & Tail Modeling

---

## ⚙️ Methodologies Implemented

| Technique                         | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| **Historical Simulation**        | Non-parametric VaR using historical portfolio returns.                      |
| **Monte Carlo Simulation**       | Parametric VaR using normal distribution of returns.                        |
| **Student-t Monte Carlo**        | Captures fat tails with Student-t distribution.                             |
| **GARCH(1,1) Forecasting**       | Volatility clustering via ARCH models, forecasting risk.                   |
| **Put Option Hedging**           | VaR impact with a basic derivatives hedging strategy.                       |
| **Copula-Based Simulation**      | Dependency modeling between asset returns using Gaussian copula.            |
| **Extreme Value Theory (EVT)**   | Tail-focused risk modeling with Peaks-Over-Threshold method.               |
| **VaR Comparison Table**         | Consolidated side-by-side VaR/ES estimates across models.                  |
| **Visual Analysis**              | Histograms, KDE plots, VaR/ES lines, and violation shading.                |

---

## 🔍 Objectives

- ✅ Compare traditional and advanced VaR estimation techniques  
- ✅ Incorporate volatility forecasting and fat-tail modeling  
- ✅ Understand the effect of hedging on portfolio risk  
- ✅ Simulate realistic portfolio dependencies via copulas  
- ✅ Apply EVT for extreme risk estimation  
- ✅ Align risk estimates with model validation best practices  

---

## 📈 Tools & Libraries

- `Python` (Pandas, NumPy, SciPy)
- `Matplotlib`, `Seaborn` — Visualization  
- `arch` — GARCH Modeling  
- `statsmodels` — Econometrics  
- `scikit-learn` — Copula modeling  
- `scipy.stats.genpareto` — EVT modeling

---

## 🧪 Model Governance Insight

This project mirrors real-world model validation workflows, including:

- Model specification review
- Stress testing and assumptions
- Comparison of outputs across modeling choices
- Evaluation of risk tail behavior
- Documentation of model strengths and limitations

---

## 🧾 Sample Output (Summary Table)

| Method                   | VaR (99%) | Expected Shortfall (99%) |
|--------------------------|-----------|---------------------------|
| Historical               | -4.72%    | -6.39%                    |
| Monte Carlo (Normal)     | -4.02%    | -4.59%                    |
| Student-t Monte Carlo    | -4.69%    | -6.08%                    |
| GARCH Forecasting        | -1.22%    | -2.31%                    |
| EVT (Generalized Pareto) | -4.98%    | -8.32%                    |

---

## 🏁 Next Steps (Optional)

- [ ] Add backtesting and Kupiec/Poferr test  
- [ ] Automate report generation  
- [ ] Deploy as an interactive Streamlit dashboard  

---

## 👨‍💼 Role Alignment: J.P. Morgan Model Risk Governance

This project reflects the core competencies expected in a **Quant Modelling Analyst** role:

- Strong model validation mindset  
- Deep understanding of market risk models (VaR, ES, GARCH)  
- Implementation of advanced quantitative methods  
- Attention to model robustness, performance, and limitations  

---

## 📬 Contact

**Akash Das**  
Quantitative Finance | Market Risk | Python Modeling  
[Email/LinkedIn/GitHub Link Here]
