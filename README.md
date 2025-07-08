#  Explainable AI Demos: From Curiosity to Clarity

> A multi-modal journey into the world of XAI — covering tabular, text, image data, and even transformers.

---

##  Why This Project Exists

In late 2023, I found myself obsessing over a simple but powerful question:

> "We trust models to make decisions — but do we understand how they do it?"

This question hit harder when I realized something troubling: **even when traditional ML models give us a vague idea of what’s going on under the hood, LLMs (Large Language Models) remain mostly a black box.** That tension between *trust* and *transparency* drove me into the rabbit hole of **Explainable AI (XAI).**

So in **November 2023**, fueled purely by curiosity, I began this project — not as a research requirement, not for a job, but to satisfy a need to know:  
**Can we really explain what our models are thinking?**

---

##  What’s Inside

This repo is a hands-on, multi-modal collection of XAI experiments using:

-  **SHAP** (Shapley Additive Explanations)
-  **LIME** (Local Interpretable Model-agnostic Explanations)
-  **BERTViz** (Transformer attention visualization)

Each notebook dives deep into **interpreting decisions** made by models trained on **tabular**, **text**, or **image** data.

---

##  Project Breakdown

| Domain     | Notebook(s) | Description |
|------------|-------------|-------------|
| **Tabular** | `XAI_SHAP.ipynb`<br>`LIME_tabular_manual_interpretation.ipynb`<br>`Covid19_XAI.ipynb` | Model explanations for structured data using SHAP and LIME. COVID case study included. |
| **Text** | `XAI_LIME_text.ipynb`<br>`LIME_text_manual_interpretation.ipynb`<br>`BertViz.ipynb` | XAI for NLP tasks + BERT attention visualization. |
| **Image** | `XAI_LIME_image.ipynb` | LIME applied to CNN predictions. |
| **Concept Comparison** | `LIME_SHAP.ipynb` | Direct contrast between LIME and SHAP on the same problem. |

---

##  Why This Project Is Different

Most tutorials stick to one dataset, one domain, or one method. This project explores **XAI across domains** and includes:
- Manual interpretation walkthroughs
- Real-world data (e.g. COVID-19 clinical data)
- Transformer-level introspection with BERTViz
- A curiosity-first origin story — not just a checklist project

---
