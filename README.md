
<div align="center">

# DATASET PUTUSAN NARKOTIKA DAN PSIKOTROPIKA

### Pengadilan Negeri Tarakan | Periode 2023–2025

<img src="https://img.shields.io/badge/Dataset-50%20Putusan-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Pengadilan-PN%20Tarakan-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Format-PDF%20%7C%20XLSX%20%7C%20CSV-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Project-Information%20Retrieval-purple?style=for-the-badge" />

**Repository Dataset dan Pengolahan Dokumen Hukum**  
**Ujian Tengah Semester – Mata Kuliah Temu Kembali Informasi**

</div>

---

## 1. Tentang Proyek

Repository ini berisi kumpulan **50 dokumen putusan perkara narkotika dan psikotropika dari Pengadilan Negeri Tarakan** dengan periode target tahun 2023–2025. Dokumen dikumpulkan dari Direktori Putusan Mahkamah Agung Republik Indonesia dan dilengkapi dengan metadata terstruktur.

Repository ini disusun oleh Kelompok 15 sebagai bagian dari penyelesaian tugas Ujian Tengah Semester (UTS) mata kuliah Temu Kembali Informasi.

Selain menyimpan dataset dokumen putusan dalam format PDF dan metadata dalam format Excel, repository ini juga memuat source code serta hasil proses crawling dan ekstraksi dokumen pada Tugas 3.

Dataset dipersiapkan sebagai korpus dokumen hukum untuk mendukung tahapan pengolahan teks dan penerapan **Information Retrieval (IR)**, yaitu proses menemukan dokumen yang relevan berdasarkan kebutuhan atau kueri pengguna.

## 2. Identitas Proyek dan Tim Penyusun

| Informasi | Keterangan |
|---|---|
| Institusi | Universitas Muhammadiyah Malang |
| Mata Kuliah | Temu Kembali Informasi |
| Semester | Ganjil 2026/2027 |
| Kelas | D |
| Kelompok | 15 |
| Objek Penelitian | Putusan Narkotika dan Psikotropika |
| Pengadilan | Pengadilan Negeri Tarakan |

### Tim Penyusun

| No. | Nama | NIM |
|---|---|---|
| 1 | Luqmanul Hakim | 202310370311141 |
| 2 | Imam Prayuda | 202310370311114 |

## 3. Informasi Dataset

| Komponen | Keterangan |
|---|---|
| Nama Dataset | Dataset Putusan Narkotika dan Psikotropika PN Tarakan |
| Jumlah Dokumen | 50 Putusan |
| Periode | 2023–2025 |
| Lembaga Peradilan | Pengadilan Negeri Tarakan |
| Kategori | Pidana Khusus |
| Subkategori | Narkotika dan Psikotropika |
| Sumber Data | Direktori Putusan Mahkamah Agung RI |
| Format Dokumen | PDF |
| Format Metadata | XLSX |
| Bahasa Dokumen | Bahasa Indonesia |
| Pemanfaatan | Information Retrieval |

## 4. Sumber Data

Seluruh dokumen putusan dalam dataset ini merujuk pada Direktori Putusan Mahkamah Agung Republik Indonesia.

**Sumber utama:**

