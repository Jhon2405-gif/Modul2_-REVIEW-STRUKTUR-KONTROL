# Modul2_-REVIEW-STRUKTUR-KONTROL
2311102221

**Bagian 2A**

1.Program ini digunakan untuk menukar tiga input string yang dimasukkan pengguna.
2.Program ini berfungsi untuk menentukan apakah tahun yang dimasukkan pengguna merupakan tahun kabisat.
3.Program ini menghitung volume dan luas permukaan bola berdasarkan input radius yang diberikan pengguna.
4.Program ini mengonversi suhu dalam Celsius yang diinput pengguna ke dalam satuan Reamur, Kelvin, dan Fahrenheit.
5.Program ini mengubah input pengguna berupa dua baris: baris pertama terdiri dari 5 angka integer yang akan dicetak dalam format karakter, dan baris kedua terdiri dari 3 karakter yang masing-masing akan ditambahkan 1 sebelum dicetak.

**Bagian 2B**

1.Program ini memverifikasi apakah 4 warna yang diinput pengguna sudah berurutan benar, dan akan mencetak boolean true jika benar.
2.Program ini mencetak "n" sebanyak input pengguna, lalu meminta pengguna memasukkan "n" nama bunga yang akan disatukan dengan tanda "-" di antaranya.
3.Program ini memeriksa apakah beban belanjaan Pak Andi membuat motor oleng dengan menghitung total beban minimum serta selisih beban di sisi kanan dan kiri.
4.Program ini menghitung akar kuadrat dari angka yang diinput pengguna.

**Bagian 2C**

1.Program ini menghitung biaya pengiriman berdasarkan berat parcel yang diinput pengguna dalam gram. Berat dikonversi ke kilogram dan gram, dan biaya dihitung berdasarkan tarif Rp. 10.000 per kilogram.

2.Program ini menghitung nilai akhir mata kuliah dari input pengguna, dan menampilkan hasil berupa nilai abjad ("A", "AB", "B", "BC", "C", "E").

i. Jika nilai nam adalah 80.1, apa outputnya? Apakah sesuai spesifikasi? Jawaban: Program error karena variabel nam dideklarasikan sebagai float64, tetapi program mencoba menetapkan string ke nam.

ii. Apa kesalahan program? Mengapa demikian? Kesalahan program:

nam dideklarasikan sebagai float64, tetapi program memasukkan string sebagai nilainya.
Kondisi if tidak terstruktur, sehingga beberapa blok if dapat berjalan dan mengubah nilai nmk berturut-turut.
Sebagai contoh, jika nam = 80.1, semua kondisi ini dapat terpenuhi berturut-turut, menyebabkan nmk bernilai "D" yang tidak sesuai spesifikasi.

Perbaikan Program:

Ganti nam = "A" dengan nmk = "A" untuk semua kondisi.
Gunakan else if agar hanya satu kondisi terpenuhi dan nilai nmk tidak ditimpa.
iii. Perbaiki dan uji program dengan input: 93.5, 70.6, dan 49.5. Seharusnya hasilnya 'A', 'B', dan 'D'.

Program ini mengecek apakah angka input pengguna adalah bilangan prima dengan memeriksa faktor-faktornya.
