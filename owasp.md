# Prompt AI - Fitur Keamanan Website X-TECH (Puzzle Investigasi ala OWASP)

Tambahkan fitur investigasi keamanan pada website perusahaan fiktif **X-TECH** sebagai bagian dari gameplay visual novel.

Website harus terlihat seperti website startup teknologi profesional, namun memiliki beberapa celah dan petunjuk tersembunyi yang sengaja dibuat sebagai bagian dari cerita.

**Penting:**

* Jangan membuat eksploitasi nyata yang dapat digunakan pada website sungguhan.
* Semua "kerentanan" hanya berupa puzzle, petunjuk, atau simulasi yang aman.
* Tujuannya adalah membuat pemain merasa seperti sedang melakukan investigasi digital.

---

## Halaman Tersembunyi

Buat beberapa halaman yang tidak muncul pada menu navigasi.

Contoh:

* /arsip
* /internal
* /prototype
* /chronos
* /research/alpha
* /dokumen
* /old-site

Halaman tersebut hanya dapat ditemukan melalui eksplorasi.

---

## robots.txt

Tambahkan halaman robots.txt yang berisi beberapa direktori yang sengaja disembunyikan.

Contoh isi:

* /internal/
* /prototype/
* /chronos/
* /arsip/

Direktori tersebut menjadi petunjuk untuk eksplorasi berikutnya.

---

## sitemap.xml

Buat sitemap.xml yang menampilkan beberapa halaman publik serta beberapa halaman yang sebenarnya tidak memiliki tautan pada website.

Pemain dapat menemukan halaman tersebut melalui sitemap.

---

## Source Code

Tambahkan komentar HTML yang tampak seperti catatan developer.

Contoh:

* TODO: Hapus halaman prototype sebelum rilis.
* TODO: Ganti password server internal.
* Jangan lupa hapus Project Chronos.

Komentar hanya berfungsi sebagai petunjuk cerita.

---

## Halaman Error

Buat halaman:

* 403 Forbidden
* 404 Not Found
* 500 Internal Error

Namun halaman tersebut tetap memberikan sedikit informasi mengenai dunia X-TECH.

Misalnya:

* nomor referensi
* kode proyek
* ID eksperimen
* tanggal misterius

---

## Arsip Lama

Buat halaman arsip yang berisi:

* berita lama
* press release
* foto kegiatan
* dokumen PDF
* laporan penelitian

Beberapa arsip mengandung informasi yang bertentangan dengan informasi terbaru.

---

## Metadata Dokumen

Dokumen PDF atau gambar memiliki metadata sederhana seperti:

* penulis
* tanggal pembuatan
* divisi penelitian
* nama proyek

Metadata dapat menjadi petunjuk menuju cerita berikutnya.

---

## Direktori Internal

Buat beberapa halaman internal yang menampilkan:

* "Access Restricted"
* "Employee Only"
* "Classified"

Halaman tetap dapat diakses, tetapi sebagian besar isinya disensor.

---

## Portal Karyawan

Tambahkan halaman login khusus karyawan.

Login tidak perlu benar-benar berfungsi.

Namun halaman tersebut dapat berisi:

* pengumuman internal
* jadwal rapat
* nama divisi
* ID pegawai
* poster perusahaan

---

## API Simulasi

Buat halaman yang menyerupai dokumentasi API internal.

Contoh:

* Daftar proyek
* Daftar laboratorium
* Daftar divisi
* Status server

Semua data bersifat fiktif.

---

## Versi Sistem

Tambahkan informasi versi sistem pada footer atau halaman tertentu.

Contoh:

* X-TECH Portal v3.4
* Research Platform v5.1

Versi tersebut nantinya dapat digunakan sebagai petunjuk dalam cerita.

---

## Halaman Proyek Rahasia

Beberapa proyek diberi status:

* Rahasia
* Terbatas
* Diklasifikasikan

Misalnya:

* Project CHRONOS
* Project ECHO
* Project NEXUS
* Project HELIOS
* Project SENTINEL

Sebagian informasi disensor menggunakan blok hitam.

---

## Pesan Tersembunyi

Sisipkan petunjuk kecil pada berbagai halaman, misalnya:

* footer
* komentar HTML
* metadata
* nama file
* ID proyek
* kode referensi
* tanggal
* nomor eksperimen

Semua petunjuk saling berhubungan sehingga pemain dapat menghubungkan satu halaman dengan halaman lainnya.

---

## Tingkat Kesulitan Bertahap

Rancang investigasi menjadi beberapa level.

### Level 1

Pemain hanya perlu menjelajahi halaman website.

### Level 2

Pemain mulai membaca robots.txt dan sitemap.xml.

### Level 3

Pemain menemukan komentar developer pada source HTML.

### Level 4

Pemain menghubungkan informasi dari berbagai halaman.

### Level 5

Pemain berhasil membuka halaman proyek rahasia dan memperoleh informasi penting mengenai cerita.

---

## Tujuan Desain

Website harus terasa seperti website startup teknologi sungguhan.

Sekitar **95% isi website merupakan informasi perusahaan yang normal**, sedangkan **5% sisanya berupa petunjuk misterius** yang perlahan membuka rahasia X-TECH.

Pemain tidak boleh langsung menyadari bahwa website ini merupakan bagian dari puzzle. Semua petunjuk harus terasa alami, realistis, dan konsisten dengan citra perusahaan teknologi profesional.
