# 🧠 Narrative-Driven Computational Framework for Clinician Burnout Surveillance

## 📌 Overview
Clinician burnout is a critical challenge affecting patient safety, care quality, and healthcare workforce sustainability—especially in high-acuity ICU environments. Traditional approaches rely on retrospective surveys or coarse EHR metadata, limiting real-time and longitudinal insights.

This project introduces a **narrative-driven, weakly supervised computational framework** that leverages ICU clinical notes to detect and monitor clinician burnout risk.

---

## 🎥 Demo Video
[![Watch the Demo](https://img.youtube.com/vi/XBfgeUb-9q0/0.jpg)](https://www.youtube.com/watch?v=XBfgeUb-9q0)

---

## 👨‍🔬 Authors
- **Fazel Keshtkar**  
- **Alyssa Meczkowska**  
- **Neeam Shahriar Hayder**  
- **Syed Ahmad Chan Bukhari*** (Corresponding Author)  

📍 *St. John’s University, Queens, NY, USA*

---

## 🧩 Key Contributions
- 📝 **Narrative NLP Framework** using BioBERT for extracting stress signals from clinical text
- 📊 **Weakly Supervised Labeling** via quantile-based ordinal risk stratification (low, medium, high)
- ⏳ **Temporal Modeling** for tracking burnout trajectories over time
- 🔍 **Multi-Modal Feature Integration**:
  - Sentiment analysis
  - Lexical stress cues
  - Topic modeling
  - Structured workload proxies
- 🎯 **High Performance**: Achieved **F1-score = 0.84** for high-risk detection

---

## 📂 Dataset
- **MIMIC-IV Clinical Database**
- ~10,000 ICU discharge summaries analyzed

⚠️ Note: Data is proprietary. Users must request access directly via PhysioNet.

---

## 📈 Key Findings
- ICU narratives encode **rich longitudinal burnout signals**
- Elevated burnout indicators observed in:
  - Radiology
  - Psychiatry
  - Neurology
- Narrative-based models outperform metadata-only approaches for surveillance tasks

---

## ⚙️ Methodology
1. Clinical text preprocessing
2. BioBERT-based sentiment modeling
3. Feature extraction (lexical, semantic, temporal)
4. Weak supervision (quantile labeling)
5. Logistic regression classifier
6. Temporal trend analysis

---

## 🚀 Applications
- Real-time clinician burnout monitoring
- ICU workforce analytics
- Healthcare system decision support
- Early intervention systems

---

## 🤝 Collaboration & Contact
For questions, collaborations, or access requests:

📧 **Syed Ahmad Chan Bukhari**  
Email: bukharis@stjohns.edu

---

## 🏷️ Keywords
Clinician Burnout, Narrative NLP, BioBERT, ICU Analytics, Weak Supervision, Temporal Modeling, Healthcare AI

---

## ⭐ Citation
If you use this work, please cite our paper (details coming soon).

---

## 🔬 Lab
Developed under **HikLab / Bukhari Lab**
