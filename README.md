# HR Data Analysis: Employee Performance & Retention Dashboard

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis data internal perusahaan yang mencakup total 1.020 karyawan. Analisis difokuskan pada evaluasi demografi usia talenta, pengelolaan anggaran gaji secara keseluruhan, tren rekrutmen tahunan, serta pemetaan performa kerja karyawan berdasarkan departemen, wilayah (region), dan kebijakan kerja jarak jauh (*Remote Work*).

## 🛠️ Tools Used
* **Microsoft Excel**: Data Quality Assessment (Data Profiling & Cleaning), Pivot Tables, Pivot Charts, Slicers, dan Interactive HR Dashboard.

## 📋 Scope of Work & Data Lifecycle

### 1. Pemeriksaan Data (Data Profiling)
Melakukan audit menyeluruh terhadap struktur dataset awal untuk mendeteksi potensi masalah kualitas data. Tahap ini mengidentifikasi adanya nilai kosong (*missing values*) pada kolom usia (*Age*), inkonsistensi format penulisan tanggal bergabung (*Join Date*), variasi format nomor telepon yang mencakup simbol tanda hubung, serta penggabungan teks informasi departemen dan wilayah dalam satu kolom yang sama.

### 2. Pembersihan Data (Data Cleaning)
Melakukan transformasi dan standarisasi data secara sistematis, yang meliputi:
* **Penanganan Data Kosong:** Mengisi sel kosong pada kolom usia (*Age*) menggunakan nilai median (30 tahun) agar distribusi data demografi talenta tetap seimbang dan akurat.
* **Pemisahan Kolom:** Memisahkan informasi teks yang sebelumnya tergabung menjadi kolom *Department* dan *Region* secara terpisah agar mudah dianalisis.
* **Standarisasi Format:** Menyamakan format penulisan tanggal (*Join Date*) serta membersihkan anomali karakter atau tanda hubung pada nomor telepon agar data bersih dan tervalidasi.

### 3. Eksplorasi Data (Data Exploration)
Menggunakan *Pivot Tables* untuk mengolah dan menganalisis ringkasan statistik dasar, meliputi:
* Penghitungan total keseluruhan karyawan, total anggaran pengeluaran gaji, rata-rata gaji global, dan rata-rata usia karyawan.
* Pemetaan jumlah karyawan serta sebaran alokasi gaji di setiap departemen (seperti Sales, DevOps, HR, Admin, Cloud Tech, dan Finance).
* Analisis korelasi antara kebijakan kerja jarak jauh (*Remote Work*) dengan tingkat pencapaian performa kerja karyawan.

### 4. Visualisasi Data & Interactive Dashboard
Menerjemahkan hasil analisis ke dalam bentuk visual yang interaktif dan dinamis menggunakan *Pivot Charts* dan *Slicers* (Filter Status, Department, dan Region). Dashboard ini dirancang secara profesional agar perekrut atau manajemen dapat dengan mudah membaca metrik bisnis dan menarik kesimpulan strategis secara cepat.

## ❓ Business Questions & Insights
* **Q1:** Bagaimana tren pertumbuhan rekrutmen talenta dan sebaran karyawan di tiap departemen?
  * *Insight:* Departemen DevOps dan Sales mendominasi jumlah staf terbanyak, dengan rekrutmen tahunan tertinggi tercatat pada tahun 2023.
* **Q2:** Departemen mana yang memiliki alokasi anggaran gaji terbesar dan bagaimana kontribusinya terhadap performa?
  * *Insight:* Departemen Sales memegang alokasi anggaran gaji tertinggi ($84,8 juta total perusahaan), yang sejalan dengan kontribusi performa kerja terbaik di perusahaan.
* **Q3:** Apakah sistem kerja jarak jauh (*Remote Work*) berdampak pada produktivitas?
  * *Insight:* Karyawan yang bekerja secara jarak jauh terbukti tetap produktif dan mencatatkan persentase nilai kerja *Excellent* yang tinggi dibandingkan karyawan reguler.
* **Q4:** Bagaimana demografi usia memengaruhi tingkat produktivitas kerja?
  * *Insight:* Kelompok usia muda (sekitar usia 30 tahun) mendominasi perolehan predikat performa kerja terbaik (*Good* dan *Excellent*).

## 📁 Project Files
* `Employee_Portofolio.xlsx` - File utama Excel yang mencakup laporan kualitas data (*Data Quality Report*), proses *cleaning*, *pivot tables*, hingga *Interactive HR Performance & Salary Dashboard*.
