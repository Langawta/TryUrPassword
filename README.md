==================================================
TryUrPassword
Aplikasi Edukasi Keamanan Password
==================================================

Dibuat oleh : [Langawta]
KELAS : [XII]

==================================================

1. TUJUAN
--------------------------------------------------
Banyak orang memakai password yang lemah dan mudah
ditebak. TryUrPassword membantu pengguna menilai
kekuatan password, melihat bagaimana serangan bisa
terjadi, dan belajar cara mengamankan akun.

Aplikasi ini murni untuk edukasi. Tidak ada serangan
nyata, dan tidak ada alat untuk menyerang pihak lain.


2. CARA MEMBUKA
--------------------------------------------------
1. Jika file berupa zip, klik kanan lalu pilih
   "Extract All" terlebih dahulu.
2. Klik dua kali file "index.html".
3. Halaman terbuka di browser (Chrome, Edge, atau
   Firefox).

Tidak perlu instalasi, server, atau koneksi internet.
Hanya fitur "pemeriksaan online" pada Cek Link yang
membutuhkan internet (bersifat pilihan).


3. FITUR
--------------------------------------------------
a. Cek Password
   - Menilai kekuatan password dan memberi saran.
   - Memperkirakan waktu yang dibutuhkan untuk menebak.
   - Simulasi serangan brute force (animasi edukasi),
     lengkap dengan tampilan notifikasi sisi korban.

b. Uji Keamanan
   - Cek Link (pendeteksi phishing): menganalisis pola
     alamat dan memberi skor risiko 0 sampai 100.
   - Duel Password: membandingkan dua password.
   - Asli atau Phishing: latihan mengenali penipuan.
   - Kuis keamanan.

c. Latihan Praktik
   - Generator password acak.
   - Amankan Akun: latihan memulihkan akun yang dibobol.
   - Respons Darurat: simulasi 60 detik menangani
     kebocoran akun.

d. Belajar Sandi
   - Pengenalan sandi, materi, statistik, glosarium,
     dan FAQ.
   - Demo Sandi Caesar dan hash.


4. KEAMANAN DAN PRIVASI
--------------------------------------------------
- Semua proses berjalan di browser pengguna.
- Password yang diketik TIDAK disimpan dan TIDAK
  dikirim ke server mana pun.
- Skor dan progres latihan disimpan di browser
  pengguna sendiri (penyimpanan lokal).
- Pemeriksaan online pada Cek Link bersifat pilihan.
  Jika dicentang, hanya nama domain yang dikirim ke
  layanan dns.google dan rdap.org.
- PENTING: jangan memasukkan password yang dipakai
  sungguhan. Gunakan password contoh.


5. BATASAN
--------------------------------------------------
- Perkiraan waktu menebak password hanya kasar dan
  bergantung pada asumsi kemampuan penyerang.
- Pendeteksi phishing membaca pola alamat, bukan isi
  situsnya, sehingga bukan jaminan 100%. Sistem
  profesional juga memeriksa daftar hitam dan isi
  halaman.
- Simulasi serangan hanya animasi edukasi.


6. TEKNOLOGI
--------------------------------------------------
Satu file HTML dengan CSS dan JavaScript di
dalamnya. Tanpa library atau skrip dari luar.


7. ISI FOLDER
--------------------------------------------------
index.html   : aplikasi (file utama)
README.txt   : panduan ini
