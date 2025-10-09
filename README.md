# RWH + SHAP Pipeline for Rainwater Harvesting Simulation
## Yağmur Suyu Hasadı Simülasyonu için RWH + SHAP Projesi
### (Vilniaus Maironio Progimnazija Case Study / Vaka Çalışması)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Framework](https://img.shields.io/badge/Framework-Google%20Colab-orange.svg)

This repository provides a reproducible **Google Colab pipeline** for simulating rainwater harvesting (RWH) systems and analyzing the simulation results with **SHAP explainability**. The methodology was applied in the case study of **Vilniaus Maironio Progimnazija** and is associated with the scientific article:

*“Sustainable Modernization of Educational Buildings: Explainable AI-Supported Rainwater Harvesting Framework at Vilniaus Maironio Progimnazija”*

---
Bu repo, yağmur suyu hasadı (YSH) sistemlerini simüle etmek ve simülasyon sonuçlarını **SHAP ile açıklanabilirlik** analizi yaparak incelemek için tekrarlanabilir bir **Google Colab kodu** sunmaktadır. Metodoloji, **Vilniaus Maironio Progimnazija** vaka çalışmasında uygulanmış olup aşağıdaki bilimsel makale ile ilişkilidir:

*“Eğitim Binalarının Sürdürülebilir Modernizasyonu: Vilniaus Maironio Progimnazija'da Açıklanabilir Yapay Zeka Destekli Yağmur Suyu Hasadı Çerçevesi”*

---

## How to Use (Google Colab) / Nasıl Kullanılır?

This project is designed for one-click execution in Google Colab.
Bu proje, Google Colab'de tek tıkla çalışacak şekilde tasarlanmıştır.

1.  **Open the Notebook:** Open `RWH_Vilnius.ipynb` in Google Colab.  
    **Not Defterini Açın:** `RWH_Vilnius.ipynb` dosyasını Google Colab'de açın.
2.  **Run the Cell:** Execute the single code cell in the notebook.  
    **Hücreyi Çalıştırın:** Not defterindeki tek kod hücresini çalıştırın.
3.  **Upload Data:** When prompted, upload the Excel file `POWER_Vilnius_Maironis_2000_2025.xlsx`.  
    **Veriyi Yükleyin:** İstendiğinde, `POWER_Vilnius_Maironis_2000_2025.xlsx` adlı Excel dosyasını yükleyin.
4.  **Download Results:** A ZIP file containing all outputs will be automatically generated and downloaded.  
    **Sonuçları İndirin:** Tüm çıktıları içeren bir ZIP dosyası otomatik olarak oluşturulacak ve indirilecektir.

---

## Repository Structure / Repo Yapısı

-   `RWH_Vilnius.ipynb` → The one-cell Google Colab notebook containing the main pipeline. / Ana işlem hattını içeren tek hücreli Google Colab not defteri.
-   `POWER_Vilnius_Maironis_2000_2025.xlsx` → The input dataset (NASA POWER, 2000–2025). / Girdi veri seti (NASA POWER, 2000–2025).
-   `requirements.txt` → A list of Python dependencies. / Python bağımlılıklarının listesi.
-   `outputs/` → Directory for generated figures. / Oluşturulan grafiklerin saklandığı dizin.
-   `results/` → Directory for generated data tables. / Oluşturulan veri tablolarının saklandığı dizin.
-   `LICENSE` → The MIT License file. / MIT Lisans dosyası.
-   `README.md` → This documentation file. / Bu dokümantasyon dosyası.

---

## Outputs / Üretilen Çıktılar

The script automatically generates the following files:
Kod, aşağıdaki dosyaları otomatik olarak üretir:

-   **Correlation Heatmap / Korelasyon Isı Haritası:** `outputs/Correlation_heatmap.png`
-   **RWH Reliability Plots / YSH Güvenilirlik Grafikleri:** `outputs/Rv_vs_Tank_*.png`
-   **SHAP Explainability Figures / SHAP Açıklanabilirlik Grafikleri:** `outputs/SHAP_*.png`
-   **Descriptive Statistics Tables / Tanımlayıcı İstatistik Tabloları:** `results/*.xlsx`
-   **Packaged ZIP Archive / Paketlenmiş ZIP Arşivi:** A single ZIP file containing all results for easy sharing and reproducibility. / Kolay paylaşım ve tekrarlanabilirlik için tüm sonuçları içeren tek bir ZIP dosyası.

---

## Citation / Atıf

If you use this code in your research, please cite the repository:
Bu kodu araştırmalarınızda kullanırsanız, lütfen repoya atıfta bulunun:

Muftuoglu, T.D. (2025). *RWH + SHAP Pipeline for Vilniaus Maironio Progimnazija*. GitHub Repository. https://github.com/tdmuftuoglu/RWH_Vilnius_Maironis

*(A Zenodo DOI will be added in the camera-ready version of the article.)*
*(Makalenin baskıya hazır versiyonunda bir Zenodo DOI'si eklenecektir.)*

---

## Author / Yazar

-   **Dr. Tevfik Denizhan Müftüoğlu**

---

## License / Lisans

This project is licensed under the MIT License. You are free to use, modify, and distribute it, provided the original author attribution is maintained.
Bu proje MIT Lisansı altında lisanslanmıştır. Orijinal yazar atfı korunduğu sürece kodu kullanmakta, değiştirmekte ve dağıtmakta serbestsiniz.
