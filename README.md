Sistem Pengelolaan Nilai Mahasiswa Sederhana

Program Python sederhana untuk mengelola nilai 10 mahasiswa menggunakan array (list di Python). Program ini mencakup input nilai, perhitungan statistik dasar, dan visualisasi grafik menggunakan matplotlib.

Penjelasan Konsep Array

Array adalah struktur data yang digunakan untuk menyimpan kumpulan elemen dengan tipe data yang sama dalam lokasi memori yang berurutan . Dalam Python, array paling umum diimplementasikan menggunakan tipe data list.

Dalam program ini, saya menggunakan list (nilai = []) sebagai array satu dimensi untuk menyimpan nilai mahasiswa. Karakteristik utama yang dimanfaatkan:

* Dinamis → bisa menambah elemen dengan .append()
* Diakses dengan indeks → nilai[0], nilai[3]
* Iterasi mudah→ bisa menggunakan for n in nilai:
* Built-in functions → max(), min(), sum(), len()
  
Kelebihan penggunaan list sebagai array di program ini:

* Mudah ditambah/dibaca
* Mendukung operasi statistik sederhana tanpa library tambahan (kecuali rata-rata)
* Cocok untuk data jumlah kecil hingga sedang
  
Kekurangan (jika skalanya besar):

* Operasi pencarian max/min/rata-rata tetap O(n)
* Tidak se-efisien array statis di bahasa seperti C/C++ untuk akses sangat cepat
2. Screenshot Hasil Eksekusi
  
Input nilai
<img width="1259" height="308" alt="image" src="https://github.com/user-attachments/assets/4de1bb10-3696-4b50-a362-0f845fdbf76d" />


Output teks di terminal
<img width="798" height="272" alt="image" src="https://github.com/user-attachments/assets/660bf5f0-493a-4a12-a5c2-2611b97c67bd" />


Grafik bar (Min – Avg – Max)
<img width="1242" height="864" alt="image" src="https://github.com/user-attachments/assets/3552acab-8a03-41d3-8245-c4d1dd5c4283" />



3. Analisis Kompleksitas

   ![screenshot-1774286469210](https://github.com/user-attachments/assets/eab93642-6954-45d5-b9ed-36930ea3a204)


Kesimpulan: Program sangat efisien untuk skala kecil (10 mahasiswa). Jika jumlah mahasiswa menjadi jutaan, saya bisa optimasi dengan struktur data yang lebih baik (misal heap untuk max/min cepat), tapi untuk kasus ini sudah sangat memadai.

Refleksi Pembelajaran
Melalui proyek ini saya belajar beberapa hal penting:

Pemahaman array/list di Python
List sangat fleksibel dan powerful untuk pemula, tapi saya menyadari batasannya jika data sangat besar.

Input validation
Menggunakan try-except dan loop while untuk memastikan input valid sangat penting agar program tidak crash.

Pemisahan logika
Memisahkan bagian input, proses, output, dan visualisasi membuat kode lebih mudah dibaca dan dimodifikasi.

Visualisasi data
Grafik sederhana dengan matplotlib membantu memahami distribusi nilai jauh lebih cepat dibandingkan hanya angka.

Kesadaran kompleksitas
Meskipun n kecil, saya mulai terbiasa berpikir tentang Big-O bahkan pada program sederhana.

Hal yang ingin saya tingkatkan di proyek selanjutnya:

Membuat input jumlah mahasiswa menjadi dinamis (bukan fix 10)
Menyimpan data ke file (CSV/JSON)
Menambahkan fitur pencarian mahasiswa berdasarkan nilai tertentu
Mengimplementasikan max/min tanpa fungsi built-in (loop manual) untuk latihan lebih dalam# daud-gollu-wola-tugas-strukrur-data
