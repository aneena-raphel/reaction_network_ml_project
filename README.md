# DYNACAT Demo — Reaction Network + Machine Learning for Catalysis

This repository demonstrates skills directly relevant to the **TU Delft PhD position**  
*Computational Modeling and In Silico Design of Dynamic Hydrogenation Catalysis (DYNACAT)*:

- **Reaction network analysis** of a toy ethylene → ethane hydrogenation cycle
- **Energy span model** (Kozuch–Shaik inspired) to identify turnover-determining states
- **Baseline machine learning models** for **H adsorption energy prediction** on transition-metal surfaces
- A fully reproducible workflow with clean datasets and Jupyter notebooks

---

## 📂 Repository Structure

├── data/
│ └── dynacat_dataset.csv # Toy dataset (reaction pathways + adsorption energies)
├── notebooks/
│ └── dynacat_analysis.ipynb # Main notebook: Reaction networks + ML
├── requirements.txt # Python dependencies
└── README.md # Project description


---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/dynacat-demo.git
   cd dynacat-demo
pip install -r requirements.txt
jupyter notebook notebooks/dynacat_analysis.ipynb
