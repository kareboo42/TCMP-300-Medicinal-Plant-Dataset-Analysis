# 🌿 TCMP-300 Medicinal Plant Dataset Analysis  
**Author:** [Your Name]  
**Date:** [Month Year]  

---

## 🧭 Overview  
This project explores the **TCMP-300 (Traditional Chinese Medicinal Plant)** dataset — a large-scale resource designed to support AI-based medicinal plant recognition.  

The dataset contains metadata for **300 species** used in Traditional Chinese Medicine, including scientific (Latin) names, plant families, and image counts for model training and validation.  

The goal of this project is to:
- Summarize the dataset structure  
- Visualize its botanical diversity  
- Discuss its potential applications in pharmacognosy and biomedical AI research  

---

## 💾 Data Source  
**Paper:**  
Yang *et al.* (2025). *TCMP-300: A Comprehensive Traditional Chinese Medicinal Plant Dataset for Plant Recognition.* *Nature Scientific Data.*  
🔗 [Dataset DOI](https://doi.org/10.6084/m9.figshare.29432726)

**File Used:**  
`tcmp-info-20250329.csv` (metadata file with species and image counts)

---

## 🧰 Tools & Libraries  
- Python 3.x  
- pandas  
- seaborn  
- matplotlib  
- Jupyter Notebook  

*(optional future tools: TensorFlow, PyTorch for image modeling)*

---

## 📊 Key Analyses & Visualizations  
1. **Top 10 Plant Families**  
   - Identifies which botanical families are most represented in TCMP-300.  
2. **Distribution of Image Counts**  
   - Examines dataset balance and class representation for AI modeling.  
3. **Top 10 Most Represented Species**  
   - Highlights which species have the highest number of images.  

Each figure is accompanied by Markdown commentary summarizing key insights.

---

## 🧩 Insights  
- The dataset includes **300 unique species** from diverse medicinal plant families.  
- **Asteraceae**, **Lamiaceae**, and **Fabaceae** are among the most common.  
- The average number of images per species is approximately 150–200, providing strong coverage for model training.  
- TCMP-300 supports applications in **automated plant identification**, **pharmacognosy**, and **AI-assisted herbal research**.

---

## 🚀 Future Work  
- Integrate TCMP-300 species data with chemical and bioactivity databases (PubChem, TCMID).  
- Develop a CNN model for automatic image classification.  
- Extend analysis to connect plant species with known medicinal compounds.  

---

## 📁 Project Structure  
