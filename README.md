# Syntactic Complexity in Hindi-English Code-Mixing

This project investigates the structural properties of **Hindi-English code-mixed** text on social media. Using **Mean Dependency Distance (MDD)** as a proxy for cognitive demand, we analyze whether mixing languages alters syntactic complexity compared to monolingual baselines.

---

### 🚀 Key Findings
* **Structural Signature:** Code-mixed text is significantly more complex than English but simpler than Hindi ($p < 0.001$), confirming a **Hindi-governed matrix**.
* **Independence of Mixing:** Principal Component Analysis (PCA) reveals that **Mixing Intensity** and **Syntactic Complexity** are independent dimensions.
* **Simplification Trend:** A marginal trend ($r = -0.12$) suggests higher mixing intensity correlates with lower syntactic complexity.

### 📊 Methodology
* **Corpora:** Twitter-sourced datasets ($n = 600$) across Monolingual English, Monolingual Hindi, and Annotated Code-Mixed.
* **Tools:** Dependency parsing via **spaCy** and **Stanza**, calibrated on Universal Dependencies.
* **Metrics:** MDD, Code-Mixing Index (CMI), and Cross-Lingual Flux (CLF).

### 🛠️ Usage
The provided scripts support:
1. **Parsing:** Generating dependency trees for code-mixed strings.
2. **Metric Calculation:** Computing MDD and CMI at the sentence level.
3. **Visualization:** Mapping the orthogonal axes of complexity vs. intensity.
"""
