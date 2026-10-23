# Pertemuan 10 String
Nama: Wulan Nur'aini
NIM: 2225250131
Kelas: 3E

## Tujuan
Memahami dan mengimplementasikan manipulasi data teks (String) di Python, meliputi penggunaan operasi dasar, indeks dan pemotongan (slicing), pembersihan teks, pemisahan dan penggabungan (split & join), pencarian kata, serta normalisasi data teks secara otomatis.

## Cara Menjalankan
python3 tugas/normalisasi_data_mahasiswa.py

## Struktur Fungsi
1. bersihkan_nama(nama)
Parameter: nama (str)
Return Value: str (nama yang sudah dirapikan format spasi dan kapitalisasinya)
Deskripsi: Menghapus spasi berlebih di awal/akhir dan memformat teks menjadi format Title Case.
2. format_kode_kelas(kode)
Parameter: kode (str)
Return Value: str (kode kelas dalam huruf kapital dengan pemisah tanda hubung)
Deskripsi: Mengubah kode kelas menjadi huruf kapital dan mengganti spasi antar kata dengan tanda hubung (-).
3. hitung_kata_dan_inisial(nama)
Parameter: nama (str)
Return Value: tuple (int jumlah kata, str inisial kapital)
Deskripsi: Menghitung total kata pada nama bersih dan mengambil huruf pertama dari setiap kata sebagai inisial.

## Hasil Pengujian

| No | Fungsi / Latihan | Input / Test Case | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|---|
| 1 | `01_dasar_string.py` | `01_dasar_string.py` | `Algoritma`, `9`, `ALGORITMA`, `algoritma` | `Algoritma`, `9`, `ALGORITMA`, `algoritma` | Berhasil |
| 2 | `02_indeks_slicing.py` | `02_indeks_slicing.py` | `P`, `n`, `Pemr`, `ograman`, `namargormeP` | `P`, `n`, `Pemr`, `ograman`, `namargormeP` | Berhasil |
| 3 | `03_method_string.py` | `03_method_string.py` | `fATHIYYAH mUTHMAINNAH`, `Fathiyyah Muthmainnah`, `FATHIYYAH MUTHMAINNAH` | `fATHIYYAH mUTHMAINNAH`, `Fathiyyah Muthmainnah`, `FATHIYYAH MUTHMAINNAH` | Berhasil |
| 4 | `04_bersihkan_teks.py` | `04_bersihkan_teks.py` | `Belajar python untuk pendidikan` | `Belajar python untuk pendidikan` | Berhasil |
| 5 | `05_split_join.py` | `05_split_join.py` | `['data', 'teks', 'perlu', 'dibersihkan']`, `data-teks-perlu-dibersihkan` | `['data', 'teks', 'perlu', 'dibersihkan']`, `data-teks-perlu-dibersihkan` | Berhasil |
| 6 | `06_pencarian_kata.py` | `06_pencarian_kata.py` | `True`, `2`, `0` | `True`, `2`, `0` | Berhasil |
| 7 | `normalisasi_data_mahasiswa.py` | `Nama: aan hendrayana`, `Kode kelas: pmat a 2026` | `Nama bersih : Aan Hendrayana`, `Kode kelas : PMAT-A-2026`, `Jumlah kata : 2`, `Inisial : AH` | `Nama bersih : Aan Hendrayana`, `Kode kelas : PMAT-A-2026`, `Jumlah kata : 2`, `Inisial : AH` | Berhasil |
| 8 | `normalisasi_data_mahasiswa.py` | `Nama: fATHIYYAH mUTHMAINNAH`, `Kode kelas: kelas b` | `Nama bersih : Fathiyyah Muthmainnah`, `Kode kelas : KELAS-B`, `Jumlah kata : 2`, `Inisial : FM` | `Nama bersih : Fathiyyah Muthmainnah`, `Kode kelas : KELAS-B`, `Jumlah kata : 2`, `Inisial : FM` | Berhasil |
| 9 | `normalisasi_data_mahasiswa.py` | `Nama: BUDI`, `Kode kelas: pmtk 01` | `Nama bersih : Budi`, `Kode kelas : PMTK-01`, `Jumlah kata : 1`, `Inisial : B` | `Nama bersih : Budi`, `Kode kelas : PMTK-01`, `Jumlah kata : 1`, `Inisial : B` | Berhasil |
| 10 | `normalisasi_data_mahasiswa.py` | `Nama:  siti nur aisyah `, `Kode kelas: kelas c` | `Nama bersih : Siti Nur Aisyah`, `Kode kelas : KELAS-C`, `Jumlah kata : 3`, `Inisial : SNA` | `Nama bersih : Siti Nur Aisyah`, `Kode kelas : KELAS-C`, `Jumlah kata : 3`, `Inisial : SNA` | Berhasil |

## Refleksi
Penggunaan metode bawaan string pada Python mempermudah pemrosesan dan pembersihan teks secara efisien:
1. Kemudahan Normalisasi Teks: Method seperti strip(), title(), upper(), dan lower() memungkinkan pembentukan format input masukan pengguna yang konsisten tanpa algoritma rumit.
2. Manipulasi Struktur Teks: Kombinasi split() dan join() mempermudah pemecahan teks menjadi elemen-elemen kata serta penggabungan kembali dengan karakter pemisah tersendiri.
3. Otomatisasi Ekstraksi Informasi: Operasi pengindeksan dan iterasi list hasil pemecahan teks mempermudah proses pembuatan inisial dan perhitungan statistik kata secara presisi.