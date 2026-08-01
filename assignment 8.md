# LAPORAN PRAKTIKUM - TREE DAN BINARY TREE

Nama : Rizwar Syaefulloh

NRP : 2C2230009

Prodi : [Prodi Anda]

## 1. Judul Praktikum
Praktikum Modul 8: Tree dan Binary Tree

## 2. Tujuan Praktikum
Praktikum ini bertujuan agar mahasiswa memahami konsep dasar struktur data *Tree* dan *Binary Tree*, termasuk terminologi hierarkis seperti *parent, child, sibling*, dan *leaf node*. Mahasiswa juga diharapkan mampu mengimplementasikan struktur tersebut menggunakan Python, melakukan penelusuran (*traversal*) dengan metode *Preorder, Inorder*, dan *Postorder*, serta menganalisis kompleksitas dan menerapkan struktur pohon ini dalam penyelesaian masalah nyata.

## 3. Dasar Teori
*   **Tree** merupakan struktur data *non-linear* yang digunakan untuk merepresentasikan hubungan hierarkis antar elemen data, menyerupai bentuk cabang pohon.
*   Komponen utama dalam sebuah *Tree* meliputi **Root** (node paling atas), **Parent** (node yang memiliki anak), **Child** (node yang memiliki *parent*), **Sibling** (node dengan *parent* yang sama), dan **Leaf Node** (node yang tidak memiliki *child*).
*   **Binary Tree** adalah jenis *Tree* spesifik di mana setiap *node* dibatasi hanya boleh memiliki maksimal dua *child*, yaitu *left child* dan *right child*.
*   Proses mengunjungi seluruh *node* di dalam *Tree* disebut dengan **Traversal**. Terdapat tiga metode utama traversal pada *Binary Tree*:
    *   **Preorder:** *Root* $\rightarrow$ *Left* $\rightarrow$ *Right*.
    *   **Inorder:** *Left* $\rightarrow$ *Root* $\rightarrow$ *Right*.
    *   **Postorder:** *Left* $\rightarrow$ *Right* $\rightarrow$ *Root*.
*   Kompleksitas algoritma untuk proses traversal ini adalah $O(n)$, dengan $n$ merupakan jumlah keseluruhan *node* yang harus dikunjungi.

## 4. Implementasi Tugas (Program Python & Analisis)
<img width="434" height="384" alt="image" src="https://github.com/user-attachments/assets/0375d8be-26a5-4795-93af-5de3fd875b20" />
<img width="428" height="384" alt="image" src="https://github.com/user-attachments/assets/27085be1-6162-4751-9d3f-8e8de70033d9" />
<img width="410" height="202" alt="image" src="https://github.com/user-attachments/assets/794c4f96-d21e-4983-b512-8e4f92be9b4a" />

## Kesimpulan
Berdasarkan praktikum yang telah dilaksanakan, dapat disimpulkan bahwa Tree dan Binary Tree merupakan struktur data fundamental untuk memodelkan hierarki data dalam bentuk bercabang alih-alih linier[cite: 9]. Konsep hierarki ini sangat aplikatif digunakan pada simulasi struktur penyimpanan (sistem folder) dan pembuatan indeks (database index), di mana proses pencarian dituntut berjalan dengan optimal dan logis[cite: 9]. Melalui algoritma traversal seperti Preorder, Inorder, maupun Postorder, pengolahan data pada Tree dapat dipetakan secara terstruktur dengan kompleksitas waktu operasional yang terukur yaitu $O(n)$
