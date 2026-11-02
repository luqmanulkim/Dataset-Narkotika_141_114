
# Dataset Putusan Pengadilan Tindak Pidana Narkotika
### Pengadilan Negeri Purwokerto

![Status](https://img.shields.io/badge/Status-Pengumpulan%20Data-orange)
![Category](https://img.shields.io/badge/Kategori-Pidana%20Khusus-blue)
![Subject](https://img.shields.io/badge/Topik-Narkotika%20dan%20Psikotropika-green)

Repository ini merupakan dokumentasi dan penyimpanan dataset dokumen putusan pengadilan terkait perkara **Narkotika dan Psikotropika** pada Pengadilan Negeri Purwokerto. Dataset dikumpulkan dari Direktori Putusan Mahkamah Agung Republik Indonesia dan dipersiapkan untuk mendukung tugas Ujian Tengah Semester (UTS) mata kuliah Temu Kembali Informasi.

---

## 📌 Daftar Isi

- [Gambaran Umum](#-gambaran-umum)
- [Tujuan](#-tujuan)
- [Informasi Dataset](#-informasi-dataset)
- [Sumber Data](#-sumber-data)
- [Kriteria Pemilihan Dokumen](#-kriteria-pemilihan-dokumen)
- [Struktur Repository](#-struktur-repository)
- [Struktur Metadata](#-struktur-metadata)
- [Proses Pengumpulan Data](#-proses-pengumpulan-data)
- [Rencana Pengolahan dan Pengindeksan](#-rencana-pengolahan-dan-pengindeksan)
- [Contoh Pencarian](#-contoh-pencarian)
- [Pemeriksaan Kualitas Dataset](#-pemeriksaan-kualitas-dataset)
- [Batasan Dataset](#-batasan-dataset)
- [Tim Penyusun](#-tim-penyusun)

---

## 📖 Gambaran Umum

Dokumen putusan pengadilan merupakan salah satu sumber informasi hukum yang memiliki struktur dan isi cukup kompleks. Di dalamnya terdapat informasi mengenai identitas perkara, kronologi kejadian, pertimbangan hakim, barang bukti, serta amar putusan.

Repository ini berfokus pada pengumpulan dokumen putusan perkara narkotika dan psikotropika yang berasal dari Pengadilan Negeri Purwokerto.

Dokumen dikumpulkan dalam format PDF dan dilengkapi dengan metadata yang disusun dalam file Excel. Selanjutnya, dataset dapat dimanfaatkan sebagai korpus dalam pengembangan sistem **Information Retrieval (IR)** atau sistem temu kembali informasi.

## 🎯 Tujuan

Pengumpulan dataset ini memiliki beberapa tujuan:

1. Mengumpulkan dokumen putusan perkara narkotika dan psikotropika dari sumber resmi.
2. Menyediakan kumpulan dokumen hukum dalam format digital PDF.
3. Menyusun metadata untuk memudahkan identifikasi dan pengelolaan dokumen.
4. Menyiapkan korpus dokumen untuk proses ekstraksi teks, preprocessing, dan indexing.
5. Mendukung penerapan metode temu kembali informasi dalam pencarian dokumen putusan hukum.

## 📊 Informasi Dataset

| Informasi | Keterangan |
|---|---|
| Nama Dataset | Dataset Putusan Narkotika PN Purwokerto |
| Kategori | Pidana Khusus |
| Subkategori | Narkotika dan Psikotropika |
| Lembaga Peradilan | Pengadilan Negeri Purwokerto |
| Sumber | Direktori Putusan Mahkamah Agung RI |
| Format Dokumen | PDF |
| Format Metadata | XLSX |
| Target Jumlah Dokumen | 50 dokumen |
| Bahasa Dokumen | Bahasa Indonesia |
| Pemanfaatan | Information Retrieval |

**Catatan:** Target pengumpulan adalah 50 dokumen. Jumlah dokumen aktual mengikuti berkas PDF yang berhasil dikumpulkan dan memenuhi kriteria seleksi.

## 🌐 Sumber Data

Seluruh dokumen putusan diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia.

**Sumber utama:**

- [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/)
- [Daftar Putusan Narkotika dan Psikotropika PN Purwokerto](https://putusan3.mahkamahagung.go.id/direktori/index/pengadilan/pn-purwokerto/kategori/narkotika-dan-psikotropika-1.html)

Sumber tersebut digunakan untuk menelusuri informasi perkara dan mengunduh dokumen putusan yang tersedia.

## 📋 Kriteria Pemilihan Dokumen

Dokumen yang dimasukkan ke dalam dataset mengikuti kriteria berikut:

1. Dokumen berasal dari Pengadilan Negeri Purwokerto.
2. Termasuk kategori Pidana Khusus.
3. Termasuk subkategori Narkotika dan Psikotropika.
4. Dokumen putusan tersedia dan dapat diunduh dalam format PDF.
5. Mengutamakan putusan pada periode tahun 2023–2025.
6. Tidak memasukkan putusan dengan status Berkekuatan Hukum Tetap (BHT), sesuai ketentuan tugas.

Setiap dokumen diperiksa sebelum dimasukkan ke dalam kumpulan dataset.

## 📁 Struktur Repository

Repository disusun dengan struktur direktori sebagai berikut:

```text
Dataset-Narkotika_141_114/
│
├── Dataset/
│   └── Narkotika.zip
│
├── Overview/
│   └── Overview.xlsx
│
└── README.md
```

**Keterangan:**

| Folder/File | Deskripsi |
|---|---|
| `Dataset/` | Menyimpan kumpulan dokumen putusan. |
| `Narkotika.zip` | Arsip berisi dokumen putusan dalam format PDF. |
| `Overview/` | Menyimpan metadata dan ringkasan dokumen. |
| `Overview.xlsx` | Tabel informasi setiap dokumen putusan. |
| `README.md` | Dokumentasi repository dan dataset. |

## 🗂️ Struktur Metadata

File `Overview.xlsx` digunakan untuk mendokumentasikan informasi penting dari setiap dokumen putusan.

Metadata memiliki kolom sebagai berikut:

| Kolom | Keterangan |
|---|---|
| No | Nomor urut dokumen dalam dataset. |
| No Putusan | Nomor perkara atau nomor putusan pengadilan. |
| Lembaga Peradilan | Nama pengadilan yang mengeluarkan putusan. |
| Barang Bukti | Barang bukti yang tercantum dalam dokumen putusan. |
| Amar Putusan | Ringkasan hasil atau keputusan hakim. |

Metadata ini membantu proses identifikasi dokumen dan dapat digunakan sebagai informasi pendukung dalam sistem temu kembali informasi.

## 🔄 Proses Pengumpulan Data

Pengumpulan dataset dilakukan melalui beberapa tahapan:

1. **Penentuan sumber:** memilih Direktori Putusan Mahkamah Agung sebagai sumber dokumen.
2. **Pemilihan pengadilan:** menentukan Pengadilan Negeri Purwokerto.
3. **Penyaringan kategori:** memilih kategori Pidana Khusus dengan subkategori Narkotika dan Psikotropika.
4. **Pemeriksaan putusan:** memeriksa informasi perkara dan status putusan.
5. **Pengunduhan dokumen:** mengunduh dokumen putusan yang tersedia dalam format PDF.
6. **Pengelompokan dokumen:** mengumpulkan berkas PDF ke dalam satu arsip ZIP.
7. **Pencatatan metadata:** memasukkan informasi perkara ke dalam `Overview.xlsx`.
8. **Pemeriksaan akhir:** memastikan kesesuaian antara dokumen PDF dan metadata.

## ⚙️ Rencana Pengolahan dan Pengindeksan

Dataset ini dipersiapkan untuk digunakan dalam tahapan pengembangan sistem Information Retrieval.

Alur pengolahan dokumen yang direncanakan adalah sebagai berikut:

```text
Dokumen Putusan PDF
        |
        v
Ekstraksi Teks
        |
        v
Case Folding
        |
        v
Tokenization
        |
        v
Normalization
        |
        v
Stopword Removal
        |
        v
Stemming
        |
        v
Document Indexing
        |
        v
TF-IDF
        |
        v
Information Retrieval
        |
        v
Hasil Pencarian Dokumen
```

### Tahapan Pengolahan

**1. Ekstraksi Teks**

Mengambil isi teks dari dokumen PDF agar dapat diproses oleh sistem.

**2. Case Folding**

Mengubah seluruh karakter teks menjadi huruf kecil untuk menyamakan bentuk kata.

**3. Tokenization**

Memecah teks menjadi bagian-bagian kata atau token.

**4. Normalization**

Menyeragamkan kata yang memiliki variasi penulisan atau bentuk tidak baku.

**5. Stopword Removal**

Menghapus kata-kata umum yang kurang memberikan kontribusi terhadap proses pencarian informasi.

**6. Stemming**

Mengubah kata berimbuhan menjadi bentuk kata dasarnya.

**7. Indexing**

Menyusun representasi dokumen agar informasi di dalamnya dapat dicari secara lebih efisien.

**8. TF-IDF**

Memberikan bobot pada kata berdasarkan tingkat kepentingannya dalam dokumen dan keseluruhan kumpulan dokumen.

**9. Information Retrieval**

Melakukan pencarian dokumen berdasarkan kata kunci atau query yang dimasukkan pengguna.

## 🔎 Contoh Pencarian

Dataset ini dapat digunakan untuk menguji pencarian informasi berdasarkan kata kunci yang berkaitan dengan perkara narkotika.

Contoh query:

| No | Query Pencarian |
|---|---|
| 1 | kepemilikan narkotika jenis sabu |
| 2 | penyalahgunaan narkotika |
| 3 | barang bukti metamfetamina |
| 4 | peredaran narkotika golongan I |
| 5 | tindak pidana narkotika |

Sistem Information Retrieval nantinya diharapkan dapat menampilkan dokumen yang memiliki tingkat relevansi tertinggi terhadap query pengguna.

## ✅ Pemeriksaan Kualitas Dataset

Untuk menjaga kualitas dataset, dilakukan pemeriksaan terhadap beberapa aspek berikut:

- [ ] Dokumen berasal dari sumber resmi Mahkamah Agung.
- [ ] Seluruh dokumen sesuai dengan kategori yang ditentukan.
- [ ] Dokumen PDF dapat dibuka dan dibaca.
- [ ] Tidak terdapat dokumen duplikat.
- [ ] Nomor putusan sesuai dengan dokumen PDF.
- [ ] Metadata telah diisi sesuai informasi pada dokumen.
- [ ] Status BHT telah diperiksa dan dokumen yang tidak memenuhi kriteria dikeluarkan.
- [ ] Jumlah dokumen sesuai dengan target pengumpulan.

## ⚠️ Batasan Dataset

Beberapa batasan yang perlu diperhatikan:

1. Dataset hanya mencakup putusan dari Pengadilan Negeri Purwokerto.
2. Dataset dibatasi pada perkara Narkotika dan Psikotropika.
3. Ketersediaan dokumen bergantung pada berkas yang disediakan oleh Direktori Putusan Mahkamah Agung.
4. Tidak semua informasi dalam dokumen memiliki format penulisan yang seragam.
5. Kualitas ekstraksi teks dapat dipengaruhi oleh struktur dan kualitas file PDF.
6. Metadata merupakan ringkasan informasi yang diambil dari dokumen putusan, bukan pengganti dokumen hukum aslinya.

## 📜 Sumber, Atribusi, dan Penggunaan

Dokumen putusan dalam repository ini bersumber dari Direktori Putusan Mahkamah Agung Republik Indonesia.

Penggunaan dataset ditujukan untuk kepentingan pendidikan, pembelajaran, dan penelitian akademik pada bidang Information Retrieval.

Pengguna dataset diharapkan tetap mencantumkan sumber resmi dokumen dan memperhatikan ketentuan akses serta penggunaan informasi yang berlaku.

Repository ini tidak dimaksudkan sebagai pengganti sumber hukum resmi atau nasihat hukum.

## 👥 Tim Penyusun

Dataset ini disusun oleh mahasiswa yang tergabung dalam Kelompok 15 pada mata kuliah Temu Kembali Informasi.

| No | Nama | NIM |
|---|---|---|
| 1 | Luqmanul Hakim | 202310370311141 |
| 2 | Imam Prayuda | 202310370311114 |

**Institusi:** Universitas Muhammadiyah Malang  
**Mata Kuliah:** Temu Kembali Informasi  
**Semester:** Ganjil 2026/2027  
**Kelas:** D  
**Kelompok:** 15

---

## 📝 Riwayat Pembaruan

| Versi | Keterangan |
|---|---|
| 1.0 | Pembuatan repository dan dokumentasi awal dataset. |
| 1.1 | Penyesuaian sumber pengumpulan menjadi PN Purwokerto. |
| 1.2 | Penambahan metadata dan dokumentasi tahapan Information Retrieval. |

---

<p align="center">
  <b>Dataset Putusan Narkotika PN Purwokerto</b><br>
  Information Retrieval — Kelompok 15
</p>
