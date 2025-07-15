# 🧪 A/B Testing: Portal Layout Redesign (BPO Company)

## 📌 Project Description

This repository presents a complete simulation of an A/B test conducted in a business process outsourcing (BPO) environment. The company is preparing to launch a new design for its internal employee portal, and the data science team is tasked with evaluating whether the new layout has a measurable impact on key user behaviors.

The goal is to apply rigorous experimental design and statistical methods to determine if the new version should be fully deployed.

---

## 🎯 Objectives

### ✅ Part 1 – Experiment Design & Setup
- Calculate required sample size based on pilot effect size.
- Randomly assign users from `user_id.csv` to:
  - Control group (`Old` layout)
  - Treatment group (`New` layout)
- Export `random_assignment.csv` for implementation by data engineers.

### ✅ Part 2 – A/B Test Analysis
Using behavioral data from `lab15_data.csv`:
- Conduct exploratory data analysis and visualizations.
- Compare key metrics between versions:
  - Purchase behavior
  - Activation rate
- Perform statistical tests:
  - Shapiro-Wilk Test
  - Chi-Square Test
  - Independent t-test and Mann-Whitney U Test
  - Proportions Z-Test
  - Levene's Test for equal variances
- Calculate:
  - Effect size (Cohen’s d)
  - Power of the test
  - 95% Confidence Intervals

---

## 🗃️ Datasets

| File | Description |
|------|-------------|
| `user_id.csv` | Employee ID list for 1,000 users |
| `lab15_data.csv` | Simulated experiment results containing version assignments and behavioral metrics |

---

## 🧰 Libraries & Tools

- Python 3
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy.stats`, `statsmodels`

---

## ❓ Key Questions Addressed

- How many users are needed for reliable experimentation?
- Does the new portal version significantly improve activation or purchases?
- Can we confidently recommend the new design for full deployment?

---

## 📈 Outcome

This project demonstrates a real-world application of A/B testing principles. It shows how data scientists can use statistical reasoning, experimental design, and inferential analysis to support product decisions.

---

## 🚀 How to Run

1. Clone the repository.
2. Open the Colab notebook: `ab_test_portal_layout.ipynb`.
3. Upload `user_id.csv` and `lab15_data.csv`.
4. Run all cells to replicate the analysis.

---

## 👤 Author

**Your Name**  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for more details.
