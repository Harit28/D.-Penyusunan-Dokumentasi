# ADMINISTRASI SEKOLAH

## Deskripsi
Sistem ini dirancang untuk mengelola data sekolah seperti siswa, guru, spp, Admin, dan jadwal. Dilengkapi dengan fitur CRUD, dan antarmuka yang responsif.

## Fitur
- CRUD data siswa, guru, spp, Admin, dan jadwal.
- Desain responsif.
- Input Nama, Email, Kata Sandi, dan Pesan
- Dropdown untuk memilih Peran (Admin, Moderator, User)
- Desain modern dengan validasi dasar pada input
 Teknologi yang Digunakan
•	HTML5: Struktur halaman
•	CSS3: Desain dan tata letak responsif
 Cara Menggunakan
1.	Salin kode di atas dan simpan sebagai index.html.
2.	Buka file di browser.
3.	Isi formulir dan klik Submit.
 Form Action
•	Data akan dikirim ke endpoint /submit dengan metode POST.
Admin List - README
 Deskripsi Singkat
Halaman ini menampilkan daftar admin dalam bentuk tabel dengan informasi seperti Nama Admin, Email, Peran, dan opsi Edit serta Delete untuk setiap entri.
 Fitur Utama
•	Tampilan tabel untuk daftar admin.
•	Kolom yang mencakup: No, Nama Admin, Email, Peran, dan Aksi.
•	Tombol Edit dan Delete untuk setiap baris data.
•	Struktur yang mudah diperluas dengan lebih banyak data admin.
 Teknologi yang Digunakan
•	HTML5: Struktur dasar halaman.
•	CSS (styles.css): Untuk desain dan tata letak yang lebih baik.
 Cara Menggunakan
1.	Salin kode di atas dan simpan sebagai admin_list.html.
2.	Pastikan file styles.css tersedia di direktori yang sama.
3.	Buka file di browser untuk melihat tampilan tabel admin.
 Customisasi
•	Tambahkan lebih banyak baris data di dalam <tbody>.
•	Ubah URL aksi pada tombol Edit dan Delete agar sesuai dengan logika backend.
 Catatan
