# Leveraging AI and Machine Learning to Support Early Intervention in Children with ADHD and Autism

This repository focuses on applying **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques to pediatric neuroimaging data to support early detection and characterization of **Attention-Deficit/Hyperactivity Disorder (ADHD)** and **Autism Spectrum Disorder (ASD)**.

---

## 📘 Project Overview

This project integrates unsupervised learning methods with a sociotechnical framework to analyze neuroimaging datasets of children.  
The goal is to identify latent neurodevelopmental subgroups that may correspond to early indicators of ADHD or ASD.

---

## 🧩 Research Objectives

1. **Analyze pediatric neuroimaging data** (structural and diffusion MRI) to identify natural clusters in neurodevelopmental patterns.  
2. **Explore variations by age and sex** to detect atypical brain development trajectories.  
3. **Assess ethical, clinical, and societal implications** of using AI in early screening for neurodevelopmental disorders.

---

## 🧠 Methodology Summary

- **Dataset Source:** Pediatric brain MRI dataset (BrainMeasures, NITRC)
- **Features Used:**  
  - Gray Matter Volume (GMvol)  
  - White Matter Volume (WMvol)  
  - Cortical Thickness  
  - Fractional Anisotropy (FA)  
  - Mean Diffusivity (MD)
- **Machine Learning Models:**  
  - KMeans Clustering  
  - DBSCAN  
  - Hierarchical Clustering  
  - Principal Component Analysis (PCA)
- **Evaluation Metrics:**  
  - Silhouette Coefficient  
  - Inertia (Within-Cluster Sum of Squares)  
  - Outlier Analysis

---

## 🧮 Tools and Technologies

| Category | Tools Used |
|-----------|------------|
| Programming | Python, Jupyter Notebook |
| Libraries | NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn |
| Visualization | PCA plots, Cluster maps, Correlation heatmaps |
| Documentation | Microsoft Word, Markdown |
| Exported Outputs | HTML visualization (`ADHD.html`) |

---


---

## ⚖️ Ethical and Sociotechnical Considerations

This research emphasizes responsible AI in healthcare:
- **Ethical AI use:** ensuring fairness, transparency, and privacy in child health data.
- **Equity in access:** preventing biases in AI models that could worsen healthcare disparities.
- **Interpretability:** balancing algorithmic accuracy with clinical understanding.

---

## 📊 Key Findings (Summary)

- Identified **three primary neurodevelopmental clusters** consistent with below-average, typical, and above-average brain maturation.
- Detected **26 neuroanatomical outliers** using DBSCAN, indicating atypical development.
- Confirmed **strong correlations** between gray and white matter volumes and **inverse relationships** between FA and MD, supporting biological validity.

---

## 🏁 Conclusion

Unsupervised machine learning models can effectively uncover meaningful variability in pediatric brain development.  
These models, if ethically deployed, could aid clinicians in **early identification** and **personalized interventions** for children with neurodevelopmental disorders.

## 🧾 License

© 2025 Jimoh Olamilekan.  
This work is shared for educational and research purposes. Please credit the author appropriately if reused or referenced.

