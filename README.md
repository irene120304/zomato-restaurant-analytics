# 🍽️ Zomato Restaurant Analytics & Market Insights (Bangalore)

> **Exploratory Data Analysis (EDA) and Business Intelligence** on 50,000+ restaurant records from Zomato Bangalore to identify culinary trends, pricing patterns, and factors driving high customer ratings.

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20Zomato-lightblue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🎯 Business & Analytical Objectives
Industri kuliner (F&B) di kota besar seperti Bangalore memiliki tingkat persaingan yang sangat ketat. Analisis ini bertujuan untuk:
1. **Data Cleaning & Wrangling:** Menangani data rating unstandardized (`4.1/5`, `NEW`, `-`), menangani missing values pada fitur masakan (`cuisines`) dan lokasi, serta mengonversi biaya makan (`approx_cost`) ke format numerik.
2. **Pricing & Affordability Analysis:** Memetakan distribusi estimasi biaya makan untuk 2 orang di berbagai kawasan kuliner.
3. **Cuisine & Rating Patterns:** Menganalisis korelasi antara jenis restoran, preferensi masakan, dan volume ulasan terhadap perolehan rating tinggi.
4. **Location Intelligence:** Menentukan area dengan konsentrasi restoran tertinggi dan peluang pasar baru.

---

## 📊 Key Insights
- **Top Locations:** Area seperti *Koramangala*, *BTM*, dan *Indiranagar* memiliki kepadatan restoran tertinggi sekaligus pusat aktivitas ulasan kuliner.
- **Cost vs Rating Trend:** Restoran dengan rentang harga menengah ke atas cenderung memperoleh rating lebih stabil dan ulasan lebih konsisten dibandingkan kategori budget murah.
- **Popular Cuisines:** Masakan *North Indian*, *Chinese*, dan *Fast Food* mendominasi pangsa pasar pilihan menu paling umum di kota tersebut.

---

## 🔍 Key Analytical Questions Explored
1. **Bagaimana distribusi rating restoran di Bangalore?**  
   Mayoritas restoran memiliki rating di kisaran 3.5 - 4.0, dengan pola ulasan tertinggi terkonsentrasi pada segmen kasual dan kafe.
2. **Kawasan mana yang memiliki konsentrasi restoran tertinggi?**  
   Area Koramangala dan BTM merupakan pusat kepadatan kompetisi kuliner tertinggi di Bangalore.
3. **Apakah biaya makan berdua berpengaruh langsung terhadap rating?**  
   Restoran dengan kategori harga menengah cenderung memiliki sentimen ulasan yang lebih stabil dibandingkan kategori budget ekstrem.
4. **Apa jenis masakan (cuisines) paling populer?**  
   North Indian, Chinese, dan Fast Food mendominasi pangsa pasar menu paling banyak ditawarkan.
   
---

## 🛠️ Tech Stack
- **Data Manipulation:** Python (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📁 Repository Structure
```
├── notebooks/
│
└── 01_zomato_eda_analytics.ipynb # Main Exploratory Data Analysis & Cleaning
├── data/ # Dataset folder (download from Kaggle)
├── outputs/figures/ # Saved statistical plots
├── requirements.txt # Project dependencies
└── README.md
```

---

## 🚀 How to Run Locally

```bash
# 1. Clone repository
git clone https://github.com/irene120304/semongko.git
cd semongko

# 2. Install dependencies
pip install -r requirements.txt

# 3. Download dataset
# Kunjungi Kaggle: https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants
# Unduh file zomato.csv dan simpan ke dalam folder data/

# 4. Jalankan notebook
jupyter notebook
