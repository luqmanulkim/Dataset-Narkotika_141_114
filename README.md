
# Dataset Putusan Perkara Narkotika dan Psikotropika
### Pengadilan Negeri Tarakan

## 👥 Tim Penyusun

Dataset ini disusun oleh Kelompok 15 untuk memenuhi tugas Ujian Tengah Semester mata kuliah Temu Kembali Informasi.

| No | Nama | NIM |
|---|---|---|
| 1 | Luqmanul Hakim | 202310370311141 |
| 2 | Imam Prayuda | 202310370311114 |

**Institusi:** Universitas Muhammadiyah Malang  
**Mata Kuliah:** Temu Kembali Informasi  
**Semester:** Ganjil 2026/2027  
**Kelas:** D  
**Kelompok:** 15


<p align="center">
  <img src="https://img.shields.io/badge/Dataset-50%20Putusan-blue" />
  <img src="https://img.shields.io/badge/Kategori-Pidana%20Khusus-green" />
  <img src="https://img.shields.io/badge/Format-PDF%20%7C%20XLSX-orange" />
</p>

Repository ini berisi kumpulan dokumen putusan pengadilan terkait perkara **Narkotika dan Psikotropika** yang berasal dari Pengadilan Negeri Tarakan. Dataset dikumpulkan melalui Direktori Putusan Mahkamah Agung Republik Indonesia untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah **Temu Kembali Informasi**.

Dataset terdiri dari 50 data putusan yang dilengkapi dengan dokumen PDF dan metadata dalam format Excel. Kumpulan dokumen ini dipersiapkan sebagai korpus dokumen hukum untuk mendukung proses pengolahan data dan penerapan sistem Information Retrieval.

---

## 📑 Daftar Isi

