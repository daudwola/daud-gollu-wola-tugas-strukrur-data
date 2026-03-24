**Sistem Pengelolaan Nilai Mahasiswa Sederhana**

Program Python sederhana untuk mengelola nilai 10 siswa menggunakan array (list di Python). Program ini mencakup nilai input, perhitungan statistik dasar, dan visualisasi grafik menggunakan matplotlib.

**1.Penjelasan Konsep Array**

**Array** adalah struktur data yang digunakan untuk menyimpan kumpulan elemen dengan **tipe data yang sama** dalam lokasi memori yang berurutan. Dalam Python, array paling umum diimplementasikan menggunakan tipe data list .

Dalam program ini, saya menggunakan list ( nilai = []) sebagai array satu dimensi untuk menyimpan nilai siswa. Karakteristik utama yang dimanfaatkan:

*Dinamis → bisa menambah elemen dengan.append()
*Diakses dengan indeks → nilai[0],nilai[3]
*Iterasi mudah→ bisa menggunakanfor n in nilai:
*Fungsi bawaan → max(), min(), sum(),len()

Kelebihan penggunaan list sebagai array di program ini:

*Mudah ditambah/dibaca oleh semua orang
*Mendukung operasi statistik sederhana tanpa perpustakaan tambahan (kecuali rata-rata)
*Cocok untuk data jumlah kecil hingga sedang

Kekurangan (jika skalanya besar):

*Operasi pencarian max/min/rata-rata tetap O(n)
*Tidak se-efisien array statistik dalam bahasa seperti C/C++ untuk akses sangat cepat

**2. Screenshot Hasil Eksekusi
Nilai masukan**
<img width="1259" height="308" alt="image" src="https://github.com/user-attachments/assets/afe5cca3-51e3-40e1-abca-88504c58698d" />

**Output teks di terminal**
<img width="798" height="272" alt="image" src="https://github.com/user-attachments/assets/92fd0632-31b1-4acd-a88a-9e225b7a1712" />

Bilah grafik (Min – Rata-rata – Maks)
<img width="1242" height="864" alt="image" src="https://github.com/user-attachments/assets/b0e3ebf3-d16a-4690-8c0b-0d3a716bcaff" />

3. Analisis Kompleksitas
   ![screenshot-1774286469210](https://github.com/user-attachments/assets/28df4c5d-8bc7-4f1e-811d-267f29e8a04f)

**Kesimpulan :** Program sangat efisien untuk skala kecil (10 siswa). Jika jumlah siswa menjadi jutaan, saya bisa optimasi dengan struktur data yang lebih baik (misal heap untuk max/min cepat), tetapi untuk kasus ini sudah sangat memadai.

4.Refleksi Pembelajaran
Melalui proyek ini saya belajar beberapa hal penting:

1.Pemahaman array/list di Python
List sangat fleksibel dan kuat untuk pemula, tetapi saya menyadari batasannya jika data sangat besar.

2.Validasi input
Menggunakan try-exceptdan loop whileuntuk memastikan input valid sangat penting agar program tidak crash.

3.Pemisahan logika
Memisahkan bagian input, proses, output, dan visualisasi membuat kode lebih mudah dibaca dan dimodifikasi.

4.Visualisasi data
Grafik sederhana dengan matplotlib membantu memahami distribusi nilai jauh lebih cepat dibandingkan hanya angka.

5.Tingkat kesulitan
Meskipun n kecil, saya mulai terbiasa berpikir tentang Big-O bahkan pada program sederhana.

Hal yang ingin saya tingkatkan pada proyek selanjutnya:

*Membuat input jumlah siswa dinamis menjadi (bukan fix 10)
*Menyimpan data ke file (CSV/JSON)
*Menambahkan fitur pencarian siswa berdasarkan nilai tertentu
*Mengimplementasikan max/min tanpa fungsi built-in (loop manual) untuk latihan lebih dalam

**Dibuat :Daud Golu wola**
