# Code Demo + Reflection on "The Role of Explainable AI in the Research Field of AI Ethics"

This project combines a **hands-on demonstration of Explainable AI (XAI)** techniques with a **reflection on the paper**:

> Heidi Vainio-Pekka, Mamia Ori-Otse Agbese, Marianna Jantunen, Ville Vakkuri, Tommi Mikkonen, Rebekah Rousi, and Pekka Abrahamsson.  
> *The Role of Explainable AI in the Research Field of AI Ethics*.  
> ACM Transactions on Interactive Intelligent Systems, 13(4), Article 26, December 2023.  
> [https://doi.org/10.1145/3599974](https://doi.org/10.1145/3599974)

---

## 📖 Project Overview

- **Paper Summary**:  
  The study systematically maps empirical research in XAI within the context of AI ethics.  
  Key findings:
  - Only 23% of AI ethics papers use empirical evidence.  
  - The field is **solution-oriented**, focusing more on bias mitigation tools than on challenges.  
  - Growth surged after 2018, aligning with public discourse.  
  - Black-box issues dominate: 84% of papers are relevant to XAI.  
  - The field is still young, uneven, and in need of **accountability and user-centric approaches**.  

- **Demo Goal**:  
  Illustrate how a simple **Logistic Regression classifier** can be paired with **global explanations (permutation importance)** and **local explanations (per-sample probabilities)** to make AI models more interpretable.

---

## 🧑‍💻 Code Demo

The demo uses the classic **Iris dataset**.  
Steps included:
1. Train/test split.  
2. Logistic Regression with scaling.  
3. Performance evaluation (classification report + confusion matrix).  
4. **Global explanation**: permutation importance ranking of features.  
5. **Local explanation**: prediction probabilities for an example sample.  

---

## 📊 Example Output

**Permutation Importance (from a local run):**