1. [Tentang Dataset](#-tentang-dataset)
2. [Tujuan Pengumpulan](#-tujuan-pengumpulan)
3. [Informasi Dataset](#-informasi-dataset)
4. [Sumber Data](#-sumber-data)
5. [Kriteria Pemilihan Dokumen](#-kriteria-pemilihan-dokumen)
6. [Struktur Repository](#-struktur-repository)
7. [Struktur Metadata](#-struktur-metadata)
8. [Contoh Metadata](#-contoh-metadata)
9. [Tahapan Akuisisi Dataset](#-tahapan-akuisisi-dataset)
10. [Pemanfaatan Dataset](#-pemanfaatan-dataset)
11. [Pemeriksaan Kualitas Dataset](#-pemeriksaan-kualitas-dataset)
12. [Batasan Dataset](#-batasan-dataset)
13. [Sumber dan Atribusi](#-sumber-dan-atribusi)
14. [Tim Penyusun](#-tim-penyusun)

---

## 📖 Tentang Dataset

Dataset ini merupakan kumpulan dokumen putusan pengadilan yang berkaitan dengan tindak pidana narkotika dan psikotropika pada Pengadilan Negeri Tarakan.

Setiap dokumen putusan memuat berbagai informasi hukum, antara lain:

- Nomor perkara atau nomor putusan.
- Lembaga peradilan yang mengeluarkan putusan.
- Informasi barang bukti.
- Amar putusan atau hasil keputusan hakim.
- Informasi lain yang tercantum dalam dokumen putusan.

Informasi utama dari setiap dokumen dicatat dalam file Excel agar memudahkan proses identifikasi, pengelolaan, dan pencarian data.

Dataset ini selanjutnya dapat dimanfaatkan sebagai kumpulan dokumen (document collection) dalam pengembangan sistem temu kembali informasi atau Information Retrieval.

## 🎯 Tujuan Pengumpulan

Pengumpulan dataset ini memiliki beberapa tujuan:

1. Mengumpulkan dokumen putusan perkara narkotika dan psikotropika dari sumber resmi Mahkamah Agung Republik Indonesia.
2. Membentuk kumpulan dokumen hukum dalam format digital PDF.
3. Menyediakan metadata terstruktur untuk setiap dokumen putusan.
4. Menyiapkan dataset untuk proses ekstraksi teks dan preprocessing.
5. Mendukung penerapan metode temu kembali informasi berdasarkan isi dokumen hukum.
6. Menjadi sumber data untuk pengujian proses pencarian dan pengambilan informasi berdasarkan kata kunci.

## 📊 Informasi Dataset

| Informasi | Keterangan |
|---|---|
| Nama Dataset | Dataset Putusan Narkotika PN Tarakan |
| Jumlah Data | 50 putusan |
| Lembaga Peradilan | Pengadilan Negeri Tarakan |
| Kategori | Pidana Khusus |
| Subkategori | Narkotika dan Psikotropika |
| Sumber Data | Direktori Putusan Mahkamah Agung RI |
| Periode Target | 2023–2025 |
| Format Dokumen | PDF |
| Format Metadata | XLSX |
| Bahasa Dokumen | Bahasa Indonesia |
| Pemanfaatan | Information Retrieval |

## 🌐 Sumber Data

Seluruh data putusan diperoleh melalui Direktori Putusan Mahkamah Agung Republik Indonesia.

**Sumber utama:**

- [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/)
- [Daftar Putusan Narkotika dan Psikotropika PN Tarakan](https://putusan3.mahkamahagung.go.id/direktori/index/pengadilan/pn-tarakan/kategori/narkotika-dan-psikotropika-1.html)

Sumber tersebut digunakan untuk menelusuri daftar perkara, memeriksa informasi putusan, dan memperoleh dokumen PDF yang tersedia.

## 📋 Kriteria Pemilihan Dokumen

Dokumen yang dikumpulkan mengikuti kriteria berikut:

1. Berasal dari Pengadilan Negeri Tarakan.
2. Termasuk kategori Pidana Khusus.
3. Termasuk subkategori Narkotika dan Psikotropika.
4. Berada dalam periode tahun 2023–2025 sesuai ketentuan tugas.
5. Memiliki nomor putusan yang dapat diidentifikasi.
6. Dokumen putusan tersedia dalam format PDF.
7. Tidak termasuk putusan dengan status Berkekuatan Hukum Tetap (BHT), sesuai ketentuan tugas.

Setiap dokumen perlu diperiksa kesesuaiannya dengan kriteria tersebut sebelum digunakan dalam proses penelitian.

## 📁 Struktur Repository

Repository ini menggunakan struktur direktori sebagai berikut:

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

### Penjelasan Struktur

| File/Folder | Keterangan |
|---|---|
| `Dataset/` | Folder penyimpanan kumpulan dokumen putusan. |
| `Narkotika.zip` | Arsip berisi dokumen putusan dalam format PDF. |
| `Overview/` | Folder penyimpanan metadata dataset. |
| `Overview.xlsx` | File Excel berisi informasi 50 putusan. |
| `README.md` | Dokumentasi mengenai dataset dan repository. |

## 🗂️ Struktur Metadata

Metadata dataset disimpan dalam file `Overview.xlsx`. File ini digunakan untuk mencatat informasi utama dari setiap dokumen putusan.

Terdapat lima kolom utama dalam metadata:

| No | Nama Kolom | Deskripsi |
|---|---|---|
| 1 | No | Nomor urut setiap data putusan. |
| 2 | No Putusan | Nomor perkara atau nomor putusan pengadilan. |
| 3 | Lembaga Peradilan | Nama lembaga peradilan yang mengeluarkan putusan. |
| 4 | Barang Bukti | Informasi barang bukti yang tercantum dalam dokumen putusan. |
| 5 | Amar Putusan | Informasi mengenai hasil atau keputusan hakim dalam perkara tersebut. |

Metadata disusun berdasarkan informasi yang tercantum dalam dokumen putusan sehingga setiap baris data dapat ditelusuri kembali ke dokumen sumbernya.

## 📝 Contoh Metadata

Berikut merupakan contoh dua data putusan yang tercatat dalam `Overview.xlsx`:

| No | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
|---:|---|---|---|---|
| 1 | 163/Pid.Sus/2023/PN Tar | PN TARAKAN | 29 (dua puluh sembilan) bungkus plastik bening berisi narkotika jenis sabu; 1 (satu) buah dompet kecil berwarna hitam; 1 (satu) bendel plastik klip bening pembungkus sabu; dan 2 (dua) bungkus plastik sedotan berwarna merah berisi narkotika jenis sabu. | Menyatakan Terdakwa RUSDI alias DAENG REWA Bin ABDULLAH telah terbukti secara sah dan meyakinkan bersalah melakukan tindak pidana secara tanpa hak atau melawan hukum, bermufakat untuk membeli Narkotika Golongan I bukan tanaman. |
| 2 | 247/Pid.Sus/2023/PN Tar | PN TARAKAN | 1 (satu) bungkus plastik klip bening berisikan narkotika jenis sabu; dan 1 (satu) buah kotak rokok Gudang Garam Surya 16. Barang bukti dirampas untuk dimusnahkan. | Menyatakan Terdakwa Salang Bin (Alm) Caco terbukti secara sah dan meyakinkan bersalah melakukan tindak pidana percobaan atau permufakatan jahat tanpa hak atau melawan hukum menawarkan untuk dijual, menjual, membeli, menerima, menjadi perantara dalam jual beli, menukar, atau menyerahkan Narkotika Golongan I. |

*Catatan: Contoh di atas menunjukkan format penyajian metadata. Informasi lengkap seluruh putusan tersedia dalam file `Overview.xlsx`.*

## 🔄 Tahapan Akuisisi Dataset

Proses pengumpulan dataset dilakukan melalui beberapa tahapan berikut:

**1. Penentuan Sumber Data**

Menentukan Direktori Putusan Mahkamah Agung Republik Indonesia sebagai sumber utama pengumpulan dokumen hukum.

**2. Penentuan Lembaga Peradilan**

Memilih Pengadilan Negeri Tarakan sebagai lembaga peradilan yang menjadi sumber dokumen putusan.

**3. Pemilihan Kategori Perkara**

Memilih kategori Pidana Khusus dengan subkategori Narkotika dan Psikotropika.

**4. Penelusuran Dokumen**

Menelusuri daftar putusan yang tersedia pada Direktori Putusan Mahkamah Agung berdasarkan pengadilan dan kategori perkara yang telah ditentukan.

**5. Pengumpulan Dokumen PDF**

Mengunduh dokumen putusan yang tersedia dan sesuai dengan kriteria pengumpulan.

**6. Pencatatan Metadata**

Mencatat informasi nomor putusan, lembaga peradilan, barang bukti, dan amar putusan ke dalam file Excel.

**7. Pengelompokan Dataset**

Mengumpulkan dokumen PDF ke dalam satu arsip ZIP agar lebih mudah disimpan, dikelola, dan didistribusikan.

**8. Pemeriksaan Dataset**

Memeriksa kesesuaian informasi metadata dengan dokumen PDF yang menjadi sumber data.

## 🔍 Pemanfaatan Dataset

Dataset ini dipersiapkan untuk mendukung penerapan sistem Information Retrieval pada dokumen hukum.

Informasi yang dapat dimanfaatkan sebagai dasar pencarian antara lain:

- Nomor putusan.
- Informasi barang bukti.
- Kata kunci dalam amar putusan.
- Istilah yang berkaitan dengan tindak pidana narkotika.
- Isi teks dalam dokumen putusan.

Dalam proses pengembangan sistem Information Retrieval, dataset ini dapat digunakan sebagai korpus dokumen untuk tahapan:

1. Ekstraksi teks dari dokumen PDF.
2. Preprocessing teks.
3. Tokenisasi dan normalisasi.
4. Stopword removal.
5. Stemming.
6. Pembentukan indeks dokumen.
7. Pembobotan kata menggunakan TF-IDF.
8. Pencarian dokumen berdasarkan query pengguna.

Dengan tahapan tersebut, dokumen putusan dapat diproses menjadi kumpulan informasi yang lebih mudah dicari dan ditemukan berdasarkan relevansi terhadap kata kunci.

## ✅ Pemeriksaan Kualitas Dataset

Pemeriksaan kualitas dilakukan untuk memastikan dataset tersusun dengan baik dan dapat digunakan pada tahap penelitian selanjutnya.

- [x] Menentukan Pengadilan Negeri Tarakan sebagai sumber pengadilan.
- [x] Menentukan kategori Narkotika dan Psikotropika.
- [x] Mengumpulkan 50 data putusan.
- [x] Menyusun metadata dalam file `Overview.xlsx`.
- [ ] Memastikan seluruh dokumen PDF dapat dibuka.
- [ ] Memeriksa kesesuaian nomor putusan dengan dokumen PDF.
- [ ] Memeriksa kemungkinan dokumen duplikat.
- [ ] Memverifikasi status BHT setiap putusan.
- [ ] Memastikan seluruh dokumen memenuhi ketentuan periode pengumpulan.

## ⚠️ Batasan Dataset

Beberapa batasan yang perlu diperhatikan dalam penggunaan dataset:

1. Dataset hanya mencakup putusan dari Pengadilan Negeri Tarakan.
2. Dataset dibatasi pada perkara Narkotika dan Psikotropika.
3. Ketersediaan dokumen bergantung pada publikasi melalui Direktori Putusan Mahkamah Agung.
4. Struktur dan gaya penulisan setiap dokumen putusan dapat berbeda.
5. Kualitas ekstraksi teks dapat dipengaruhi oleh format dan kualitas dokumen PDF.
6. Metadata merupakan ringkasan informasi dan tidak menggantikan dokumen putusan asli.

## 📜 Sumber dan Atribusi

Seluruh dokumen putusan dalam repository ini bersumber dari Direktori Putusan Mahkamah Agung Republik Indonesia.

Dataset disusun untuk keperluan pendidikan, pembelajaran, dan penelitian akademik dalam bidang Information Retrieval.

Pengguna dataset diharapkan tetap mencantumkan sumber asli dokumen serta memperhatikan ketentuan akses dan penggunaan informasi yang berlaku.

Repository ini tidak dimaksudkan sebagai pengganti dokumen hukum resmi maupun nasihat hukum.

---

<p align="center">
  <b>Dataset Putusan Narkotika dan Psikotropika</b><br>
  Pengadilan Negeri Tarakan<br>
  Information Retrieval — Kelompok 15
</p>
