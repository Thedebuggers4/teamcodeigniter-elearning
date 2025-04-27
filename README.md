# Team TA
## CodeIgniter 3 / e-learnix's
____
#### Sistem Informasi E-Learning Pada SMK Teknologi Pilar Bangsa
____
Dibuat Oleh The Debuggers [ada disini](https://thedebuggers.vercel.app/)
____

### Panduan:
#### Added
- Support PHP 7.4 ~ 8.3
- Login e-learnix's
- Update foto siswa perkelas
- Auto logout admin setelah ganti password
- Import Guru dengan foto
- Editor Header jawaban essai di ujian siswa


#### Changed
- Font Arabic Calibri
- Remove vendor folder

#### Fixed
- Zoom in/out soal siswa
- Koreksi Ujian
- Rekap ujian
- Pengawas undefined
- Jawaban isian singkat dianggap salah
- Jawaban soal menjodohkan dianggap belum menjawab
- Hasil export nilai Excel header tabel tidak pas ketika tidak ada soal PG
- Nilai siswa ketika diulang
- Tanda petik di header Kartu Ujian, Daftar Kehadiran dan Berita Acara
- Nilai harian (e-Learning)
- Edit Materi (e-Learning)


___________

## Catatan:
Aplikasi ini akan dihibahkan untuk SMK Teknologi Pilar Bangsa dengan tujuan untuk proses kegiatan belajar mengajar.

Kami selaku pengembang aplikasi ini terdiri :
- Arya Dillah - Backend Dev
- Adi Satria Sejati - Frontend Dev
- Febrian Sitorus - UI/UX Dev
Mengucapkan banyak-banyak terima kasih atas dukungan dan bimbingannya. 
______________

----
## Install
* Download Aplikasi dari menu **Code => Download ZIP**
* Extract di folder **htdocs** jika menggunakan XAMPP, atau folder **www** jika mengonakan Laragon
----
## Update
* Download Aplikasi dari menu **Code => Download ZIP**
* Extract dan replace semua code di folder aplikasi
* sesuaikan nama database yang digunakan
* backup database untuk berjaga-jaga
* jalankan menu **update** di menu DATABASE => UPDATE
______
### MENU FITUR
1. DATA MASTER
   * Beranda
   * Data Umum
      * Tahun Pelajaran
      * Jurusan
      * Mata Pelajaran
      * Ekstrakurikuler
      * Siswa
      * Kelas / Rombel
      * Guru
   * Data E-Learning
      * Jadwal Pelajaran
      * Materi
      * Tugas
      * Jadwal Materi/Tugas
   * Data Ujian
      * Jenis Ujian
      * Sesi
      * Ruang
      * Atur Ruang dan Sesi
      * Atur Nomor Peserta
      * Bank Soal
      * Jadwal
      * Alokasi Waktu
      * Token
   * Pengumuman

2. PELAKSANAAN
   * Hasil E-Learning
      * Nilai Harian
      * Kehadiran Harian
      * Kehadiran Bulanan
      * Rekap Nilai
   * Pelaksanaan Ujian
      * Cetak
      * Status Siswa
      * Hasil Ujian
      * Analisis Soal
      * Rekap Nilai Ujian

3. RAPOR
   * Setting Rapor
   * Kumpulan Nilai Rapor
   * Buku Induk
   * Alumni

4. PENGATURAN
   * Profile Sekolah
   * User Management
      * Administrator
      * Guru
      * Siswa
   * Database
      * Backup/Restore
      * Update

6. LOGOUT

___________
## version: 2.1.0
___________
#### Added
- Soal gambar menjodohkan
- Soal gambar tanpa text
- Search/paging rekap nilai
- Search kelas/rombel
- Search status ujian
- NIS list siswa di menu edit kelas
- Detect new tab ketika siswa sedang ujian

#### Fixed
- Rekap nilai 0
- Detail soal
- Typo
- Edit soal gambar hang
- Gambar soal di menu koreksi
- Hapus jadwal ujian
- Hapus siswa dari rombel
- Download soal ujian KP
- Edit soal ketika ujian berlangsung
- Mapel SD/MI
- Cetak rapor PTS beda predikat
- Kehadiran rapor di DKN
- Rapor prestasi berbeda dengan arsip
- Rapor kesehatan
- Ttd kepsek rapor akhir
- Mapel rapor berbeda dengan arsip

- Struktur organisasi ##admin
- Reset waktu ujian siswa #pengawas
- Search daftar siswa ada siswa lain kelas #wali kelas
- Tugas/Materi guru membaca kelas lain #guru
- Semua guru dianggap pengawas #pengawas
- Soal menjodohkan dianggap terjawab #siswa

______
MIT License

Copyright (c) 2025 The Debuggers / Team TA