•	Aksi tombol Edit dan Delete saat ini hanya berupa tautan dummy (#).
•	Integrasikan dengan backend untuk menangani aksi yang sebenarnya.
Login Page - README
 Deskripsi Singkat
Halaman login yang responsif dan ramah pengguna dengan input untuk Email dan Password, serta tombol untuk mengirimkan data login.
 Fitur Utama
•	Input Email dan Password dengan validasi dasar.
•	Tombol Login dengan efek hover.
•	Tautan ke halaman Register untuk pengguna yang belum memiliki akun.
•	Desain responsif dan modern.
 Teknologi yang Digunakan
•	HTML5: Struktur dasar halaman.
•	CSS3: Desain dan efek interaktif.

 Cara Menggunakan
1.	Simpan kode di atas sebagai login.html.
2.	Buka file di browser untuk melihat tampilan halaman login.
3.	Formulir akan mengirim data ke endpoint /login dengan metode POST.
 Customisasi
•	Ubah atribut action pada tag <form> agar sesuai dengan endpoint backend Anda.
•	Sesuaikan warna dan gaya di dalam bagian <style> sesuai dengan tema proyek.
 Navigasi Tambahan
•	Pengguna dapat mengakses halaman Register melalui tautan di bagian bawah formulir.
 Catatan
•	Pastikan backend mendukung endpoint /login untuk memproses kredensial pengguna dengan aman.
•	Gunakan protokol HTTPS untuk keamanan data saat login.
Logout Button - README
 Deskripsi Singkat
Halaman sederhana dengan tombol Log Out yang memungkinkan pengguna untuk keluar dari sesi mereka dengan mudah.
 Fitur Utama
•	Tombol Log Out yang mudah diakses.
•	Mengarahkan pengguna ke endpoint /logout untuk memproses sesi logout.
•	Desain sederhana dan dapat disesuaikan dengan file styles.css.
 Teknologi yang Digunakan
•	HTML5: Struktur halaman dasar.
•	CSS (styles.css): Untuk gaya dan tata letak tombol logout.
 Cara Menggunakan
1.	Simpan kode di atas sebagai logout.html.
2.	Pastikan file styles.css tersedia di direktori yang sama.
3.	Pastikan endpoint /logout di backend sudah dikonfigurasi untuk menangani proses logout.
4.	Buka halaman di browser untuk menguji tombol logout.
 Customisasi
•	Ubah tautan di atribut href untuk menyesuaikan dengan endpoint logout pada backend Anda.
•	Sesuaikan tampilan tombol di dalam file styles.css.
 Catatan
•	Pastikan backend menangani sesi pengguna dengan benar setelah logout.
•	Setelah logout, arahkan pengguna kembali ke halaman login atau halaman utama.
Main Page - README
 Deskripsi Singkat
Halaman utama sederhana yang berisi Header, Navigasi, Konten Utama, dan Footer. Desain responsif dengan tampilan yang ramah pengguna untuk menavigasi berbagai bagian situs.
 Fitur Utama
•	Header: Judul halaman utama.
•	Navigasi: Tautan ke bagian Home, About, Services, dan Contact.
•	Konten Utama: Menyediakan informasi utama dengan judul dan paragraf deskriptif.
•	Footer: Hak cipta dengan informasi singkat di bagian bawah halaman.
•	Responsif: Tampilan ramah pengguna di berbagai perangkat.
 Teknologi yang Digunakan
•	HTML5: Struktur halaman.
•	CSS3: Desain dan tata letak halaman.
 Cara Menggunakan
1.	Salin kode di atas dan simpan sebagai index.html.
2.	Buka file di browser untuk melihat halaman utama.
3.	Navigasikan menggunakan tautan di bagian menu untuk berpindah antar bagian.
 Customisasi
•	Ubah warna tema dengan mengedit bagian CSS.
•	Tambahkan lebih banyak tautan di bagian navigasi jika diperlukan.
•	Sesuaikan konten utama dengan teks atau elemen tambahan sesuai kebutuhan.
 Catatan
•	Pastikan tautan navigasi mengarah ke bagian yang sesuai dalam halaman atau ke halaman eksternal yang valid.
•	Pastikan konten diperbarui secara berkala untuk menjaga relevansi informasi.
Printable Page - README
 Deskripsi Singkat
Halaman ini dirancang untuk menampilkan dokumen yang dapat dicetak dengan mudah. Terdapat tabel data dan tombol Print untuk mencetak langsung melalui peramban.
 Fitur Utama
•	Tata Letak Terpusat: Kontainer yang terstruktur dengan baik untuk tampilan yang bersih.
•	Tabel Data: Tampilan tabel yang rapi dengan header dan baris data.
•	Tombol Print: Memungkinkan pengguna mencetak halaman langsung dengan sekali klik.
•	Mode Cetak Khusus: Tampilan dioptimalkan untuk hasil cetak yang lebih baik.
 Teknologi yang Digunakan
•	HTML5: Struktur dasar halaman web.
•	CSS3: Styling untuk tampilan layar dan mode cetak.
•	JavaScript: Fungsi sederhana untuk menangani aksi cetak.
 Cara Menggunakan
1.	Simpan kode di atas sebagai printable.html.
2.	Buka file di browser.
3.	Klik tombol "Print" untuk mencetak halaman atau gunakan pintasan keyboard (Ctrl+P di Windows atau Cmd+P di Mac).
4.	Pratinjau hasil cetak dan cetak dokumen.
 Customisasi
•	Tambahkan atau ubah data di dalam tabel sesuai kebutuhan.
•	Sesuaikan desain melalui bagian CSS (warna, margin, atau font).
•	Ubah judul dokumen dengan mengedit elemen <div class="print-title">.
 Catatan
•	Elemen seperti tombol Print akan otomatis disembunyikan saat halaman dicetak.
•	Pastikan pengaturan cetak di browser sesuai untuk hasil terbaik.
SPP Payment Form - README
 Deskripsi Singkat
Halaman SPP Payment Form memungkinkan pengguna untuk mengisi data pembayaran SPP siswa dengan mudah dan cepat. Formulir ini mencakup detail penting seperti nama siswa, ID siswa, kelas, bulan pembayaran, dan jumlah pembayaran.
 Fitur Utama
•	Input Nama Siswa: Memasukkan nama siswa yang melakukan pembayaran.
•	Input ID Siswa: Memasukkan ID unik siswa.
•	Pemilihan Kelas: Dropdown untuk memilih kelas siswa.
•	Pemilihan Bulan Pembayaran: Dropdown untuk memilih bulan pembayaran.
•	Input Jumlah Pembayaran: Memasukkan jumlah pembayaran dalam format numerik.
•	Validasi Formulir: Semua kolom wajib diisi sebelum formulir dikirim.
•	Tombol Kirim: Mengirim data pembayaran ke server.
 Teknologi yang Digunakan
•	HTML5: Struktur dasar halaman web.
•	CSS3: Styling untuk tampilan halaman yang responsif dan menarik.
•	JavaScript (Opsional): Bisa ditambahkan untuk validasi atau interaksi lebih lanjut.
 Cara Menggunakan
1.	Simpan file ini sebagai spp_payment.html.
2.	Buka file di browser.
3.	Isi formulir dengan informasi yang benar.
4.	Klik tombol "Submit Payment" untuk mengirim data.
5.	Pastikan server memiliki endpoint /submit-spp untuk menangani data formulir.
 Customisasi
•	Tambahkan lebih banyak kelas atau bulan di dalam elemen <select>.
•	Ubah warna tema dengan mengedit bagian CSS.
•	Tambahkan validasi tambahan menggunakan JavaScript.
 Struktur Formulir
•	Student Name: Input teks untuk nama siswa.
•	Student ID: Input teks untuk ID siswa.
•	Class: Dropdown untuk memilih kelas.
•	Payment Month: Dropdown untuk memilih bulan pembayaran.
•	Amount (IDR): Input numerik untuk jumlah pembayaran.
 Validasi Formulir
•	Semua kolom wajib diisi.
•	Kolom jumlah hanya menerima angka.
 Catatan Tambahan
•	Pastikan server siap menerima data formulir dengan metode POST di endpoint /submit-spp.
•	Gunakan protokol HTTPS untuk keamanan data pembayaran.


Data Table - README
 Deskripsi Singkat
Halaman Data Table menampilkan data siswa dalam format tabel yang rapi dan mudah dibaca. Desain ini mencakup judul tabel, baris data siswa, serta elemen footer untuk memberikan tampilan yang profesional.
________________________________________
 Fitur Utama
•	Struktur Tabel yang Rapi: Tampilan tabel dengan header, baris data, dan footer.
•	Highlight Baris: Efek hover untuk memudahkan pengguna membaca data.
•	Warna Baris Berselang: Pola warna selang-seling untuk meningkatkan keterbacaan.
•	Responsif: Tabel dapat diakses dengan baik di berbagai perangkat.
•	Desain Modern: Menggunakan warna modern dengan tampilan profesional.
________________________________________
 Teknologi yang Digunakan
•	HTML5: Struktur dasar halaman web.
•	CSS3: Styling untuk tata letak dan estetika halaman.
________________________________________
 Cara Menggunakan
1.	Simpan file ini sebagai data_table.html.
2.	Buka file di browser.
3.	Lihat tabel data siswa yang disusun rapi.
4.	Jika diperlukan, tambahkan atau edit data di dalam elemen <tbody>.
5.	![image](https://github.com/user-attachments/assets/1779c331-b0be-4206-8ba3-4056cb64d12b)

 
Customisasi
•	Tambahkan lebih banyak baris dengan menyalin elemen <tr> dalam <tbody>.
•	Ubah warna tabel dengan mengedit bagian CSS:
![image](https://github.com/user-attachments/assets/9bd3cfa8-94a8-4146-b8bd-83c38ece68ae)

 
•	Sesuaikan gaya hover atau warna baris sesuai kebutuhan.
________________________________________
 Validasi Data
•	Pastikan setiap baris data berisi informasi yang lengkap.
•	Format tabel harus konsisten di setiap baris.
________________________________________
 Catatan Tambahan
•	Halaman ini hanya menampilkan data statis. Untuk menambahkan data dinamis, Anda dapat menghubungkan tabel dengan backend menggunakan JavaScript atau server-side scripting seperti PHP atau Node.js.