- [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/)
- [Daftar Putusan Narkotika dan Psikotropika PN Tarakan](https://putusan3.mahkamahagung.go.id/direktori/index/pengadilan/pn-tarakan/kategori/narkotika-dan-psikotropika-1.html)

Portal tersebut digunakan sebagai rujukan untuk menelusuri daftar perkara, mengidentifikasi informasi putusan, dan memperoleh dokumen PDF yang tersedia.

## 5. Kriteria Pemilihan Dokumen

Dokumen yang dimasukkan ke dalam dataset mengikuti kriteria berikut:

1. Berasal dari Pengadilan Negeri Tarakan.
2. Termasuk kategori Pidana Khusus dengan subkategori Narkotika dan Psikotropika.
3. Berada dalam periode tahun 2023–2025.
4. Memiliki nomor putusan yang dapat diidentifikasi.
5. Dokumen tersedia dalam format PDF.
6. Tidak termasuk putusan berstatus Berkekuatan Hukum Tetap (BHT), sesuai ketentuan tugas.

Setiap dokumen dikumpulkan berdasarkan kriteria tersebut agar dataset memiliki ruang lingkup yang jelas dan sesuai dengan kebutuhan tugas.

## 6. Struktur Repository

Repository ini disusun dengan struktur direktori sebagai berikut:

```text
Dataset-Narkotika_141_114/
│
├── Dataset/
│   ├── README.md
│   └── Narkotika.zip
│
├── Overview/
│   ├── README.md
│   └── Overview.xlsx
│
├── Tugas_3/
│   ├── README.md
│   ├── Hasil_Ekstraksi.csv
│   ├── Output_Tugas3_PN_Tarakan.zip
│   └── Notebook_Tugas_3.ipynb
│
└── README.md
```

### Keterangan Folder dan File

| Folder/File | Keterangan |
|---|---|
| `Dataset/` | Menyimpan arsip dokumen putusan sumber. |
| `Narkotika.zip` | Arsip kumpulan dokumen putusan dalam format PDF. |
| `Overview/` | Menyimpan metadata dataset. |
| `Overview.xlsx` | Daftar informasi 50 putusan. |
| `Tugas_3/` | Menyimpan source code dan hasil pengerjaan Tugas 3. |
| `Hasil_Ekstraksi.csv` | Hasil ekstraksi informasi putusan dalam format CSV. |
| `Output_Tugas3_PN_Tarakan.zip` | Arsip hasil proses ekstraksi Tugas 3. |
| `Notebook_Tugas_3.ipynb` | Notebook Google Colab untuk crawling dan ekstraksi dokumen. |
| `README.md` | Dokumentasi utama repository. |

*Catatan: Nama Notebook_Tugas_3.ipynb pada struktur di atas merupakan nama penjelas. Sesuaikan dengan nama file notebook aktual yang diunggah ke GitHub.*

## 7. Struktur Metadata

Metadata dataset disimpan dalam file `Overview.xlsx`. File ini digunakan untuk mencatat informasi utama dari setiap dokumen putusan.

Metadata terdiri atas lima kolom utama:

| No. | Nama Kolom | Deskripsi |
|---|---|---|
| 1 | No | Nomor urut data putusan. |
| 2 | No Putusan | Nomor perkara atau nomor putusan pengadilan. |
| 3 | Lembaga Peradilan | Nama lembaga peradilan yang mengeluarkan putusan. |
| 4 | Barang Bukti | Informasi barang bukti yang tercantum dalam dokumen putusan. |
| 5 | Amar Putusan | Informasi mengenai hasil atau keputusan hakim. |

Metadata disusun berdasarkan informasi yang tercantum dalam dokumen putusan sehingga setiap data dapat ditelusuri kembali ke dokumen sumbernya.

## 8. Tahapan Akuisisi dan Pengolahan Data

Proses pengumpulan dan pengolahan dataset dilakukan melalui beberapa tahapan:

1. **Penentuan Sumber Data**  
   Menentukan Direktori Putusan Mahkamah Agung Republik Indonesia sebagai sumber utama pengumpulan dokumen hukum.

2. **Penentuan Lembaga Peradilan**  
   Memilih Pengadilan Negeri Tarakan sebagai sumber dokumen putusan.

3. **Pemilihan Kategori Perkara**  
   Memilih kategori Pidana Khusus dengan subkategori Narkotika dan Psikotropika.

4. **Penelusuran Dokumen**  
   Menelusuri daftar putusan berdasarkan pengadilan, kategori perkara, dan periode yang telah ditentukan.

5. **Pengumpulan Dokumen PDF**  
   Mengumpulkan dokumen putusan yang tersedia dan sesuai dengan kriteria dataset.

6. **Pencatatan Metadata**  
   Mencatat nomor putusan, lembaga peradilan, barang bukti, dan amar putusan ke dalam file Excel.

7. **Pengarsipan Dataset**  
   Mengelompokkan dokumen PDF ke dalam satu arsip ZIP agar lebih mudah dikelola dan disimpan.

8. **Crawling dan Ekstraksi Dokumen**  
   Melakukan pengolahan dokumen menggunakan program Python pada Google Colaboratory. Apabila akses otomatis ke situs mengalami pembatasan, dokumen PDF yang telah dikumpulkan secara lokal digunakan sebagai sumber ekstraksi.

9. **Pemeriksaan Hasil Ekstraksi**  
   Memeriksa hasil pengolahan dan mencocokkan informasi dokumen dengan metadata yang telah disusun.

## 9. Pemanfaatan Dataset untuk Information Retrieval

Dataset ini dipersiapkan untuk mendukung pembelajaran dan penerapan sistem temu kembali informasi pada dokumen hukum.

Informasi yang dapat dimanfaatkan sebagai dasar pencarian antara lain:

- Nomor putusan.
- Informasi barang bukti.
- Kata kunci dalam amar putusan.
- Istilah yang berkaitan dengan tindak pidana narkotika dan psikotropika.
- Isi teks dalam dokumen putusan.

Dalam pengembangan sistem Information Retrieval, dataset dapat digunakan sebagai korpus dokumen untuk tahapan berikut:

1. Ekstraksi teks dari dokumen PDF.
2. Case folding dan pembersihan teks.
3. Tokenisasi.
4. Normalisasi kata.
5. Stopword removal.
6. Stemming.
7. Pembentukan indeks dokumen (indexing).
8. Pembobotan kata menggunakan TF-IDF.
9. Pencarian dokumen berdasarkan query pengguna.
10. Pemeringkatan dokumen berdasarkan relevansi.

Melalui tahapan tersebut, dokumen putusan dapat diolah menjadi kumpulan informasi yang lebih terstruktur dan dapat dicari berdasarkan relevansinya terhadap kata kunci yang diberikan pengguna.

## 10. Pemeriksaan Kualitas Dataset

Pemeriksaan kualitas dilakukan untuk memastikan dataset tersusun dengan baik dan dapat digunakan pada tahap penelitian selanjutnya.

- [x] Menentukan Pengadilan Negeri Tarakan sebagai sumber pengadilan.
- [x] Menentukan kategori Narkotika dan Psikotropika.
- [x] Mengumpulkan 50 dokumen putusan.
- [x] Menyusun metadata dalam file Overview.xlsx.
- [x] Memeriksa status BHT sesuai konfirmasi kelompok.
- [ ] Memeriksa kembali keterbacaan seluruh dokumen PDF.
- [ ] Mencocokkan nomor putusan dengan dokumen PDF.
- [ ] Memeriksa kemungkinan dokumen duplikat.
- [ ] Memeriksa kelengkapan hasil ekstraksi teks.
- [ ] Memastikan seluruh file yang disebutkan dalam README tersedia di repository.

## 11. Batasan Dataset

Beberapa batasan yang perlu diperhatikan dalam penggunaan dataset ini:

1. Dataset hanya mencakup putusan dari Pengadilan Negeri Tarakan.
2. Dataset dibatasi pada perkara Narkotika dan Psikotropika.
3. Periode pengumpulan dibatasi pada tahun 2023–2025.
4. Ketersediaan dokumen bergantung pada publikasi melalui Direktori Putusan Mahkamah Agung.
5. Struktur dan gaya penulisan setiap dokumen putusan dapat berbeda.
6. Kualitas ekstraksi teks dapat dipengaruhi oleh format dan kualitas dokumen PDF.
7. Metadata merupakan ringkasan informasi dan tidak menggantikan dokumen putusan asli.
8. Hasil ekstraksi otomatis tetap memerlukan pemeriksaan untuk mengidentifikasi teks yang tidak terbaca atau informasi yang tidak tertangkap.

## 12. Sumber dan Atribusi

Seluruh dokumen putusan dalam repository ini bersumber dari Direktori Putusan Mahkamah Agung Republik Indonesia.

Dataset disusun untuk keperluan pendidikan, pembelajaran, dan penelitian akademik dalam bidang Information Retrieval.

Pengguna dataset diharapkan tetap mencantumkan sumber asli dokumen serta memperhatikan ketentuan akses dan penggunaan informasi yang berlaku.

Repository ini tidak dimaksudkan sebagai pengganti dokumen hukum resmi maupun nasihat hukum.

---

<div align="center">

**DATASET PUTUSAN NARKOTIKA DAN PSIKOTROPIKA**

Pengadilan Negeri Tarakan

**INFORMATION RETRIEVAL — KELOMPOK 15**

Universitas Muhammadiyah Malang

</div>
