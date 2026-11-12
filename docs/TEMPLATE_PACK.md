# Template Pack
Tags: #type/template #domain/pbl #pbl/level-1
Level : 1
Semester : 1
Version : Draft v2.0
Last Updated : 2026-09-19
Related Files:
- `project_guide_level_1`
- [WORKSHEET_BOOK.md](WORKSHEET_BOOK.md)
- `instructor_guide`
- `individual_competency_passport`
- `learning_spine`

---

# Petunjuk Penggunaan
- Template berikut adalah **dokumen penyerahan (submission documents)** untuk **Core Learning Artifacts D1–D4** dan **Supporting Evidence**.
- Bukan worksheet — pengerjaan analisis dilakukan di [WORKSHEET_BOOK.md](WORKSHEET_BOOK.md); template ini untuk menyajikan hasil akhir secara profesional.
- Merujuk `revision_note_1.md`: hanya **4 core artifacts** (D1–D4) yang menjadi deliverable besar; AI disclosure, decision log, meeting log, peer assessment, LinkedIn menjadi **supporting evidence** (lampiran), bukan dokumen berdiri sendiri.
- Salin template sesuai kebutuhan, isi bagian bertanda `[...]`, lalu hapus bagian panduan.
- Standar profesional: jelas, ringkas, mudah dipahami (SFIA ICPM L2).

---

# CORE LEARNING ARTIFACTS

## TPL-01 — Template Problem Brief (D1)
*Dipenuhi dari hasil WS02–WS04.*

## Problem Brief
**Project**: Digital Problem Framing Mini Project — [Tini laundry]
**Tim**: [Tsaqif Naafi Ghazalah, Galang Maulana, Muhammad Deryl Vezel, Muhammad Raihan Ibnu Rafi] | **Tanggal**: [14/10/2026] | **Versi**: [v1.0]

### 1. User / Context
- Nama unit usaha / organisasi: [tini laundry]
- Jenis usaha / layanan: [laundry]
- Lokasi: [Tamanan, Bantul]
- Deskripsi operasional: [jasa cuci baju, pelanggan dan penyedia jasa, Beroperasi dari pukul 08.00 - 21.00]
- Narahubung / pemilik: [ibu Watini, Pemilik, 089654609751]

### 2. Observed Situation (Situasi yang Diamati)
- Fenomena yang diamati di lapangan: [pemilik usaha belum tidak melakukan rekap pendapatan rutin sehingga tidak mengetahui berapa keuntungan yang didapat]

### 3. Evidence (Bukti)
- Data kuantitatif pendukung (indikator, nilai/baseline, sumber data, tanggal):
  | Indikator | Nilai/Baseline | Sumber Data | Tanggal |
  |---|---|---|---|
  | [mis. waktu layanan rata-rata] | [3-5 menit/orang] | [observasi dan wawancara] | [10/11] |
