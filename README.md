# klasifikasi-laporan-keselamatan-penerbangan
Aplikasi web berbasis Flask untuk mengklasifikasikan narasi laporan keselamatan
penerbangan secara otomatis menggunakan TF-IDF dan Support Vector Machine (SVM).

Proyek Mata Kuliah Proyek Perangkat Lunak, Program Studi Teknik Informatika,
Fakultas Ilmu Komputer dan Informatika, Universitas Nurtanio Bandung (2026).

## Anggota Kelompok 6

| Nama | NIM | Peran |
|---|---|---|
| Rusdiana | 55201123002 | Data & Text Preprocessing Pipeline |
| Daffa Danishwara | 55201123020 | Feature Engineering (TF-IDF) & Pelatihan/Evaluasi Model SVM |
| Philip Zefanya Victory S | 55201122030 | Backend Flask & Integrasi Model |
| Muhammad Albar Imamuddin R | 55201123015 | Frontend Web, Diagram/Wireframe, Pengujian & Laporan |

Dosen Pengampu: Suharjanto Utomo, S.Si., M.T.

## Deskripsi

Pengguna memasukkan teks narasi laporan, lalu sistem menampilkan kategori hasil
klasifikasi beserta tingkat keyakinannya. Hasil bersifat bantuan dan tetap perlu
diverifikasi oleh petugas keselamatan.

## Teknologi

- Python, scikit-learn (TF-IDF, SVM), NLTK
- Flask (backend), HTML/CSS/JavaScript (frontend)
- Google Colab (pelatihan model)

## Status

Proyek sedang dalam pengerjaan. Bagian dataset, hasil evaluasi, dan cara
menjalankan aplikasi akan dilengkapi setelah implementasi selesai.

## Struktur Folder

```
├── data/        dataset
├── notebooks/   notebook prapemrosesan dan pelatihan model
├── src/         fungsi prapemrosesan yang dipakai bersama
├── models/      pipeline hasil pelatihan (.joblib)
├── app/         aplikasi Flask (backend dan frontend)
└── docs/        laporan dan diagram
```
