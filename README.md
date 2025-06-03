# Risk Analysis on AI-Generated Misinformation Propagation on Social Media

## 📘 Overview
This project investigates the risks associated with the spread of AI-generated misinformation across social media platforms. The primary goal is to quantify these risks using advanced data-driven and statistical methodologies, providing actionable insights for mitigation and policy development.

---

## 🎯 Objectives
- Assess the likelihood and impact of misinformation propagation.
- Quantify misinformation risks using probabilistic models.
- Compare the effectiveness of classification models.
- Evaluate mitigation strategies via decision-support tools.

---

## 🧪 Methods Used
- **Bayesian Analysis**: Updated beliefs about misinformation using posterior probabilities.
- **Poisson Distribution**: Modeled daily occurrences of misinformation events.
- **Decision Tree, Random Forest, XGBoost**: Classification of fake vs. real news based on tweet features.
- **Sensitivity Analysis & Payoff Tables**: Evaluated trade-offs between predicting "real" vs "fake".
- **Influence Diagrams & Fault/Event Trees**: Modeled system vulnerabilities and failure propagation paths.

---

## 🧠 Dataset
- **Source**: [CoAID Dataset](https://github.com/cuilimeng/CoAID)
- **Focus**: COVID-19-related misinformation tweets
- Includes tweet content, metadata, and labels (real/fake).

---

## 📊 Key Findings
- **XGBoost** achieved the highest classification accuracy (~91.24%).
- **Posterior probability** of fake news was reduced to ~7.82% with reply-based evidence.
- **Fault Tree Analysis** revealed a ~1.53% system failure probability in misinformation control.
- **Sensitivity threshold** (p = 0.065) helps optimize classification decisions.

---

## ⚠️ Limitations
- Focused only on COVID-19 misinformation.
- Does not include non-textual data (e.g., images, videos).
- Simplified models—future iterations can explore deep learning and real-time detection.

---

## 📌 Future Work
- Expand to multi-lingual and multimodal datasets.
- Integrate sentiment and engagement-based features.
- Explore deep learning models (e.g., BERT) for context-aware classification.
- Develop live misinformation detection tools with adaptive learning.

