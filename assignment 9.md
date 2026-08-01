# LAPORAN PRAKTIKUM - BINARY SEARCH TREE (BST)

Nama :   Rizwar Syaefulloh

NRP : 2C2230009

Prodi : Sains Data

## 1. Judul Praktikum
Praktikum Modul 9: Binary Search Tree (BST)

## 2. Tujuan Praktikum
Praktikum ini bertujuan agar mahasiswa memahami konsep dan aturan penyimpanan pada Binary Search Tree (BST). Selain itu, mahasiswa diharapkan mampu mengimplementasikan operasi *Insert*, *Search*, dan *Delete*, melakukan traversal, menganalisis efisiensi BST dibandingkan struktur data lain, serta menerapkan BST dalam aplikasi nyata.

## 3. Dasar Teori
*   **Binary Search Tree (BST)** adalah struktur data *Binary Tree* yang menerapkan aturan khusus: nilai node pada *subtree* kiri selalu lebih kecil dari *parent*, dan nilai node pada *subtree* kanan selalu lebih besar dari *parent*.
*   Aturan ini membuat pencarian data menjadi sangat cepat karena program dapat langsung mengikuti cabang yang relevan tanpa harus menelusuri seluruh elemen satu per satu.
*   Pada implementasi standar BST, data tidak boleh duplikat.
*   Terdapat tiga metode *traversal* utama, di mana traversal *Inorder* pada BST akan selalu menghasilkan urutan data secara *ascending* (terurut membesar).
*   Operasi *delete* pada BST adalah yang paling kompleks karena melibatkan tiga kondisi: menghapus *leaf node*, menghapus node dengan satu *child*, dan menghapus node dengan dua *child* (memerlukan *inorder successor* atau *predecessor*).
*   Untuk BST yang seimbang (*balanced*), kompleksitas waktu untuk operasi pencarian, penyisipan, dan penghapusan adalah $O(\log n)$. Namun jika BST tidak seimbang (membentuk garis lurus), kompleksitasnya dapat menurun menjadi $O(n)$.

## 4. Implementasi Tugas (Program Python & Analisis)
<img width="437" height="380" alt="image" src="https://github.com/user-attachments/assets/47f6700d-981e-4dba-85df-91442c8eeefa" />
<img width="410" height="385" alt="image" src="https://github.com/user-attachments/assets/deecff48-fe7b-4fc4-bafa-7682cefaa178" />
<img width="416" height="385" alt="image" src="https://github.com/user-attachments/assets/110f3b62-e667-44d5-8dd4-f77df0ecc150" />
<img width="305" height="67" alt="image" src="https://github.com/user-attachments/assets/48783925-b02e-4eff-b6ce-db75c40e33c0" />

## Kesimpulan
Binary Search Tree (BST) adalah pengembangan terstruktur dari pohon biner yang dirancang secara khusus untuk memaksimalkan efisiensi dalam mengelola data. Melalui aturan peletakan elemen secara hierarkis (Kiri < Akar < Kanan), operasi fundamental pencarian dan penyisipan dapat dieksekusi dengan kecepatan $O(\log n)$[cite: 8]. Konsep BST menjadi pondasi krusial bagi berbagai aplikasi modern yang berbasis pencarian massal, seperti manajemen rekam medis hingga pengindeksan basis data
