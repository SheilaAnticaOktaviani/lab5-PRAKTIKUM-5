# lab5-PRAKTIKUM-5
## Nama: SHEILA ANTICA OKTAVIANI
## Kelas: TI.24.A1
## NIM: 312410002

# Deskripsi

File ini berisi kumpulan contoh kode dasar JavaScript yang digunakan untuk memahami konsep fundamental pemrograman web menggunakan JavaScript.
Setiap bagian menunjukkan fungsi dan penggunaan elemen JavaScript seperti document.write, console.log, alert box, prompt, function, if-else, switch-case, serta manipulasi elemen HTML.

# Tujuan Pembelajaran

1. Memahami dasar penggunaan JavaScript dalam dokumen HTML. Mampu menampilkan output menggunakan document.write, console.log, dan alert. Mengenal penggunaan input user dengan prompt(). 
2. Mempelajari struktur kontrol seperti if-else dan switch-case.
3. Menggunakan fungsi (function) untuk menjalankan perintah.
4. Memanipulasi objek document seperti warna latar belakang dan teks.
5. Membuat perhitungan sederhana dengan event handler (misalnya onclick).
# Isi dan Penjelasan Setiap Bagian
1. Hello World
Menampilkan teks "Hello World" menggunakan:
## document.write("Hello World");
## console.log("Hello World");
Menunjukkan dua cara menampilkan output — ke layar (HTML) dan ke console browser.
# 2. Alert Box
Menampilkan pesan pop-up sederhana:
## window.alert("ini merupakan pesan untuk anda");
Berguna untuk memberi notifikasi atau informasi kepada pengguna.
# 3. Menampilkan Teks dengan document.write
## document.write("selamat mencoba javascript<br>");
## document.write("semoga sukses!");
Menampilkan teks langsung ke halaman web.
# 4. Input Menggunakan prompt
## var nama = prompt("siapa nama anda?", "masukkan nama anda");
## document.write("hai, " + nama);
Meminta pengguna memasukkan data melalui kotak dialog.
# 5. Fungsi dan Event onload
## function pesan() {
## alert("memanggil javascript lewat body onload");
## }
Menjalankan fungsi otomatis saat halaman dimuat.
# 6. Operasi Aritmatika
Menggunakan fungsi dengan tombol onclick:
## function test(val1, val2) {
   ## document.write("perkalian: " + (val1 * val2));
## }
Menampilkan hasil operasi matematika seperti tambah, kurang, kali, bagi, dan modulus.
# 7. Struktur Kendali if-else
## if (nilai >= 60)
    hasil = "lulus";
## else
    hasil = "tidak lulus";
Mengambil keputusan berdasarkan kondisi nilai.
# 8. Struktur Kendali switch-case
## switch (val1) {
    case "1": document.write("bilangan satu"); break;
    ...
}
Memilih hasil berdasarkan input angka tertentu.
# 9. Menentukan Bilangan Ganjil/Genap
## if (val1 % 2 == 0)
    document.kirim.T2.value = "bilangan genap";
## else
    document.kirim.T2.value = "bilangan ganjil";
    Mengambil input dari form dan menampilkan hasilnya.
# 10. Manipulasi Objek Document
## Mengubah warna latar belakang dan teks:
document.bgColor = warna;
document.fgColor = warna;
Contoh penggunaan DOM (Document Object Model).
# 11. Program Daftar Menu (Perhitungan Total)
## function hitung(ele) {
    var total = document.getElementById('total').value;
    ...
}
Menjumlahkan harga makanan berdasarkan checkbox yang dipilih pengguna.
# Cara Menjalankan
1. Buka file lab5_javascript.html di browser (Chrome, Edge, Firefox, dsb).
Amati hasil dari setiap bagian script.
2. Coba ubah nilai input atau perintah JavaScript untuk melihat perbedaan hasilnya.
# Kesimpulan
Melalui praktikum ini, kita belajar bagaimana JavaScript bekerja di dalam HTML untuk:
Menampilkan data ke layar.
Berinteraksi dengan pengguna.
Mengambil keputusan.
Melakukan perhitungan.
Mengubah elemen di halaman web secara dinamis.

# HASIL RUN DI WEB 
<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/ee304ee8-685e-4499-838f-d0678fc442d0" />

