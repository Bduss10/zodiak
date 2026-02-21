Program ini merupakan aplikasi sederhana berbasis JavaScript yang dijalankan melalui terminal menggunakan Node.js. Program dibuat untuk menentukan zodiak berdasarkan tanggal dan bulan lahir yang dimasukkan oleh pengguna. Saat program dijalankan, sistem akan meminta user untuk menginput tanggal lahir dengan rentang 1 sampai 31 serta bulan lahir dengan rentang 1 sampai 12. Setelah data dimasukkan, program akan memproses input tersebut dan menampilkan hasil berupa tanggal lahir dalam format Bahasa Indonesia serta zodiak yang sesuai dengan rentang tanggal yang telah ditentukan.

Pada bagian awal kode, program mengimpor module readline yang berfungsi untuk menerima input dari terminal. Module ini memungkinkan interaksi langsung antara user dan program melalui command line. Setelah itu dibuat sebuah fungsi bernama tentukanZodiak yang berisi serangkaian percabangan if-else untuk menentukan zodiak berdasarkan kombinasi tanggal dan bulan. Setiap kondisi disusun sesuai dengan rentang tanggal masing-masing zodiak, seperti Aries yang berada pada rentang 21 Maret hingga 19 April, Taurus pada 20 April hingga 20 Mei, dan seterusnya hingga Pisces. Fungsi ini akan mengembalikan nama zodiak yang sesuai apabila input valid, dan akan menampilkan pesan kesalahan apabila tanggal atau bulan berada di luar batas yang ditentukan.

Selain itu, program juga menggunakan sebuah array bernama namaBulan yang berisi daftar nama bulan dalam Bahasa Indonesia, mulai dari Januari hingga Desember. Array ini digunakan untuk menampilkan hasil tanggal lahir dengan format yang lebih mudah dipahami oleh pengguna, sehingga output tidak hanya berupa angka bulan, tetapi juga nama bulan secara lengkap. Setelah user memasukkan data, program akan mengubah input menjadi tipe data integer menggunakan parseInt, kemudian melakukan validasi sederhana untuk memastikan bahwa tanggal berada dalam rentang 1–31 dan bulan dalam rentang 1–12. Jika input valid, maka program akan memanggil fungsi tentukanZodiak dan menampilkan hasil berupa tanggal lahir serta zodiak pengguna.

Program ini dapat dijalankan dengan membuka terminal pada folder project dan mengetikkan perintah node zodiak.js. Setelah itu, user dapat langsung memasukkan tanggal dan bulan lahir sesuai instruksi yang muncul di layar. Berdasarkan beberapa percobaan yang telah dilakukan, program berjalan dengan baik dan mampu menampilkan hasil zodiak sesuai dengan input yang diberikan. Pada dokumentasi repository ini juga disertakan minimal tiga screenshot hasil percobaan yang menunjukkan proses input dan output program di terminal sebagai bukti bahwa program berfungsi dengan benar.


Sebagai bukti bahwa program berjalan dengan baik, berikut ditampilkan beberapa hasil percobaan saat program dijalankan melalui terminal.

![Percobaan 1](screenshots/screenshot1.png)

![Percobaan 2](screenshots/screenshot2.png)

![Percobaan 3](screenshots/screenshot3.png)
