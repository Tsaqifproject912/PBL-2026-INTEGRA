# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 3\)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate \- Problem Framing) & S-03.1 (Intermediate \- Pemetaan SI)** \| **SFIA BUSA L1, REQM L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design \- TPL-02)**

---

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

* **Nama Kelompok**: Tini Londry (INTEGRA)  
* **Objek UMKM Mitra**: Laundry   
* **Phase Lead 3 (Define)**: Muhammad Raihan Ibnu Rafi \- 2615026093  
* **Anggota Tim**:  
  1\. Tsaqif Naafi Ghazalah \- 2611016007  
  2\. Muhammad Deryl Vezel \- 2600016084  
  3\. Galang Maulana \- 2600016070

---

### **2\. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap *Systems Analysis*, fokus utama tim adalah menentukan **APA (*What*)** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (*How*)** sistem dibangun secara teknis (Marakas & O'Brien, 2013).

* **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:  
  \$\$\\text{"Sebagai \[Peran Pengguna\], Saya ingin \[Kemampuan/Fitur\], Sehingga \[Manfaat Bisnis Nyata\]"}\$\$  
* **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

---

### **3\. Workspace A: Formulasi User Story Fungsional**

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Pencatatan Nota DIgital)**

* **Sebagai (*As a*)**: Kasir  
* **Saya ingin (*I want to*)**: Mencatat nota transaksi transaksi laundry secara digital melalui aplikasi kasir  
* **Sehingga (*So that*)**: Waktu pencatatan transaksi berkurang menjadi 1–2 menit per orang dan tidak ada risiko data hilang akibat nota kertas terselip atau rusak

#### **User Story 2 (Pengadaan & Metode QRIS)**

* **Sebagai (*As a*)**: Pelanggan  
* **Saya ingin (*I want to*)**: Melakukan dan memproses pembayaran menggunakan metode QRIS secara instan  
* **Sehingga (*So that*)**: Pelanggan dapat bertransaksi dengan praktis tanpa terbebani biaya admin transfer bank dan efisiensi transaksi meningkat hingga 60%

#### **User Story 3 (Rekapitulasi Keuangan Harian)**

* **Sebagai (*As a*)**: Pemilik Usaha  
* **Saya ingin (*I want to*)**: Melihat ringkasan rekapitulasi harian total pendapatan dan pengeluaran usaha secara otomatis  
* **Sehingga (*So that*)**: Pemilik dapat mengetahui tingkat keuntungan dan kerugian harian dengan akurasi \> 90% tanpa perlu menghitung nota fisik manual setiap malam

---

### **4\. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk **User Story 3** (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)**

* **Diberikan (*Given*)**: Pemilik usaha berada di halaman utama aplikasi dan seluruh data transaksi penjualan serta pengeluaran harian telah tercatat dalam sistem.   
* **Ketika (*When*)**: Pemilik usaha memilih menu rekapitulasi keuangan dan menentukan tanggal laporan yang ingin ditampilkan.   
* **Maka (*Then*)**: Sistem secara otomatis menampilkan ringkasan total pendapatan, total pengeluaran, serta hasil perhitungan keuntungan atau kerugian berdasarkan data transaksi pada tanggal yang dipilih. 

#### **Skenario 1B: Penanganan Pembayaran Kurang / Eror (Exception Path)**

* **Diberikan (*Given*)**: Pemilik usaha berada di halaman rekapitulasi keuangan dan ingin melihat laporan keuangan harian berdasarkan tanggal tertentu.   
* **Ketika (*When*)**: Pemilik usaha memilih tanggal yang diinginkan, tetapi terdapat data transaksi atau pengeluaran yang belum tercatat, atau sistem mengalami kegagalan dalam memuat data laporan.   
* **Maka (*Then*)**: Sistem menampilkan notifikasi bahwa data keuangan belum lengkap atau laporan gagal dimuat, memberikan informasi mengenai data yang bermasalah, serta meminta pemilik usaha melengkapi data atau mencoba memuat ulang laporan sebelum hasil rekapitulasi digunakan. 

---

### **5\. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

* **Tanggal Validasi**:7 November 2026  
* **Narahubung Mitra**: Ibu Tini (Pemilik)  
* **Hasil Konfirmasi User Story**:  
  \[ \] Seluruh User Story disetujui mitra  
  \[ \] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):


---

---

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

* **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan skenario *Given-When-Then*? Tidak  
  *(Jika Ya, wajib melampirkan formulir **TPL-07: AI Usage Disclosure & Verification Note**)*.

**Tanda Tangan Tim & Pengesahan Dosen**:

* **Phase Lead 3**: Muhammad Raihan Ibnu Rafi \- 2615016093 (Tanggal:7 November 2026\)  
* **Dosen Coach**: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ (Tanggal: \_\_\_\_\_\_\_\_\_\_)  \[ \] Approved

| `Muhammad Raihan Ibnu Rafi` |
| :---- |
| ![][image1] |

[image1]: <data:image/png;base64,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>