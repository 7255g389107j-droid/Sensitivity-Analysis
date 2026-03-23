# Sensitivity-Analysis
Sensitivity Analysis of the System
# Sensitivity Engine: LOO-Stability Tracker (Diagnostic Module)

> **"Do not just remove outliers. Diagnose the storm behind them."**

In Compositional Data Analysis (CoDA), when a specific sample destabilizes the "Unchanging Reference Component" (the Anchor), it is not a mere error—it is a **critical signal**. This engine performs a **Leave-One-Out (LOO) Sensitivity Analysis** to pinpoint which samples deviate from the common physical and geometric logic of the system.

Developed by **Tatsuki Itagaki** as a core diagnostic tool for **Practical Science and Deep Investigation.**

## 🔍 The Mission: Beyond Outlier Removal
The goal of this engine is not to "clean" the data to fit a model. Instead, it measures the **System Stability Impact** of each sample to trigger a scientific inquiry: 

**"What external factor caused this specific sample to shift the entire compositional baseline?"**

It tracks the impact across two critical dimensions:
1.  **Physical Delta (Delta_IR):** Measures the shift relative to the **Poisson Noise Floor (Invariance Ratio)**.
2.  **Geometric Delta (Delta_PI):** Measures the shift in the **Geometric Purity (Purity Index)** of the compositional simplex.

## 🚀 Key Features
- **Perturbation Scoring:** Identifies samples that carry a different "Physical Logic" compared to the rest of the set.
- **Dual-Panel Diagnostic Visualization:** 
    - **Panel 1 (Physical):** Reveals samples that exhibit non-Poisson noise (indicating external interference or measurement shifts).
    - **Panel 2 (Geometric):** Reveals samples that pull the "Geometric Center" toward a different state.
- **Numerical Traceability:** Every bar is labeled with its exact impact value, allowing researchers to correlate stability shifts with external metadata (Time, Temperature, Concentration, etc.).
## 🧪 The "Itagaki Method" of Investigation
When a sample shows a high **Combined_Score** (indicating it destabilizes the anchor), it is a call for scientific inquiry:

1.  **Identify the Perturber:** Note the Sample Index from the diagnostic plots.
2.  **External Correlation:** Ask: Did an external event occur at this specific time-point? (e.g., environmental change, biological spike, or a shift in measurement conditions).
3.  **Physical Inquiry:** If a sample destabilizes the anchor, it proves that the **"Unchanging Reference"** is no longer unchanging in that specific context. This is a **discovery**, not an error.
4.  **The Honest Conclusion:** If stability is lost, report the **Truth**. The loss of an anchor is evidence of a fundamental shift in the system's basis. Do not hide the deviation; explain its origin.

## 🛡 Philosophy: Statistics as a Practical Science
Removing a sample just to get a "clean" result is a betrayal of the data. Use this engine to **validate the boundaries of your system.** 

> **"The truth lies in the deviation."**

---
**Author:** Tatsuki Itagaki  
**Motto:** Find the truth behind the storm.
