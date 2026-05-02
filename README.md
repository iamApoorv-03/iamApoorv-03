# Hi, I'm Apoorv 

**AI Researcher** · Shoolini University, India · 3rd Year B.Tech (Artificial Intelligence)

I work at the intersection of **deep learning and clinical medicine** — specifically on why AI systems fail the patients who need them most.

---

## 🔬 The Problem I'm Working On

I built a Swin Transformer for breast cancer detection on CBIS-DDSM.

| Metric | Result |
|--------|--------|
| Overall AUC | **0.98** |
| TPR Gap (Dense vs Fatty Tissue) | **12.3%** |
| TPR Gap after Adversarial Debiasing | **23%** ⚠️ |

The standard fix made it **worse**.

**Why?** Tissue density and tumour morphology are entangled in the feature space. When you train the model to stop encoding density, you remove part of the signal it needs to detect cancer in dense tissue. The model becomes fairer by one metric and more dangerous for the patients that metric was supposed to protect.

**The fix isn't post-hoc. It has to be architectural.**

I'm currently building an **ensemble-of-experts** with density-stratified pathways and subgroup-specific calibration heads — so each expert learns the signal structure of its own tissue subgroup independently.



---

## 📌 Other Work

**🧬 Causal-FedFusion**
Multimodal fusion of MRI radiomics and genomics for glioma therapy stratification using causal inference inside a federated learning framework.
✅ Abstract accepted — **IC3R 2025, BRIC-NCCS Pune**

**💊 OPOINT-Bolt**
Generative AI pipeline for structure-based drug design targeting G-protein-biased mu-opioid receptor agonists. Multi-constraint optimisation: preserve analgesic effect, eliminate addiction pathway.
🏆 **2nd Place International** — Boltzmann Labs Bio-Hackathon 2025 (76 teams)

**📝 Review Paper in Preparation**
*Machine Learning for First-Trimester Prediction of Pre-Eclampsia Using Maternal Serum Biomarkers and Clinical Risk Factors: A Systematic Review and Meta-Analysis*

---

## 🛠️ Stack

**Deep Learning**
`PyTorch` `Swin Transformer` `Fairlearn` `SHAP` `Grad-CAM` `TensorFlow`

**Computational Biology**
`RFdiffusion` `AutoDock Vina` `ADMET` `ChEMBL`

**Languages & Tools**
`Python` `C++` `SQL` `Git` `Linux` `LaTeX` `Docker` `FastAPI`

---

## 🎯 Research Interests

Fairness-aware deep learning · Medical image analysis · Distribution shift in clinical datasets · Uncertainty quantification · Generative AI for computational biology

---

## 📬 Connect

- 📧 apoorvprashar2006@gmail.com
- 💼 [linkedin.com/in/apoorv-ai](https://linkedin.com/in/apoorv-ai)

