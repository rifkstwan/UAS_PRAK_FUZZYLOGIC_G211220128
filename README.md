# UAS Fuzzy Logic - Gasal 2024/2025
Nama : Rifki Setiawan
NIM  : G.211.22.0128

Repositori ini berisi implementasi Python untuk dua kasus sistem fuzzy yang merupakan bagian dari Ujian Akhir Semester (UAS) mata kuliah Fuzzy Logic.

## 📋 Deskripsi Kasus

### Kasus A: Fuzzy Logic - Diagnosa Risiko Demam Berdarah (DBD)

Sistem fuzzy untuk mendiagnosa tingkat risiko Demam Berdarah Dengue (DBD) berdasarkan parameter klinis pasien.

**Input Variables:**
- Suhu Tubuh (°C)
- Jumlah Trombosit (10⁹/L)
- Jumlah Leukosit (10⁹/L)

**Output:**
- Tingkat Risiko: Rendah / Sedang / Tinggi

**Fuzzy Rules:**
1. Jika Suhu tinggi AND Trombosit rendah AND Leukosit rendah → Risiko = Tinggi
2. Jika Suhu demam AND Trombosit rendah → Risiko = Tinggi
3. Jika Suhu demam AND Trombosit normal → Risiko = Sedang
4. Jika Suhu normal AND Trombosit normal AND Leukosit normal → Risiko = Rendah
5. Jika Suhu tinggi AND Leukosit normal → Risiko = Sedang

### Kasus B: ANFIS - Prediksi Produksi Jagung

ANFIS (Adaptive Neuro-Fuzzy Inference System) untuk memprediksi produksi jagung agroindustri.

**Input Variables:**
- Kelembaban Tanah / soil_moisture (%)
- pH Tanah / soil_pH
- Suhu Rata-rata / avg_temp (°C)

**Output:**
- Prediksi Produksi (ton/ha)

**ANFIS Parameters:**
- Rule 1: p₁ = 0.0692, q₁ = 0.0461, r₁ = 0.00231
- Rule 2: p₂ = 0.0698, q₂ = 0.0390, r₂ = 0.00139
- Rule 3: p₃ = 0.0585, q₃ = 0.0183, r₃ = 0.00084
- Rule 4: p₄ = 0.0505, q₄ = 0.0318, r₄ = 0.00115

## 🚀 Cara Menjalankan

### Prerequisites

Pastikan Python 3.7+ sudah terinstall. Install dependencies:

