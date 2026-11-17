# 🚕⚡ Carbon Emission Analysis and NYC Taxi Electrification Strategy

Analisis emisi karbon dan perumusan strategi elektrifikasi armada taksi serta *For-Hire Vehicles* (FHV) di bawah regulasi **New York City Taxi and Limousine Commission (NYC TLC)**.

---

## 📋 Ringkasan Eksekutif

New York City Taxi and Limousine Commission (NYC TLC) merupakan lembaga pemerintah yang bertanggung jawab atas regulasi dan pengawasan operasional taksi serta *for-hire vehicles* (FHV) di Kota New York, termasuk pengawasan aspek keselamatan dan emisi kendaraan.

Proyek ini bertujuan untuk mengevaluasi jejak karbon operasional armada taksi NYC saat ini dan menyusun strategi transisi menuju kendaraan listrik (*Electric Vehicles* / EV) yang berbasis data guna mendukung target pengurangan emisi kota.

---

## 🎯 Tujuan Proyek

- **Kuantifikasi Emisi Karbon:** Menghitung estimasi emisi $\text{CO}_2$ dari operasional perjalanan taksi dan FHV berdasarkan data perjalanan NYC TLC.
- **Identifikasi Pola Operasional:** Menganalisis distribusi jarak tempuh, waktu puncak operasional, serta zona dengan konsentrasi emisi tertinggi (seperti Manhattan, bandara JFK, dan LaGuardia).
- **Strategi Elektrifikasi:** Memberikan rekomendasi strategis berbasis data terkait prioritas elektrifikasi armada, kebutuhan infrastruktur pengisian daya (*charging station*), dan potensi reduksi emisi.

---

## 📂 Struktur Repositori

```text
├── data/                   # Dataset mentah dan hasil pemrosesan (NYC TLC Trip Records)
├── notebooks/              # Jupyter Notebook analisis utama (.ipynb)
├── src/                    # Skrip pembersihan data, kalkulasi emisi, dan visualisasi
├── assets/                 # Grafik, peta, dan gambar pendukung dokumentasi
└── README.md               # Dokumentasi proyek
