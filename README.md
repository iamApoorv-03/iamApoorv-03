Hi, I'm Apoorv
I'm a third-year undergraduate in Artificial Intelligence at Shoolini University, India. I work at the intersection of deep learning and clinical medicine — specifically on the question of why AI systems fail the patients who need them most.

The Problem I'm Working On
I built a Swin Transformer for breast cancer detection on the CBIS-DDSM dataset. Overall AUC: 0.98. Strong result.
Then I looked at performance by breast tissue density.
Dense tissue subgroups had a 12.3% TPR gap — meaning the model was systematically missing cancers in the patients already hardest to diagnose and at highest clinical risk.
Standard fix: apply adversarial debiasing and importance reweighting.
Result: the gap grew to 23%.
I spent a long time trying to find the mistake. There was no mistake. The interventions were working as designed. They were just making things worse.
Why? Tissue density and tumour morphology are entangled in the feature space. When you train the model to stop encoding density, you remove part of the signal it needs to detect cancer in dense tissue. The model becomes fairer by one metric and more dangerous for the patients that metric was supposed to protect.
The fix isn't post-hoc. It has to be architectural. I'm currently building an ensemble-of-experts with density-stratified pathways and subgroup-specific calibration heads — so each expert learns the signal structure of its own tissue subgroup independently.
Manuscript in preparation → MICCAI 2026
→ FairBreastAI-Bias-Mitigation

Other Work
Causal-FedFusion — Multimodal fusion of MRI radiomics and genomics for glioma therapy stratification, using causal inference inside a federated learning framework. Abstract accepted at IC3R 2025, BRIC-NCCS Pune.
OPOINT-Bolt — Generative AI pipeline for structure-based drug design targeting G-protein-biased mu-opioid receptor agonists. Built for a multi-constraint optimisation problem: preserve analgesic effect, eliminate addiction pathway. 2nd Place International, Boltzmann Labs Bio-Hackathon 2025 (76 teams).
Review paper in preparation — ML for First-Trimester Prediction of Pre-Eclampsia Using Maternal Serum Biomarkers and Clinical Risk Factors: A Systematic Review and Meta-Analysis.

Stack
Deep Learning    PyTorch · Swin Transformer · Fairlearn · SHAP · Grad-CAM
Comp. Biology    RFdiffusion · AutoDock Vina · ADMET · ChEMBL
Languages        Python · C++ · SQL
Tools            Git · Linux · LaTeX · Docker · FastAPI

Research Interests
Fairness-aware deep learning · Medical image analysis · Distribution shift in clinical datasets · Uncertainty quantification · Generative AI for computational biology

Connect

📧 apoorvprashar2006@gmail.com
💼 linkedin.com/in/apoorv-ai
📄 Available for research internships from May 2026
