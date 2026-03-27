# 🎲 Monte Carlo Simulation — NetLogo
**Course:** BUAD 667 – Simulation by AI | University of Delaware  
**Tools:** NetLogo, Python (Google Colab)

---

## 📌 Project Overview
Built a Monte Carlo simulation model to estimate probabilities and analyze uncertainty using the Law of Large Numbers and Central Limit Theorem. This project demonstrates how increasing simulation iterations leads to more stable and reliable estimates.

---

## ❓ Problem Statement
*(Update this section with your specific simulation problem — e.g., queue modeling, risk estimation, inventory, etc.)*

---

## 🧠 Concepts Demonstrated
| Concept | Description |
|---|---|
| **Monte Carlo Method** | Using repeated random sampling to estimate outcomes |
| **Law of Large Numbers** | As N → ∞, sample mean converges to expected value |
| **Central Limit Theorem** | Distribution of sample means approaches normal as N increases |
| **Variance Reduction** | Observing how spread narrows with larger simulations |

---

## 🛠️ Tools & Technologies
- **NetLogo** — Agent-based simulation modeling platform
- **Python (Google Colab)** — Supporting statistical analysis and visualization

---

## 📈 Simulation Parameters
*(Update with your specific values)*
| Parameter | Value |
|---|---|
| Number of iterations (N) | TBD |
| Random seed | TBD |
| Key output variable | TBD |

---

## 📊 Results
*(Update with your findings)*
- At N = [X] iterations, estimated value converges to [Y]
- 95% confidence interval: [range]
- Observed variance reduction as N increases: [describe]

---

## 📁 Repository Structure
```
├── netlogo/            # .nlogo model file
├── notebooks/          # Python notebook (Google Colab .ipynb)
├── output/             # Simulation result charts and tables
└── README.md
```

---

## 🔧 How to Run
1. Download and install [NetLogo](https://ccl.northwestern.edu/netlogo/)
2. Open the `.nlogo` file from the `netlogo/` folder
3. Adjust simulation parameters in the interface panel
4. Click **Setup** then **Go** to run

For the Python analysis:
```bash
# Open the notebook in Google Colab or Jupyter
jupyter notebook notebooks/monte_carlo_analysis.ipynb
```
