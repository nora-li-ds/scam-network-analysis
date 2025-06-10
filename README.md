# Scam Network Analysis

A simple network-based simulation of fraud propagation, with node-level risk modeling and visualization. Built using Python, NetworkX, and Pandas.

---

## 🔍 Project Overview

This project models a small-scale fraud network using graph theory. It simulates how a scam might spread through victims and their contacts, assigning attributes such as `age`, `role`, and `is_risky` to each node.

It is designed for both academic and practical exploration of:
- Risk-aware fraud detection
- Influence of age and network structure
- Agent-based logic in financial crime modeling

---

## 🧠 Features

- Directed graph of fraud influence paths
- Node attributes: role, age, risk level
- Network visualization with node properties
- Exportable dataset for machine learning use

---

## 🛠️ Tech Stack

- Python 3.13+
- NetworkX
- Pandas
- Matplotlib

---

## 📁 Folder Structure

```
scam-network-analysis/
│
├── data/                # CSV file with node info
├── scripts/             # Network creation & analysis code
├── notebooks/           # Optional Jupyter notebooks
├── scam_network.py      # Main executable script
└── README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/nora-li-ds/scam-network-analysis.git
cd scam-network-analysis

# 2. (Optional) Create virtual environment
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# 3. Run the simulation
python scam_network.py
```

---

## 🧩 To-Do

- [ ] Expand network using real-world datasets (e.g. AML transaction paths)
- [ ] Add a risk prediction model (ML)
- [ ] Integrate with Agent-Based Modeling (ABM) tools (e.g. Mesa, NetLogo)
- [ ] Jupyter notebook with step-by-step explanation

---

## 👩‍💻 Author

**Nora Li**  
MSc Crime Science with Data Science @UCL  
Passionate about FinCrime AI, risk modeling, and intelligent systems.

[GitHub](https://github.com/nora-li-ds) | [LinkedIn](https://www.linkedin.com/in/xinnuoli-profile)

---

## 📄 License

This repository is licensed under the MIT License.
