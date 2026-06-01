# 🎨 Laporan Evaluasi UI/UX

## 📲Halaman Home, Login, Register

---

## 1. Responsive & User-Friendly

### Status

✅ aman

### Catatan

* Tampilan tetap rapi dan konsisten pada Desktop, Tablet, maupun Mobile

---

## 2. Typography, Proportion & Precision

### Issue

* Logo masih memiliki border/latar belakang putih yang cukup terlihat
* Ukuran card Login dan Register terlihat sedikit terlalu lebar sehingga proporsi halaman terasa kurang seimbang

### Suggestion

* Hapus border/latar belakang putih pada logo
* Sesuaikan lebar card Login dan Register agar tampilannya lebih proporsional (biar ga terlihat gendut:( ).

---

## 3. Input Validation

### Issue

* Pesan validasi NIM menampilkan "NIM hanya boleh angka", padahal masalah yang terjadi adalah jumlah digit yang belum memenuhi ketentuan minimum
* Pesan validasi pada field kosong masih menggunakan tanda titik (.) di akhir kalimat
* Ukuran font pesan validasi hampir sama dengan ukuran font input sehingga kurang nyaman dilihat sih

### Suggestion

* Ubah pesan validasi NIM menjadi lebih spesifik, misalnya: **"NIM minimal 5 digit"**
* Hilangkan tanda titik (.) pada pesan validasi field kosong agar lebih konsisten
* Gunakan weight/size font yang sedikit lebih kecil untuk pesan validasi dibandingkan teks input
<img width="243" height="108" alt="image" src="https://github.com/user-attachments/assets/bd335901-49c7-4106-a431-32ce35d92c6f" />

---

## 4. Alert & Notification System

### Issue

* Notifikasi "Login Berhasil" masih kurang menonjol sehingga feedback keberhasilannya terasa kurang terlihat

### Suggestion

* Gunakan warna hijau pada font atau elemen notifikasi sukses agar lebih mudah dikenali sebagai status berhasil
<img width="207" height="66" alt="image" src="https://github.com/user-attachments/assets/12d46c94-0e8c-40f5-9830-080cf6476f60" />

---

## 5. Informative Message & User Stress

### Issue

* Pada halaman Register belum tersedia opsi cepat untuk menuju halaman Login jika pengguna ternyata sudah memiliki akun

### Suggestion

* Tambahkan teks like this maybe **"Sudah punya akun? Masuk di sini"** di bawah tombol Register agar pengguna dapat langsung berpindah ke halaman Login dengan satu klik

---

## 📖Halaman Mahasiswa dan Dosen

---

## 1. Responsive & User-Friendly

### Issue

* Sidebar tidak muncul pada tampilan Mobile sehingga beberapa menu menjadi sulit diakses

### Suggestion

* Tambahkan menu sidebar versi Mobile agar fitur tetap dapat diakses pada layar kecil

---

## 2. Typography, Proportion & Precision

### Issue

* Teks placeholder **"Tulis pertanyaanmu di sini"** terlihat terlalu besar
* Kotak chat awal terlihat seperti elemen statis dan biasa aja, jadi kurang eye catching
* Ukuran font judul **"RAG Hub"** terasa sedikit kurang besar dibandingkan elemen utama lainnya
* Ikon History terlihat seperti tombol, tetapi saat dicoba belum dapat diklik (mau dibuat bisa di klik or engga?)
* Tombol Logout kurang memiliki feedback visual saat disentuh atau diarahkan kursor
* Judul halaman di page Dosen terlihat terlalu besar jadi seperti mendominasi tampilan
* Bagian atas halaman tidak tetap (sticky) saat pengguna melakukan scroll, jadi misal list banyak dan tb" mau add kb harus balik ke atas jauh
* Tombol **Kelola** kurang menonjol dibandingkan elemen lainnya, tidak seperti button

### Suggestion

* Kurangi ukuran font pada placeholder **"Tulis pertanyaanmu di sini"**
* Berikan efek hover atau focus yang lebih terlihat pada kotak chat agar lebih eye catching
* Sedikitt perbesar ukuran font judul **"RAG Hub"** agar lebih menonjol
* Jika ikon History memang berfungsi sebagai tombol, pastikan dapat diklik dan memberikan feedback visual
* Tambahkan efek hover pada tombol Logout, misalnya latar merah muda/merah soft dengan teks tetap berwarna merah
* Sesuaikan ukuran beberapa judul agar proporsi halaman lebih seimbang
* Pertimbangkan menggunakan header sticky (stay) agar menu utama tetap terlihat saat scroll
* Buat tombol **Kelola** lebih menonjol, misalnya dengan warna, ukuran, atau kontras yang lebih jelas.

---

## 3. Input Validation

### Issue

* Bubble chat masih belum dapat dibuka 
### Suggestion

---

## 4. Alert & Notification System

### Issue

* 

### Suggestion

* 

---

## 5. Informative Message & User Stress

### Issue

* 

### Suggestion

* 

---

## Prioritas Perbaikan

### Prioritas Tinggi

* Perbaikan pesan validasi NIM
* Penyesuaian ukuran card Login dan Register
* Penyesuaian ukuran font pesan validasi
* Peningkatan visual notifikasi "Login Berhasil"
* Perbaikan sidebar pada tampilan Mobile
* Perbaikan hover pada kotak chat mhs

### Prioritas Sedang

* Perbaikan ukuran dan hierarki teks pada halaman Role Mahasiswa dan Dosen
* Peningkatan visibilitas tombol Kelola

### Prioritas Rendah

* Penghapusan border putih pada logo
* Penambahan efek hover pada beberapa tombol dan komponen
* Penyempurnaan konsistensi pesan validasi dan feedback visual
