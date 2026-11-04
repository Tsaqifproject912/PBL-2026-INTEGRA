# **WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce \- Problem Framing) \| SFIA BUSA L1 (*Business Analysis*), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief \- TPL-01)**

---

## **1\. Identifikasi Tim & Objek Proyek**

| Elemen Informasi | Rincian Identitas Kelompok & Mitra |
| :---- | :---- |
| **Nama Kelompok / Kelas** | \[ INTEGRA / B \] |
| **Phase Lead 2 (Frame \- M2)** | \[ Galang Maulana — 2600016070 \] |
| **Nama UMKM Mitra Lapangan** | \[ Tiny Laundry \] |
| **Pemilik / Kontak Mitra** | \[ Ibu Tiny \] |

---

## **2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari `WS03` untuk memisahkan antara **Gejala Permukaan (*Symptoms*)** dan **Akar Masalah Utama (*Root Cause*)** operasional bisnis mitra:

| No | Kategori Observasi | Gejala Permukaan (*Symptoms*) | Akar Masalah Operasional (*Root Cause*) | Bukti Kuantitatif (*Baseline Data*) |
| :---: | :---- | :---- | :---- | :---- |
| **1** | **Qris** | Tidak bisa menggunakan Qris. | mitra tidak ingin menggunakan qris dikarenakan pajak yang dikenakan, ucap mitra | Pernah menjadi pelanggan di mitra tersebut |
| **2** | **Pencatatan nota** | Pencatatan nota masih manual. | karena kurangnya pemahaman mitra terhadap mesin kasir digital | Hasil wawancara |
| **3** | **Rekapitulasi Keuangan** | Pemilik usaha tidak melakukan rekap | pemilik usaha merasa tidak memerlukan rekap karena langsung menggunakan hasil dari usaha tsb | Hasil wawancara |

---

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
*Petunjuk*: Hindari mendefinisikan masalah sebagai *"Mitra belum memiliki aplikasi Python/komputer"*. Definisikan dari hambatan bisnis nyata mitra\!

> **Rumusan Problem Statement Kelompok**:  
> *"Metode pembayaran masih hanya bisa menggunakan cash atau transfer di Tiny Laundry yang mana menyebabkan beberapa keluhan dari pelanggan ketika ingin melakukan transaksi, karena ada biaya admin ketika melakukan transfer. pencatatan nota pun masih manual karena kurangnya pemahaman mitra terhadap mesin kasir digital yang dimana membutuhkan waktu yang lebih lama. Dan juga pemilik tidak melakukan rekap keuangan tiap malam karena uang langsung masuk rekening, yang dimana ini menyebabkan tidak bisa menghitung keuntungan dan kerugian nya tiap hari."*

---

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (*Scope Creep*) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (*In-Scope*)** dan apa yang **Di Luar Cakupan (*Out-of-Scope*)**:

```
 ┌───────────────────────────────────────────┐
 │                    SYSTEM BOUNDARY (BATASAN SISTEM)                    │
 │                                                                        │
 │   [ IN-SCOPE: Fitur yang Akan Dibangun ]                               │
 │   1. Pencatatan transaksi kasir berbasis konsol (CLI).                 │
 │   2. Pengurangan stok otomatis setiap transaksi berhasil.              │
 │   3. Pencetakan ringkasan rekapitulasi harian untuk pemilik.           │
 │                                                                        │
 │─────────────────────────────────────────── │
 │                                                                        │
 │   [ OUT-OF-SCOPE: Di Luar Cakupan Proyek ]                             │
 │   1. Integrasi gateway pembayaran e-wallet / QRIS otomatis.            │
 │   2. Fitur penggajian karyawan / manajemen HRD.                        │
 │   3. Pemesanan stok otomatis ke supplier luar.                         │   └────────────────────────────────────────────┘
```

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| No | Modul / Fitur Sistem | Status Cakupan (*In-Scope / Out-of-Scope*) | Alasan Pertimbangan Kelayakan (O'Brien) |
| :---: | :---- | :---: | :---- |
| **1** | Pengadaan kode QRIS | **IN-SCOPE** | Di era serba digital ini konsumen terkadang lebih memilih menggunakan pembayaran melalui QRIS |
| **2** | pencatatan nota | **IN-SCOPE** | pencatatan nota yang masih menggunakan metode manual memakan cukup banyak waktu sehingga tidak efisien dan tidak ada backup data jika nota kertas hilang |
| **3** | rekapitulasi keuangan | **IN-SCOPE** | menurut kami rekapitulasi keuangan tetap diperlukan walaupun mitra merasa tidak memerlukannya supaya terdata jelas penghasilan yang masuk dan keluar |
| **4** | alat operasional  | **OUT-OF-SCOPE** | mitra saat ini hanya memiliki 1 mesin cuci |
| **5** | Multi-Branch / Banyak Cabang | **OUT-OF-SCOPE** | Mitra saat ini hanya memiliki 1 lokasi usaha operasional. |

---

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| Indikator Kinerja | Kondisi As-Is (Baseline) | Target To-Be (Expected) | Estimasi Persentase Peningkatan |
| :---- | :---: | :---: | :---: |
| **Qris** | otomatis langsung ke menu pembayaran | **1-2 menit/orang** | Peningkatan efisiensi **60%** |
| **Pencatatan nota & kelengkapan data** | mencatat nota kertas 2-3 menit/orang | **1-2 menit/orang** | Penghematan waktu **33.3%** |
| **Rekap Keuangan** | tidak melakukan rekapitulasi keuangan, akurasi 50% | **Akurasi \> 90%** | Penurunan tingkat kesalahan selisih penghasilan dan terjaminnya kelengkapan data |

---

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. *Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?*  
   * **Jawab**: Menurut kami permasalahan tersebut masih ada di dalam jangkauan kemampuan kami  
2. *Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?*  
   * **Jawab**: Kami belum meminta konfirmasi ke  pemilik mitra

### **B. Tanda Tangan Pengesahan Phase Lead 2**

```
Disusun oleh Phase Lead 2 (Frame): [ Galang Maulana — 2600016070 ]
Tanggal Penyusunan: [ Tanggal ]

Tanda Tangan Phase Lead 2: ____________________

Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
Catatan Dosen: __________________________________________________
```

