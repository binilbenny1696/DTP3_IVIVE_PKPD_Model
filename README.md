# 🔬 DTP3_IVIVE_PKPD_Model

This project uses **in vitro-in vivo extrapolation (IVIVE)** and **PK/PD modeling in R** to simulate the therapeutic potential of **DTP3**, a GADD45β/MKK7 pathway disruptor under investigation for **multiple myeloma**. Simulations assess single and multiple dosing regimens (BID/TID) using **IC50 data from cell viability assays**, and predict plasma concentrations and % inhibition using a two-compartment PK model and an Emax PD model.

---

## 🧪 Project Objective

- Translate preclinical **IC50 and safety threshold** data to human plasma levels.
- Simulate PK using 2-compartment IV bolus model with humanized parameters.
- Apply Emax model to predict % inhibition over time.
- Compare **BID vs. TID** dosing for 24-hour target coverage.

---

## 🧰 Tools Used

| Category | Tools |
|----------|-------|
| Programming | R |
| Modeling | 2-compartment PK, Emax PD |
| Data | Simulated based on Tornatore et al. (2014, *Cancer Cell*) |
| Output | Plasma concentration vs. time, % inhibition, time > IC50, AUC |

---

## 📂 Project Structure


---

## 📈 Key Findings

- **TID dosing** resulted in higher trough levels and sustained % inhibition over 24 hrs.
- **Peak concentration** (~7.5 µM) stayed **below toxicity threshold (10 µM)**.
- Efficacy sustained for **>60% inhibition** across 24 hours in TID, while BID fell short.

---

## 📚 References

- Tornatore et al., *Cancer Cell*, 2014  
- DTP3 clinical pipeline (UK MM Phase I study)  
- Standard IVIVE and PK/PD modeling literature

---

## 👤 Author

**Binil Benny**  
Translational Pharmacology | IVIVE | PKPD Simulation  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

## 🪪 License

Licensed under the [MIT License](LICENSE).
