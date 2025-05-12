# Petroleum_Products_Analysis
Data analysis of Nigerian petroleum products using Python
# Comparative Analysis of Physicochemical Properties of Petroleum Products from Nigerian Crude Oil

This project presents a comparative analysis of the key physicochemical properties—**API gravity**, **kinematic viscosity**, **pour point**, and **flash point**—of three petroleum products: Premium Motor Spirit (PMS), Automotive Gas Oil (AGO), and Dual-Purpose Kerosene (DPK). The analysis is based on data extracted from a peer-reviewed Nigerian study.

## 📌 Project Objective

To use Python (Pandas & Matplotlib) to explore, compare, and visualize how these critical fuel properties differ among samples (P1, P2, D1, D2, K1, K2), and to understand what this tells us about their performance, quality, and handling characteristics.

# Data Source

**Title:** Comparative Study of Physicochemical Parameters of Some Crude Oil and Petroleum Products  
**Authors:** Okeola, F.O., et al.  
**Journal:** Nigerian Journal of Pure and Applied Sciences  
**Link:** [ResearchGate PDF](https://www.researchgate.net/publication/312586836_COMPARATIVE_STUDY_OF_PHYSICOCHEMICAL_PARAMETERS_OF_SOME_CRUDE_OIL_AND_PETROLUEM_PRODUCTS)

Data was manually extracted from **Table 1** of the publication.

#Dataset

The dataset includes:

| Product | API Gravity | Viscosity (cSt @100°F) | Pour Point (°C) | Flash Point (°C) |
|--------|-------------|------------------------|------------------|------------------|
| P1 (PMS) | 63.1 | 0.20 | -3.0 | 49.6 |
| P2 (PMS) | 58.6 | 0.10 | -5.0 | 51.1 |
| K1 (DPK) | 43.6 | N/A  | +2.0 | 95.2 |
| K2 (DPK) | 44.9 | N/A  | +2.2 | 97.0 |
| D1 (AGO) | 38.9 | 4.12 | +3.2 | 244.1 |
| D2 (AGO) | 37.9 | 3.02 | +3.0 | 240.2 |

---

# Technologies Used

- **Python 3**
- **Pandas** – for data handling
- **Matplotlib** – for visualizations
- (Optionally) **Jupyter Notebook** – for analysis presentation

---

#Visualizations

The notebook generates:
- Bar charts for API Gravity
- Bar charts for Viscosity (where available)
- Bar charts for Pour Point
- Bar charts for Flash Point

These help visually assess how product type and sample origin impact performance and handling characteristics.

---

# Key Insights

- PMS (Petrol) has the **lowest flash and pour points**, suggesting easier ignition but higher flammability risk.
- AGO (Diesel) shows **higher viscosity and flash points**, making it safer but thicker for flow.
- API gravity generally **decreases from PMS → DPK → AGO**, indicating increasing heaviness.

---

#How to Use

1. Clone the repo or download the notebook.
2. Place `petroleum_products_properties.csv` in the same folder as the notebook.
3. Run the notebook or Python script.
4. Modify or extend the code to explore additional parameters if desired.

---

#License

This project is for academic and learning purposes only. Data belongs to the original authors of the cited study.

---

## Acknowledgements

Special thanks to [Okeola et al.](https://www.researchgate.net/publication/312586836) for making their research publicly accessible. Also, gratitude to the mentors and platforms enabling open data science learning.

---
