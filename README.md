# <p align="center">🏥 DiabetAltery: Veri Odaklı Diyabet Analizi</p>
<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=waving&color=auto&height=200&section=header&text=Diyabet%20Tahmin%20Modeli&fontSize=50&animation=fadeIn&fontAlignY=35" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" />
</p>

## 📌 Proje Genel Bakışı
Bu çalışma, diyabet hastalığının erken teşhisi için makine öğrenmesi algoritmalarının performansını analiz eder[cite: 1]. Veri seti üzerinde kapsamlı temizlik, tıbbi literatüre uygun yeni öznitelik türetme (Feature Engineering) ve hiperparametre optimizasyonu süreçlerini kapsar[cite: 1].

## 🧪 Uygulanan Metodoloji
| Aşama | Açıklama | Kullanılan Teknik |
| :--- | :--- | :--- |
| **Veri Temizliği** | İmkansız 0 değerlerinin giderilmesi[cite: 1] | Medyan İmputasyonu |
| **Aykırı Değer** | Uç değerlerin sisteme zarar vermesini engelleme[cite: 1] | IQR (Interquartile Range) |
| **Öznitelik Mühendiliği** | Yeni anlamlı değişkenler türetme[cite: 1] | DSÖ BMI & Yaş Kategorileri |
| **Optimizasyon** | En iyi model parametrelerini bulma[cite: 1] | RandomizedSearchCV |

## 📊 Karşılaştırmalı Model Sonuçları
Proje kapsamında denenen modellerin başarı oranları aşağıda tablolanmıştır:

| Algoritma | Accuracy (Doğruluk) | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| K-Nearest Neighbors | %73 | 0.65 | 0.44 | 0.52 |
| Logistic Regression | %77 | 0.71 | 0.57 | 0.63 |
| Random Forest (Base) | %77 | 0.72 | 0.57 | 0.64 |
| **Random Forest (Optimized)** | **%79** | **0.74** | **0.62** | **0.67** |

> **Önemli Bulgular:** Yapılan optimizasyon çalışmaları sonucunda modelin AUC skoru **0.81'den 0.86'ya** yükseltilmiştir[cite: 1].

## 📁 Klasör Yapısı
```text
DiabetAltery/
├── data/               # Ham veri seti (diabetes.csv)Harika bir fikir! GitHub profilinde "hareketli" bir etki yaratmak için Markdown'ın desteklediği HTML etiketlerini ve dinamik badge (rozet) servislerini kullanabiliriz.

İşte projeni bir üst seviyeye taşıyacak, görsel odaklı yeni **README.md** tasarımın:

---

# <p align="center">🏥 DiabetAltery: Veri Odaklı Diyabet Analizi</p>
<p align="center">
  <img src="[https://capsule-render.vercel.app/render?type=waving&color=auto&height=200&section=header&text=Diyabet%20Tahmin%20Modeli&fontSize=50&animation=fadeIn&fontAlignY=35](https://capsule-render.vercel.app/render?type=waving&color=auto&height=200&section=header&text=Diyabet%20Tahmin%20Modeli&fontSize=50&animation=fadeIn&fontAlignY=35)" width="100%" />
</p>

<p align="center">
  <img src="[https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)" />
  <img src="[https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)" />
  <img src="[https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)" />
  <img src="[https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)" />
</p>

## 📌 Proje Genel Bakışı
Bu çalışma, diyabet hastalığının erken teşhisi için makine öğrenmesi algoritmalarının performansını analiz eder[cite: 1]. Veri seti üzerinde kapsamlı temizlik, tıbbi literatüre uygun yeni öznitelik türetme (Feature Engineering) ve hiperparametre optimizasyonu süreçlerini kapsar[cite: 1].

## 🧪 Uygulanan Metodoloji
| Aşama | Açıklama | Kullanılan Teknik |
| :--- | :--- | :--- |
| **Veri Temizliği** | İmkansız 0 değerlerinin giderilmesi[cite: 1] | Medyan İmputasyonu |
| **Aykırı Değer** | Uç değerlerin sisteme zarar vermesini engelleme[cite: 1] | IQR (Interquartile Range) |
| **Öznitelik Mühendiliği** | Yeni anlamlı değişkenler türetme[cite: 1] | DSÖ BMI & Yaş Kategorileri |
| **Optimizasyon** | En iyi model parametrelerini bulma[cite: 1] | RandomizedSearchCV |

## 📊 Karşılaştırmalı Model Sonuçları
Proje kapsamında denenen modellerin başarı oranları aşağıda tablolanmıştır:

| Algoritma | Accuracy (Doğruluk) | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| K-Nearest Neighbors | %73 | 0.65 | 0.44 | 0.52 |
| Logistic Regression | %77 | 0.71 | 0.57 | 0.63 |
| Random Forest (Base) | %77 | 0.72 | 0.57 | 0.64 |
| **Random Forest (Optimized)** | **%79** | **0.74** | **0.62** | **0.67** |

> **Önemli Bulgular:** Yapılan optimizasyon çalışmaları sonucunda modelin AUC skoru **0.81'den 0.86'ya** yükseltilmiştir[cite: 1].

## 📁 Klasör Yapısı
```text
DiabetAltery/
├── data/               # Ham veri seti (diabetes.csv)[cite: 1]
├── notebooks/          # Analiz ve modelleme (diabetMachineHarika bir fikir! GitHub profilinde "hareketli" bir etki yaratmak için Markdown'ın desteklediği HTML etiketlerini ve dinamik badge (rozet) servislerini kullanabiliriz.
