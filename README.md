# 📊 Cohort Retention Analysis: Looker E-Commerce

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis **retensi pelanggan dari waktu ke waktu** menggunakan pendekatan cohort analysis terhadap data pengguna dari platform e-commerce fiktif bernama **The Looker**. Proyek ini dilakukan oleh tim dalam rangka portofolio analisis data pada program pembelajaran.

## 🎯 Tujuan Proyek

- Memahami pola **retensi dan churn** pelanggan berdasarkan waktu pertama kali mereka melakukan transaksi.
- Mengidentifikasi **segmentasi pelanggan yang loyal** dan yang cenderung churn.
- Menggali tren penjualan serta **rata-rata produk yang dikembalikan** oleh pelanggan dari waktu ke waktu.
- Memberikan **rekomendasi berbasis data** untuk meningkatkan loyalitas dan efektivitas strategi pemasaran.

## 🗂️ Dataset

Dataset mencakup informasi seperti:
- `User ID` — Identitas unik pengguna
- `Order ID` — Identitas unik pesanan
- `Created At` — Tanggal pembuatan pesanan
- `Status` — Status pesanan (misalnya, dikirim, dikembalikan)
- `Country` — Lokasi pengguna

## 🔍 Metodologi

1. **Cohort Definition**  
   Pengguna dikelompokkan berdasarkan semester saat mereka pertama kali aktif (misalnya 2019-S2, 2020-S1).

2. **Tracking Aktivitas**  
   Aktivitas pengguna dilacak tiap semester untuk menghitung jarak waktu sejak pertama kali aktif (`semester_distance`).

3. **Perhitungan Retensi**  
   Menghitung persentase pengguna yang masih aktif pada semester-semester berikutnya.

4. **Visualisasi**  
   - Heatmap retensi antar semester
   - Tren pengguna dan order
   - Tingkat pengembalian barang
   - Perbandingan retensi antar negara (AS, Brasil, China)

## 📈 Hasil Utama

- 📉 **Tingkat retensi pelanggan secara umum menurun seiring waktu**, dengan hanya sekitar **9% pengguna melakukan pembelian ulang**.
- 📦 **Jumlah produk yang dikembalikan meningkat drastis** terutama setelah semester 2021-S2.
- 🌍 **Negara seperti China menunjukkan retensi paling stabil**, sementara **Brasil mencatat performa terendah**.
- 📊 **Tren jumlah pengguna dan order meningkat**, namun tidak berbanding lurus dengan retensi.

## 💡 Rekomendasi

1. 🛍️ **Diskon pembelian kedua untuk pengguna baru**  
   Meningkatkan kemungkinan pembelian ulang di awal siklus pelanggan.

2. 🎁 **Penawaran eksklusif untuk pelanggan loyal**  
   Meningkatkan nilai seumur hidup pelanggan (CLV) dengan insentif yang relevan.

3. 📣 **Kampanye promosi emosional dan interaktif**  
   Membangun koneksi antara pelanggan dan brand guna memperkuat loyalitas jangka panjang.

---

## 👨‍💻 Tim Pengembang

Ahmad Faik Setiawan  
Ditya Ayu Anjani  
Sarah Zeta Huwaidah  
