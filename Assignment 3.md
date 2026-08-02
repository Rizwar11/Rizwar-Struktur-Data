# LAPORAN PRAKTIKUM
MODUL 3: KONSEP STRUKTUR DATA, ADT, DAN ANALISIS KOMPLEKSITAS ALGORITMA

**Nama:** Rizwar Syaefulloh  
**NRP:** 2C2230009  
**Prodi:** Sains Data  

---

## 1. Judul Praktikum
Konsep Struktur Data, ADT, dan Analisis Kompleksitas Algoritma

## 2. Tujuan Praktikum
Praktikum ini bertujuan agar mahasiswa:
* Memahami konsep dasar struktur data, termasuk perbedaan struktur data linear dan non-linear.
* Menjelaskan pengertian dan konsep *Abstract Data Type* (ADT).
* Memahami urgensi efisiensi algoritma dalam pengembangan program.
* Mengenali kompleksitas waktu algoritma dan menggunakan *Big-O Notation* sederhana ($O(1)$, $O(n)$, $O(n^2)$).
* Mampu membandingkan efisiensi dari beberapa algoritma dasar dan mengimplementasikannya dalam Python.

## 3. Dasar Teori
* **Struktur Data:** Merupakan cara untuk menyimpan, mengorganisasikan, dan mengelola data di dalam komputer agar dapat diolah dan digunakan secara efisien. Terbagi menjadi dua, yaitu linear (seperti *Array*, *List*, *Stack*, *Queue*) dan non-linear (seperti *Tree*, *Graph*).
* **Abstract Data Type (ADT):** Model konseptual yang hanya mendefinisikan jenis data dan operasi yang dapat dilakukan, tanpa memikirkan detail teknis implementasinya. Contoh ADT adalah *Stack* dengan operasi *Push*, *Pop*, dan *Peek*.
* **Efisiensi Algoritma:** Sangat krusial karena menentukan seberapa cepat suatu program berjalan dan seberapa hemat memori yang digunakan. 
* **Big-O Notation:** Notasi matematika yang dipakai untuk mendeskripsikan laju pertumbuhan waktu eksekusi algoritma terhadap peningkatan jumlah data. Contoh umumnya adalah $O(1)$ untuk akses konstan, $O(n)$ untuk pencarian linear (*single loop*), dan $O(n^2)$ untuk pencarian kuadratik (*nested loop*).

## 4. Program Python (Penyelesaian Tugas)
<img width="908" height="355" alt="image" src="https://github.com/user-attachments/assets/8eb4049f-1d34-4193-a6b3-f86180d6595b" />
<img width="482" height="320" alt="image" src="https://github.com/user-attachments/assets/50768098-ef31-4da9-8372-0b6b64d9063b" />

## Kesimpulan
Pemilihan struktur data dan algoritma sangat krusial dalam pengembangan program[cite: 13]. Abstract Data Type (ADT) mempermudah perancangan logika program (seperti Stack atau Queue) tanpa harus mengkhawatirkan masalah sintaks teknis[cite: 13]. Selain itu, analisis kompleksitas menggunakan Big-O Notation sangat berguna untuk mengukur efisiensi program[cite: 13]. Program yang terlihat berjalan normal pada data kecil dapat terhambat secara drastis (bottleneck) jika menghadapi ribuan data akibat penggunaan logika iterasi yang tidak efisien seperti nested loop ($O(n^2)$)
