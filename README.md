**Sistem Pengelolaan Nilai Mahasiswa Sederhana**
Program Python sederhana untuk mengelola nilai 10 siswa menggunakan array (list di Python). Program ini mencakup nilai input, perhitungan statistik dasar, dan visualisasi grafik menggunakan matplotlib.

**1.Penjelasan Konsep Array**
Array adalah struktur data yang digunakan untuk menyimpan kumpulan elemen dengan tipe data yang sama dalam lokasi memori yang berurutan. Dalam Python, array paling umum diimplementasikan menggunakan tipe data list .

Dalam program ini, saya menggunakan list ( nilai = []) sebagai array satu dimensi untuk menyimpan nilai siswa. Karakteristik utama yang dimanfaatkan:

Dinamis → bisa menambah elemen dengan.append()
Diakses dengan indeks → nilai[0],nilai[3]
Iterasi mudah→ bisa menggunakanfor n in nilai:
Fungsi bawaan → max(), min(), sum(),len()
Kelebihan penggunaan list sebagai array di program ini:

Mudah ditambah/dibaca
Mendukung operasi statistik sederhana tanpa perpustakaan tambahan (kecuali rata-rata)
Cocok untuk data jumlah kecil hingga sedang
Kekurangan (jika skalanya besar):

Operasi pencarian max/min/rata-rata tetap O(n)
Tidak se-efisien array statistik dalam bahasa seperti C/C++ untuk akses sangat cepat
**2. Screenshot Hasil Eksekusi
Nilai masukan**
