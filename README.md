# RWH + SHAP Pipeline (Vilniaus Maironio Progimnazija Case Study)

**Author:** Dr. Tevfik Denizhan Müftüoğlu  
**License:** MIT (free to use with attribution)  

This repository provides a reproducible **Google Colab pipeline** for simulating rainwater harvesting (RWH) and analyzing results with **SHAP explainability**.  
It was applied in the case study of **Vilniaus Maironio Progimnazija**, as presented in the article:  

*“Sustainable Modernization of Educational Buildings: Explainable AI-Supported Rainwater Harvesting Framework at Vilniaus Maironio Progimnazija”*  

---

## 🚀 Quick start (Colab)
1. Open `RWH_Vilnius.ipynb` in Google Colab  
2. Run the single cell  
3. Upload the Excel file `POWER_Vilnius_Maironis_2000_2025.xlsx` when prompted  
4. Download the generated ZIP with all outputs  

---

## 📂 Repository structure
- `RWH_Vilnius.ipynb` → One-cell Colab notebook (main pipeline)  
- `POWER_Vilnius_Maironis_2000_2025.xlsx` → Input dataset (NASA POWER, 2000–2025)  
- `requirements.txt` → Python dependencies  
- `outputs/` → Figures (generated after running)  
- `results/` → Tables (generated after running)  
- `LICENSE` → MIT License  
- `README.md` → Documentation  

---

## 📊 Outputs
- Correlation heatmap (`outputs/Correlation_heatmap.png`)  
- RWH reliability plots (`outputs/Rv_vs_Tank_*.png`)  
- SHAP explainability figures (`outputs/SHAP_*.png`)  
- Descriptive statistics tables (`results/*.xlsx`)  
- Packaged ZIP with all results for reproducibility  

---

## 🔗 Citation
If you use this code, please cite:  

Muftuoglu, T.D. (2025). *RWH + SHAP Pipeline for Vilniaus Maironio Progimnazija*. GitHub Repository. https://github.com/tdmuftuoglu/RWH_Vilnius_Maironis  

(A Zenodo DOI will be added in the camera-ready version of the article.)

