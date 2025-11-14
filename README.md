🚍 Analisis Data Perjalanan TransJakarta
Urban Mobility Data Analysis – Portfolio Project

Proyek ini bertujuan menganalisis data perjalanan TransJakarta untuk memahami pola mobilitas penumpang, rute populer, serta faktor yang memengaruhi kepadatan dan kualitas layanan. Dengan memanfaatkan data transaksi penumpang sebanyak 189.500 baris (April 2023), analisis ini memberikan insight untuk mendukung perencanaan transportasi publik yang lebih efisien dan berorientasi pada pengguna.

📌 Tujuan Proyek

Mengidentifikasi pola perjalanan berdasarkan waktu, usia, dan demografi.

Mengetahui halte dan rute dengan aktivitas tertinggi.

Menganalisis jam sibuk serta tren weekday vs weekend.

Memberikan rekomendasi untuk peningkatan kualitas layanan TransJakarta.

📂 Struktur Dataset

Dataset berisi 22 kolom, di antaranya:

transID – ID unik transaksi

payCardID, payCardBank, payCardSex, payCardBirthDate – informasi dasar pengguna

corridorID, corridorName – informasi rute

tapInStops / tapOutStops – titik naik dan turun

tapInTime / tapOutTime – waktu perjalanan

payAmount – tarif perjalanan

Koordinat halte – tap in & tap out latitude/longitude

Total: 189.500 baris data perjalanan penumpang.

🛠 Metodologi

Proyek ini diselesaikan dengan pendekatan CRISP-DM, meliputi:

Project Definition

Data Understanding

Data Preparation & Cleaning

Exploratory Data Analysis (EDA)

Insight Generation

Reporting & Recommendation

📊 Hasil Analisis & Insight
1. Demografi Penumpang

Dominan usia 30–39 tahun.

Usia 20–29 juga tinggi, sedangkan usia >50 cukup rendah.

2. Pola Gender

Penumpang laki-laki dan perempuan relatif seimbang
(≈ 53% vs 47%).

3. Aktivitas Halte

Halte dengan tap-in tertinggi: Penjaringan, BKN, dan Rusun Penjaringan.

Dominasi area permukiman dan akses LRT.

4. Rute Terpopuler

Penjaringan ↔ Rusun Penjaringan menjadi rute dengan volume tertinggi.

5. Jam Sibuk

Dua puncak:

06:00–08:00 (berangkat kerja/sekolah)

17:00–18:00 (pulang kerja/sekolah)

6. Tren Harian

Ridership stabil pada weekday.

Menurun drastis pada akhir pekan.

🚌 Rekomendasi

Optimalisasi Armada di Jam Sibuk
Tingkatkan frekuensi bus pada 06:00–08:00 dan 17:00–18:00.

Penguatan Layanan di Halte Padat
Atur ulang alur antrian dan kapasitas halte seperti Penjaringan & BKN.

Strategi Weekend Ridership
Buat program tarif khusus atau kolaborasi dengan destinasi wisata.

Segmentasi Berdasarkan Usia Pengguna
Fokuskan fasilitas seperti Wi-Fi & charging port untuk usia produktif (20–39).

Monitoring Rute Populer
Khususnya Penjaringan – Rusun Penjaringan untuk menghindari overload.

🧩 Tools & Libraries

Python

Pandas

NumPy

Matplotlib / Seaborn

Geopandas (opsional)

Jupyter Notebook

📁 Isi Repository
📦 transjakarta-analysis
 ┣ 📜 notebook.ipynb
 ┣ 📜 README.md
 ┣ 📂 data
 ┃ ┗ transjakarta_april2023.csv
 ┗ 📂 images
    ┗ charts & visualizations

🙌 Acknowledgment

Proyek ini dibuat sebagai bagian dari pembelajaran di Dibimbing.id, dan menjadi latihan penting dalam memahami data transportasi publik serta penerapannya untuk pengambilan keputusan.


<img src ="Dashboard_TJ.jpg">
