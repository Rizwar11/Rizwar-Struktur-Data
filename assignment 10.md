# LAPORAN PRAKTIKUM - HEAP DAN PRIORITY QUEUE

Nama : Rizwar Syaefulloh

NRP : 2C2230009

Prodi : Sains Data

## 1. Judul Praktikum
Modul 10: Heap dan Priority Queue

## 2. Tujuan Praktikum
Praktikum ini bertujuan untuk memberikan pemahaman mengenai konsep Heap sebagai struktur data berbasis *Tree*, perbedaan Min Heap dan Max Heap, implementasi operasi dasarnya, serta penerapan *Priority Queue* untuk menyelesaikan studi kasus dunia nyata menggunakan bahasa pemrograman Python.

## 3. Dasar Teori
**Heap** adalah struktur data berbentuk *Complete Binary Tree* yang digunakan untuk menyimpan data berdasarkan prioritas. Terdapat dua jenis Heap, yaitu:
*   **Max Heap:** Nilai *parent* selalu lebih besar atau sama dengan *child*-nya, sehingga nilai terbesar berada di *root*.
*   **Min Heap:** Nilai *parent* selalu lebih kecil atau sama dengan *child*-nya, sehingga nilai terkecil berada di *root*.

Berbeda dengan *Queue* biasa yang menggunakan prinsip FIFO (*First In First Out*), *Priority Queue* (yang diimplementasikan dengan Heap) memproses elemen berdasarkan prioritas tertinggi terlebih dahulu. Operasi penambahan (*insert*) dan penghapusan (*delete*) pada Heap memiliki kompleksitas waktu $O(log\ n)$, menjadikannya sangat efisien untuk manajemen prioritas. Python menyediakan modul bawaan bernama `heapq` yang secara bawaan (*default*) beroperasi sebagai Min Heap.

## 4. Implementasi Tugas (Program Python & Output)
<img width="434" height="375" alt="image" src="https://github.com/user-attachments/assets/90bae24f-a26f-48b7-8709-4e56afd586ef" />
<img width="421" height="347" alt="image" src="https://github.com/user-attachments/assets/62fb1fbb-c076-4dee-af04-fededb1b1996" />

## Kesimpulan
Berdasarkan praktikum Modul 10 yang telah dilakukan, dapat disimpulkan bahwa:

1. **Heap** merupakan struktur data berbasis *Complete Binary Tree* yang sangat efisien untuk mengelola data berdasarkan tingkat prioritas, bukan berdasarkan urutan waktu kedatangan (FIFO) seperti pada struktur *Queue* biasa[cite: 7]. 
2. Dalam bahasa pemrograman Python, operasi Heap dapat diimplementasikan dengan mudah menggunakan modul bawaan `heapq`[cite: 7]. Modul ini secara *default* beroperasi sebagai *Min Heap*, namun dapat dimodifikasi menjadi *Max Heap* dengan cara memanipulasi nilai data menjadi negatif
3. Heap memiliki performa yang sangat baik untuk antrian prioritas karena kompleksitas waktu untuk operasi utamanya, seperti *insert* dan *delete root*, berjalan secara logaritmik atau $O(\log n)$[cite: 7]. Hal ini membuatnya lebih unggul dibandingkan *Binary Search Tree* (BST) khusus untuk kebutuhan akses data berprioritas
4. Konsep *Priority Queue* yang dibangun di atas Heap terbukti sangat aplikatif dan esensial dalam memecahkan berbagai masalah komputasi di dunia nyata, seperti penjadwalan proses pada sistem operasi (*CPU Scheduling*), sistem antrian IGD rumah sakit yang mengutamakan tingkat kegawatan, hingga penentuan prioritas kelayakan pembiayaan kredit
