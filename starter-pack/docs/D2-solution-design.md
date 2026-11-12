# D2 — System & Solution Design

**Project**: Digital Problem Framing Mini Project — [Tini Laundry]
**Tim**: [Tsaqif Naafi Ghazalah,Galang Maulana,Muhammad Deryl Vezel] | **Tanggal**: [11/11/2026] | **Versi**: [v1.0]
**Template**: TPL-02

> **Petunjuk**: Hapus teks dalam `[...]` setelah diisi.
> Worksheet terkait: WS05, WS06, WS07

---

## 1. Daftar Kebutuhan (User Story)

| # | User Story | Prioritas |
|---|---|---|
| 1 | Sebagai Pemilik Usaha, saya ingin Melihat ringkasan rekapitulasi harian total pendapatan dan pengeluaran usaha secara otomatis sehingga Pemilik dapat mengetahui tingkat keuntungan dan kerugian harian dengan akurasi > 90% tanpa perlu menghitung nota fisik manual setiap malam | Tinggi |
| 2 | Sebagai Pelanggan, Saya ingin Melakukan dan memproses pembayaran menggunakan metode QRIS secara instan sehingga Pelanggan dapat bertransaksi dengan praktis tanpa terbebani biaya admin transfer bank dan efisiensi transaksi meningkat hingga 60% | Rendah |
| 3 | Sebagai  Kasir, saya ingin Mencatat nota transaksi transaksi laundry secara digital melalui aplikasi kasir Sehingga Waktu pencatatan transaksi berkurang menjadi 1–2 menit per orang dan tidak ada risiko data hilang akibat nota kertas terselip atau rusak | Sedang |
| 4 | Sebagai Pemilik Usaha, saya ingin mencatat setiap pemasukan dari transaksi laundry sehingga seluruh pendapatan usaha dapat terdokumentasi dengan baik. | Tinggi |
| 5 | Sebagai Pemilik Usaha, saya ingin melihat laporan rekapitulasi keuangan berdasarkan periode harian, mingguan, dan bulanan sehingga dapat memantau perkembangan keuangan usaha. | Tinggi|

## 2. Kriteria Penerimaan

| # | Kriteria Penerimaan (terukur & dapat diuji) |
|---|---|
| 1 | Sistem dapat menampilkan hasil perhitungan rekapitulasi dalam waktu maksimal 3 detik setelah pengguna memilih periode laporan. |
| 2 | Sistem dapat menampilkan data transaksi yang telah dicatat dan memastikan tidak ada data yang hilang setelah disimpan.|
| 3 | Sistem dapat menyimpan data pemasukan dan pengeluaran serta menampilkan totalnya secara otomatis. |
| 4 | Sistem dapat menghitung keuntungan bersih dengan rumus total pemasukan dikurangi total pengeluaran secara akurat.|
| 5 | Sistem dapat menampilkan rekapitulasi keuangan berdasarkan periode harian, mingguan, dan bulanan.|

## 3. Success Metrics

| Metrik | Baseline (Sekarang) | Target | Cara Mengukur |
|---|---|---|---|
| [Kelengkapan pencatatan pemasukan] | [Belum tercatat secara terstruktur] | [100% transaksi tercatat] | [Membandingkan transaksi aktual dengan data dalam sistem] |
| [Keakuratan perhitungan keuntungan] | [Belum dihitung secara rutin] | [100% sesuai perhitungan manual berdasarkan data yang sama] | [Membandingkan hasil sistem dengan perhitungan manual] |
| [Waktu rekapitulasi keuangan] | [Belum memiliki proses rekapitulasi rutin] | [Maksimal 3 menit] | [Mengukur waktu yang dibutuhkan untuk menghasilkan laporan] |
| [Ketersediaan laporan keuangan] | [Belum tersedia secara terstruktur] | [Tersedia laporan harian, mingguan, dan bulanan] | [Menguji fitur laporan berdasarkan periode yang dipilih] |

## 4. Desain Solusi

### 4.1 Konsep Solusi (ringkasan)

_[Prototipe yang dikembangkan berupa sistem pencatatan dan rekapitulasi keuangan sederhana berbasis digital untuk membantu Tini Laundry mengatasi permasalahan belum adanya pencatatan dan rekapitulasi pendapatan secara rutin. Sistem ini menyediakan fitur pencatatan pemasukan dari transaksi laundry dan pengeluaran operasional, perhitungan keuntungan secara otomatis, serta penyajian laporan keuangan berdasarkan periode harian, mingguan, dan bulanan. Dengan adanya prototipe ini, pemilik usaha diharapkan dapat memantau kondisi keuangan secara lebih mudah, akurat, dan terstruktur tanpa harus melakukan perhitungan secara manual, sehingga dapat mendukung pengambilan keputusan dalam pengelolaan usaha.]_

### 4.2 Peta Komponen (IPO)

```
Input  ──▶  Proses  ──▶  Output
  │                           │
  └───── Data/Penyimpanan ────┘
```

- **Input**: [data yang masuk berupa jumlah transaksi pelanggan, tanggal, jumlah uang yang diterima]
- **Proses**: [sistem mengumpulkan data yang sudah dikumpulkan kemudian mengolahnya sesuai dengan kebutuhan pemilik usaha]
- **Output**: [data matang berupa pemasukan dan pengeluaran per bulan, serta berapa keuntungan yang didapat]
- **Data/Penyimpanan**: [data disimpan di perangkat milik pelaku usaha, mis. file CSV]

### 4.3 Flowchart & Pseudocode

_[Tempel flowchart di `assets/` dan tulis pseudocode di bawah]_

```
[PSEUDOCODE]
```

## 5. Hasil Validasi Pemilik Usaha

- **Tanggal validasi**: [11/11/2026]
- **Feedback pemilik**: [Menyetujui dan menyanggupi]
- **Perubahan setelah validasi**: [...]

---

**Status**: ⬜ Draf → ⬜ Review Tim → ⬜ Validasi Pemilik → ⬜ Final (GATE 1)