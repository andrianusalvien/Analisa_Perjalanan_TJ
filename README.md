# 🚍 Analisis Data Perjalanan TransJakarta  
*Urban Mobility Insight using Data Analytics*

Proyek ini menganalisis **189.500 transaksi perjalanan TransJakarta (April 2023)** untuk memahami pola mobilitas penumpang, rute populer, jam sibuk, serta karakteristik pengguna. Hasil analisis digunakan untuk memberikan rekomendasi peningkatan layanan transportasi publik di Jakarta.

---

## 📌 Project Objectives
- Mengidentifikasi pola perjalanan berdasarkan usia, gender, dan waktu.
- Mengetahui halte dan rute dengan aktivitas tertinggi.
- Menganalisis jam sibuk dan perbedaan weekday–weekend.
- Memberikan rekomendasi berbasis data untuk peningkatan kualitas layanan.

---

## 📂 Dataset Overview
- **Total Rows:** 189,500  
- **Total Columns:** 22  
- **Data Source:** Simulasi data transaksi perjalanan TransJakarta (April 2023)  
- **Key Fields:**  
  - `transID`  
  - `corridorName`  
  - `tapInStopsName`, `tapOutStopsName`  
  - `tapInTime`, `tapOutTime`  
  - `payCardGender`, `payCardBirthDate`  
  - `payAmount`  

---

## 🛠️ Tools & Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📊 Key Findings
### **1. Demografi Pengguna**
- Pengguna didominasi usia **30–39 tahun**.  
- Usia >50 relatif kecil jumlahnya.

### **2. Pola Gender**
- Laki-laki 53%  
- Perempuan 47%

### **3. Halte dengan Tap-In Tertinggi**
- Penjaringan  
- BKN  
- Rusun Penjaringan

### **4. Rute Paling Sibuk**
- Penjaringan → Rusun Penjaringan  
- Rusun Penjaringan → Penjaringan

### **5. Jam Sibuk**
- **06:00–08:00** dan **17:00–18:00**

### **6. Perbedaan Weekday vs Weekend**
- Tinggi pada Senin–Jumat  
- Turun signifikan pada Sabtu–Minggu

---

## 🚌 Recommendations
- Tambah frekuensi bus pada jam sibuk.
- Optimalkan manajemen antrian di halte padat.
- Buat program promo untuk meningkatkan ridership weekend.
- Fokuskan fasilitas pendukung untuk usia produktif (20–39).
- Monitor kapasitas rute populer untuk mencegah overload.

---

## 📸 Visual Preview


<img src ="Dashboard_TJ.jpg">
