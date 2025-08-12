# Predictive Churn Model – IndoAgus Store

Proyek ini bertujuan untuk membangun **model prediksi churn pelanggan** di IndoAgus Store menggunakan teknik *machine learning*, sehingga tim dapat mengidentifikasi pelanggan yang berisiko tinggi untuk berhenti berbelanja dan mengambil langkah retensi yang tepat.

## 📌 Latar Belakang
Tingkat churn pelanggan yang tinggi dapat menyebabkan:
- Penurunan pendapatan.
- Peningkatan biaya akuisisi pelanggan baru.
- Berkurangnya loyalitas pelanggan.

Dengan memanfaatkan data historis transaksi dan perilaku pelanggan, IndoAgus Store dapat memprediksi potensi churn dan mengurangi biaya promosi yang terbuang.

## 🎯 Tujuan
1. Mengidentifikasi pelanggan berisiko churn.
2. Mengoptimalkan biaya promosi retensi.
3. Meningkatkan **Customer Lifetime Value (CLV)**.

## 🛠️ Analytical Approach
1. **Pengumpulan Data** – Data transaksi, interaksi pelanggan, dan profil demografi.
2. **Preprocessing** – Data cleaning, handling missing values, encoding, dan feature scaling.
3. **Feature Engineering** – Menambahkan fitur baru yang relevan (frekuensi pembelian, rata-rata nilai transaksi, waktu sejak pembelian terakhir).
4. **Modeling** – Menggunakan algoritma seperti Logistic Regression, Random Forest, dan XGBoost.
5. **Evaluasi** – Menggunakan metrik seperti Accuracy, Precision, Recall, F1-Score, dan ROC-AUC.

## 📊 Main Evaluation Metrics
- **Akurasi**
- **Precision / Recall**
- **F1-Score**
- **ROC-AUC**
- *Confusion Matrix*

## 📈 Hasil Simulasi
### Tanpa Model:
- **Total Biaya**: 6.310 USD  
- **Churn yang ditemukan**: 108 orang  
- **Biaya terbuang**: 5.230 USD

### Dengan Model:
- **Total Biaya**: 1.150 USD  
- **Churn yang ditemukan**: 86 orang  
- **Biaya terbuang**: 1.170 USD  
- **Penghematan**: **4.060 USD**

## 💡 Insight Bisnis
- Faktor terbesar penyebab churn: frekuensi pembelian menurun, nilai transaksi kecil, dan tidak ada pembelian dalam periode tertentu.
- Segmen prioritas: pelanggan dengan nilai transaksi tinggi tetapi aktivitas menurun dalam 3 bulan terakhir.

## 📌 Rekomendasi
- Kirimkan promo khusus kepada pelanggan dengan skor churn tinggi.
- Gunakan kanal komunikasi yang paling efektif (WA, Email).
- Lakukan retraining model setiap 3–6 bulan.

## ⚠️ Limitations & Challenges
- Ketergantungan pada kualitas dan kelengkapan data.
- Perubahan tren perilaku pelanggan.
- Keterbatasan sumber daya tim untuk analisis lanjutan.

## 🚀 Next Steps
- Integrasi real-time scoring ke sistem CRM.
- Uji coba A/B untuk strategi retensi.
- Ekspansi model ke kategori produk lain.

---