- Kutipan observasi/wawancara kunci: ["Disini sudah tidak ada karyawan mas, jadinya kami tidak lagi menghitung pendapatan perminggu]

### 4. Insight
- Pemahaman mengapa masalah ini terjadi: [karna pemilik usaha merasa uang yang didapatnya akan berputar saja disekitar operasional dan tidak ada uang yang harus dibagi kepada karyawan]

### 5. Problem Statement
- Pernyataan masalah yang jelas (bukan solusi): [rekap pendapatan adalah hal yang sangat penting, sehingga pemilik usaha bisa mengukur apakah bisnisnya mengalami kerugian atau mendapatkan keuntungan. jika tidak melakukan rekap, keuntungan maupun kerugian tidak bisa terdeteksi]
- Pihak yang terdampak & keparahan: [pelaku usaha & sedang]

### 6. Impact
- Dampak bila masalah tidak diselesaikan: [pelaku usaha tidak bisa memastikan apakah usahanya mengalami kerugian atau mendapatkan keuntungan]

### 7. Scope
- Diselesaikan dalam proyek ini: [Membantu mitra memahami pentingnya rekapitulasi pendapatan serta merancang sistem pencatatan dan rekapitulasi keuangan sederhana yang dapat membantu mitra mencatat pemasukan, pengeluaran, dan menghitung keuntungan usaha secara lebih terstruktur]

### 8. Non-Scope
- Tidak diselesaikan (dan alasan): [Pengelolaan laporan keuangan secara profesional dan integrasi dengan sistem akuntansi berskala besar. Hal ini karena proyek kami berfokus pada penyediaan solusi sederhana yang sesuai dengan kebutuhan dan kemampuan operasional mitra]

### 9. Success Metric
- Metrik yang menunjukkan masalah teratasi: [Kelengkapan pencatatan pemasukan, Ketersediaan laporan keuangan]

### 10. Daftar Rujukan / Bukti
- [Observasi lapangan tanggal 11/11], [Wawancara pemilik tanggal 11/11], [Dokumen pendukung]

---

## TPL-02 — Template System & Solution Design (D2)
*Dipenuhi dari hasil WS05–WS08.*

## System & Solution Design
**Project**: Digital Problem Framing Mini Project — [Tini Laundry]
**Tim**: [Tsaqif Naafi Ghazalah, Galang Maulana, Muhammad Deryl Vezel, Muhammad Raihan Ibnu Rafi] | **Tanggal**: [11/11/2026] | **Versi**: [v1.0]

### 1. User
- Pengguna utama solusi & yang terdampak: [...]

### 2. User Story
| # | User Story | Prioritas (Tinggi/Sedang/Rendah) |
|---|---|---|
| 1 | Sebagai Pemilik Usaha, saya ingin Melihat ringkasan rekapitulasi harian total pendapatan dan pengeluaran usaha secara otomatis sehingga Pemilik dapat mengetahui tingkat keuntungan dan kerugian harian dengan akurasi > 90% tanpa perlu menghitung nota fisik manual setiap malam | tinggi |
| 2 | Sebagai Pemilik Usaha, saya ingin melihat laporan rekapitulasi keuangan berdasarkan periode harian, mingguan, dan bulanan sehingga dapat memantau perkembangan keuangan usaha. | tinggi |

### 3. Requirements
- Daftar kebutuhan yang diturunkan dari D1: [Sebagai Pemilik Usaha, saya ingin melihat laporan rekapitulasi keuangan berdasarkan periode harian, mingguan, dan bulanan sehingga dapat memantau perkembangan keuangan usaha.]

### 4. Acceptance Criteria
| # | Kriteria Penerimaan (terukur & dapat diuji) |
|---|---|
| 1 | Sistem dapat menghitung keuntungan bersih dengan rumus total pemasukan dikurangi total pengeluaran secara akurat. |
| 2 | Sistem dapat menampilkan rekapitulasi keuangan berdasarkan periode harian, mingguan, dan bulanan. |

### 5. Success Metric
| Metrik | Baseline | Target | Cara Mengukur |
|---|---|---|---|
| [Keakuratan perhitungan keuntungan] | [Belum dihitung secara rutin] | [100% sesuai perhitungan manual berdasarkan data yang sama] | [Membandingkan hasil sistem dengan perhitungan manual] |
| [Ketersediaan laporan keuangan] | [Belum tersedia secara terstruktur] | [Tersedia laporan harian, mingguan, dan bulanan] | [Menguji fitur laporan berdasarkan periode yang dipilih] |

### 6. Input-Process-Output (IPO)
- Input: data yang masuk berupa jumlah transaksi pelanggan, tanggal, jumlah uang yang diterima
- Proses: sistem mengumpulkan data yang sudah dikumpulkan kemudian mengolahnya sesuai dengan kebutuhan pemilik usaha
- Output: data matang berupa pemasukan dan pengeluaran per bulan, serta berapa keuntungan yang didapat

### 7. Data
- Data yang disimpan & sumbernya: [data transaksi keuangan yang bersumger dari transaksi pelanggan]

### 8. Flowchart
[Gambar/teks sederhana: mulai → proses → keputusan → selesai]

### 9. Pseudocode
[Pseudocode singkat untuk setiap bagian utama]

### 10. Solution Concept
- Konsep solusi: bagaimana kebutuhan dijawab solusi & peta komponen SI (proses-data-aplikasi-infrastruktur).

### 11. Hasil Validasi Pemilik Usaha
- Tanggal validasi: [11/11/2026] | Feedback: [menyetujui] | Perubahan setelah validasi: [...]

---

## TPL-03 — Template Tested Solution Prototype (D3)
*Dipenuhi dari hasil WS07, WS09–WS13.*

## Tested Solution Prototype
**Project**: Digital Problem Framing Mini Project — [tini laundry]
**Tim**: [Tsaqif Naafi Ghazalah, Galang Maulana, Muhammad Deryl Vezel, Muhammad Raihan Ibnu Rafi] | **Tanggal**: [DD/MM/YYYY] | **Versi**: [v1.0]

### 1. Ringkasan Solusi
- Masalah yang diselesaikan: [...]
- Bentuk prototipe: [konsol / menu]
- Alur utama (input → proses → output): [...]

### 2. Working Prototype & Source Code
- Lokasi penyimpanan kode: [...]
- Cara menjalankan: `python src/main.py`
- Catatan struktur kode (fungsi, variabel utama): [...]

### 3. Test Cases & Test Results
| # | Kasus Uji | Input | Output Diharapkan | Output Aktual | Status | Perbaikan |
|---|---|---|---|---|---|---|
| 1 | ... | ... | ... | ... | Lulus/Gagal | ... |

### 4. User / Client Validation
- Tanggal validasi pemilik: [DD/MM/YYYY]
- Hasil validasi kriteria penerimaan: [...]
- Masukan pemilik & yang diubah setelahnya: [...]

### 5. Improvement
- Perbaikan yang dilakukan selama Build–Test: [...]

### 6. Limitation
- Keterbatasan prototipe & pengembangan semester berikutnya: [...]

### 7. Catatan Code Walkthrough
- Nama pengembang yang menjelaskan: [...]
- Bagian yang dibantu AI & penjelasan manual: [...]

---

## TPL-04 — Template Reflection & Portfolio (D4)
*Dipenuhi dari hasil WS01, WS14–WS16.*

## Reflection & Portfolio
**Project**: Digital Problem Framing Mini Project — [Nama Unit Usaha]
**Tim**: [Nama anggota] | **Periode**: [Minggu 1–16]

### 1. Project Summary
- Ringkasan proyek (masalah, solusi, bukti, dampak) — dapat mengacu executive summary: [...]

### 2. Important Decisions
- Keputusan penting + alasan (lihat Decision Log): [...]

### 3. Individual Contribution
- Kontribusi tiap anggota (termasuk phase lead yang dijalani): [...]

### 4. AI Usage Disclosure
- Tool AI, bagian yang dibantu, modifikasi, verifikasi manual (lihat TPL-07): [...]

### 5. Verification
- Apa yang diverifikasi manual dan bagaimana (angka, sintaks, fakta): [...]

### 6. Reflection
- Refleksi individu & postmortem tim: [...]

### 7. Portfolio Documentation
- Kumpulan dokumen: D1–D4, meeting log, peer assessment, decision log, profil LinkedIn, screenshot demo, repo GitHub.

### 8. Buat Laporan dengan TPL-04 sebagai lampiran:
1. Pendahuluan & latar belakang (objek studi, masalah)
2. Analisis kebutuhan (ringkasan D1–D2)
3. Desain solusi (IPO, flowchart, pseudocode)
4. Implementasi prototipe (D3 + log uji)
5. Evaluasi & keterbatasan
6. Refleksi tim & postmortem
7. Supporting evidence (AI disclosure, decision log) — lampiran
8. Daftar bukti (observasi, wawancara, screenshot)

---

# SUPPORTING EVIDENCE (batch declare, bukan deliverable inti)

## TPL-05 — Template Executive Summary (Fase Communicate)
*Dipenuhi dari hasil WS14. Bahasa Inggris, 150–250 kata.*

## Executive Summary
**Project**: Digital Problem Framing Mini Project — [Nama Unit Usaha]
**Team**: [Nama anggota] | **Date**: [DD/MM/YYYY]

[Pendahuluan: konteks dan audiens]
[Problem: masalah utama dan siapa yang terdampak, dengan bukti singkat]
[Solution: prototipe yang dibangun dan cara kerjanya]
[Evidence: data/bukti yang mendukung]
[Impact & limitation: dampak dan keterbatasan]
[Call to action / rekomendasi]

*Catatan revisi (untuk asesmen proses):*
| Revisi | Alasan Perbaikan |
|---|---|
| ... | ... |

## TPL-06 — Template Pitch Deck (Fase Communicate)
*Dipenuhi dari hasil WS14. Maksimal 8 slide.*

| Slide | Isi Pesan |
|---|---|
| 1 | Judul, nama tim, unit usaha |
| 2 | Masalah & audiens yang terdampak |
| 3 | Solusi (prototipe) |
| 4 | Demo (screenshot / poin demo) |
| 5 | Bukti & data |
| 6 | Pembelajaran & keterbatasan |
| 7 | AI disclosure ringkas |
| 8 | Terima kasih & tanya jawab |

**Catatan**: satu slide = satu pesan; gunakan poin singkat; sesuaikan bahasa dengan audiens non-teknis.

## TPL-07 — Template AI Usage Disclosure & Verification Note (Supporting Evidence)
*Dipenuhi dari hasil WS15.*

## AI Usage Disclosure & Verification Note
**Project**: ... | **Tim**: ... | **Tanggal**: [DD/MM/YYYY]

### 1. Daftar Penggunaan AI
| Artefak | Tool AI | Bagian yang Dibantu | Modifikasi yang Dilakukan |
|---|---|---|---|
| D1 | [nama tool] | [bagian] | [cara modifikasi] |
| D2 | ... | ... | ... |
| D3 | ... | ... | ... |
| D4 | ... | ... | ... |

### 2. Verification Note
| Artefak | Yang Dicek Ulang Manual | Cara Verifikasi |
|---|---|---|
| D1 | [angka/klaim] | [hitung ulang, cek sumber] |
| D2 | ... | ... |
| D3 | [sintaks & logika] | [jalankan di mesin, uji kasus] |
| D4 | [fakta & bahasa] | [cek kebenaran isi] |

### 3. Pernyataan Kejujuran
Kami menyatakan daftar di atas lengkap dan jujur. Seluruh output AI telah dianalisis, dimodifikasi, dan diverifikasi secara manual.
Tanda tangan seluruh anggota: [nama] / [nama] / [nama] / [nama]

## TPL-08 — Template Decision Log (Supporting Evidence)
*Dipenuhi dari hasil WS08, WS12, WS15.*

## Decision Log
**Project**: ... | **Tim**: ... | **Periode**: [Minggu 5–16]

| # | Tanggal | Konteks | Keputusan | Alternatif yang Dipertimbangkan | Alasan | Konsekuensi |
|---|---|---|---|---|---|---|
| 1 | [DD/MM] | [latar belakang] | [keputusan] | [opsi lain] | [alasan berdasarkan bukti] | [dampak] |
| 2 | ... | ... | ... | ... | ... | ... |

*Aturan: minimal 5 entri; setiap keputusan penting (pemilihan masalah, batasan, desain, revisi, penggunaan AI) wajib dicatat.*

## TPL-09 — Template Meeting Log & Peer Assessment (Supporting Evidence)
*Dipenuhi dari hasil WS01, WS13, WS16.*

## Meeting Log & Peer Assessment
**Project**: ... | **Tim**: ... | **Periode**: [Minggu 1–16]

### 1. Kesepakatan Norma Tim & Rotasi Phase Lead
[Norma + tabel rotasi phase lead + tanda tangan]

### 2. Log Pertemuan
| Tanggal | Agenda | Keputusan | Tindak Lanjut | PIC |
|---|---|---|---|---|
| ... | ... | ... | ... | ... |

### 3. Log Kontribusi Anggota
| Anggota | Peran (Fase) | Kontribusi Utama | Minggu |
|---|---|---|---|
| ... | ... | ... | ... |

### 4. Peer Assessment
| Anggota | Umpan Balik (be kind, be specific, be helpful) |
|---|---|
| ... | ... |

### 5. Refleksi Etika / Perilaku
- Kepatuhan prosedur: ...
- Refleksi nilai (agama/kebangsaan sesuai konteks MK): ...

## TPL-10 — Template Profil LinkedIn / Portofolio Digital (Supporting Evidence)
*Dipenuhi dari hasil WS16.*

## Profil LinkedIn & Portofolio Digital
**Project**: ... | **Nama**: ... | **Tanggal**: [DD/MM/YYYY]

1. **Foto Profil** - foto profesional
2. **Headline** - judul singkat (mis. "Information Systems Student | Aspiring Business Analyst")
3. **About** - ringkasan singkat & apa yang dipelajari dari proyek
4. **Projects** - proyek ini ditambahkan ke bagian "Projects" / "Experience"
5. **Skills** - minimal 3 skill yang dilatih

*Lihat cheat sheet di guidebook (Lampiran LinkedIn).*

## TPL-11 — Individual Competency Passport (per mahasiswa)
*Diisi per mahasiswa; format lengkap di `individual_competency_passport`.*

## Individual Competency Passport
**Nama**: ... | **NIM**: ... | **Semester**: 1

| Kompetensi | Bukti Utama | Skor (0–100) | Tingkat | Status Klaim |
|---|---|---|---|---|
| Problem Framing | D1 + Gate 1 | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| System Thinking | D2 | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Computational Thinking | Flowchart/Pseudocode | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Programming | D3 + Gate 2 | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Testing | D3 (log uji) | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Communication | D4 + presentasi | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Collaboration | Team evidence | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| AI Literacy | AI disclosure | | | [ ] Klaim [ ] Penguatan [ ] Remedial |
| Reflection | D4 refleksi | | | [ ] Klaim [ ] Penguatan [ ] Remedial |

---

# Template Completion Checklist (untuk seluruh penyerahan)
- [ ] Header lengkap (project, tim, tanggal, versi)
- [ ] Bahasa profesional, ringkas, mudah dipahami
- [ ] Data/angka dapat diverifikasi (ada sumber)
- [ ] Seluruh penggunaan AI didisklos (supporting evidence → D4)
- [ ] Keputusan penting tercatat di decision log
- [ ] Kontribusi individu terdokumentasi (untuk passport)
- [ ] File diunggah sesuai jadwal gate di project wall
