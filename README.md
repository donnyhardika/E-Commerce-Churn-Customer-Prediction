<h1> [E-Commerce Customer Churn Prediction] </h1>

## 1. Project Overview
Customer retention merupakan salah satu faktor terpenting dalam industri e-commerce. Biaya memperoleh pelanggan baru dapat mencapai 5–7 kali lebih besar dibandingkan mempertahankan pelanggan yang sudah ada. Oleh karena itu, kemampuan memprediksi pelanggan yang berpotensi melakukan churn menjadi sangat penting agar perusahaan dapat melakukan tindakan preventif. Project ini membangun model **Machine Learning Classification** untuk memprediksi kemungkinan pelanggan akan melakukan churn berdasarkan karakteristik transaksi, perilaku belanja, dan informasi pelanggan.

Key Objectives:
- Objective 1: Membangun model klasifikasi untuk memprediksi customer churn.
- Objective 2: Menghasilkan daftar pelanggan berisiko tinggi sebagai prioritas program retensi.
- Objective 3: Mengidentifikasi faktor utama penyebab churn.
- Objective 4: Memberikan rekomendasi bisnis berbasis data untuk meningkatkan customer retention.

## 2. Data Sources
data_ecommerce_customer_churn - Description of dataset (informasi pelanggan, aktivitas transaksi, dan status churn.)

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, Skicit-learn, Imbalanced-learn)
- Visualization: (Matplotlib, Seaborn, Plotly)
- Version Control: Git
- Others: Jupyter Notebook, Github
- Machine Learning: Logistic Regression, Decision Tree, Random Forest, XGBoost, Hyperparameter Tuning, Cross Validation,     Pipeline, Feature Engineering)
- Evaluation Metrics: (Recall, Precision, F1-score, ROC-AUC, Confusion Metrix)

## 4. Project Structure
```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description,
                          "capstone3_ecommerce_churn.ipynb"
│                         
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with pip freeze > requirements.txt
│
└── src                <- Source code for use in this project.
```

## 5. Summary of Finding
### 5.1 Business Insight
Beberapa karakteristik pelanggan dengan risiko churn tinggi antara lain:
- Customer dengan masa berlangganan (Tenure) yang rendah.
- Pelanggan dengan tingkat kepuasan rendah.
- Pelanggan yang pernah melakukan komplain.
- Frekuensi transaksi yang rendah.
- Cashback yang diterima relatif kecil.
- Jarak gudang ke pelanggan yang lebih jauh.

### 5.2 Actionable Recommendation
Beberapa rekomendasi bisnis yang dapat diterapkan:
- Menjalankan program retensi khusus bagi pelanggan dengan skor risiko churn tinggi.
- Memberikan promo atau cashback personalisasi kepada pelanggan berisiko.
- Meningkatkan kualitas layanan pelanggan terutama pada pelanggan yang pernah melakukan komplain.
- Mengoptimalkan proses pengiriman untuk pelanggan dengan warehouse distance yang tinggi.
- Mengimplementasikan model prediksi churn secara berkala sebagai bagian dari sistem Customer Relationship Management (CRM).

## 6. Contact
- Name: Donny, Hane
- Email: donny.hardika@gmail.com, hanededewa228@gmail.com
- Linkedin: www.linkedin.com/in/donny-aditya-7a32013a8, www.linkedin.com/in/hane-andreanu-subiyakto-66092b25a

