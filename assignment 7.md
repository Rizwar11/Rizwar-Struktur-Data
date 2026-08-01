LAPORAN PRAKTIKUM - STRUKTUR DATA
Nama : Rizwar Syaefulloh

NRP : 2c2230009

Prodi : Sains Data

Judul Praktikum
"Praktikum Modul 7: Implementasi dan Operasi Dasar Linked List menggunakan Python"

Tujuan Praktikum
Praktikum ini bertujuan untuk memberikan pemahaman dasar mengenai konsep struktur data dinamis dan implementasinya menggunakan bahasa pemrograman Python:

a. Memahami konsep dasar dan struktur node pada Linked List.
b. Menjelaskan perbedaan penyimpanan memori antara Array dan Linked List.
c. Mengimplementasikan Single Linked List beserta operasi insert, delete, search, dan traversal ke dalam program Python.
d. Menganalisis kompleksitas algoritma dari operasi dasar pada Linked List.

Dasar Teori
Linked List adalah struktur data linear dinamis yang terdiri dari sekumpulan elemen yang disebut node. Berbeda dengan Array yang menyimpan data pada lokasi memori yang berurutan (contiguous memory), Linked List menyimpan data pada lokasi memori yang tersebar. Elemen-elemen ini dihubungkan satu sama lain menggunakan pointer (alamat referensi).

Setiap node pada Singly Linked List memiliki dua komponen utama:

Data: Nilai atau informasi yang disimpan.

Next / Pointer: Referensi yang menunjuk ke node berikutnya dalam rangkaian. Jika node tersebut adalah elemen terakhir, maka pointer-nya akan bernilai None atau Null.

Keunggulan utama Linked List dibandingkan Array adalah fleksibilitasnya dalam alokasi memori (ukurannya dinamis) serta efisiensi dalam melakukan operasi penambahan (insertion) dan penghapusan (deletion) data tanpa harus menggeser elemen-elemen lainnya.

Langkah Praktikum
1. Membuat Struktur Dasar Node dan Linked List
Mendefinisikan class Node untuk menyimpan data dan pointer, serta class LinkedList untuk menginisialisasi Head (titik awal list).

2. Mengimplementasikan Operasi Dasar (Fungsi)
Menambahkan fungsi-fungsi ke dalam class LinkedList untuk memanipulasi data:

insert_awal(): Menambahkan node baru di posisi paling depan (menggeser Head).

insert_akhir(): Melakukan traversal ke ujung list, lalu menambahkan node baru di akhir.

hapus_node(): Mencari nilai tertentu dan menghapus node tersebut dengan mengarahkan pointer node sebelumnya ke node sesudahnya.

cari_data(): Mencari keberadaan suatu nilai di dalam list dan mengembalikan posisinya.

tampilkan(): Melakukan traversal dari Head hingga None untuk mencetak seluruh isi list.

3. Eksekusi Program (Syntax)
<img width="428" height="386" alt="image" src="https://github.com/user-attachments/assets/58b34dca-4bba-4211-80d2-c10f779e47e5" />
<img width="388" height="332" alt="image" src="https://github.com/user-attachments/assets/11c42cc0-fe36-46ee-a352-4692b2b3afdb" />
<img width="169" height="95" alt="image" src="https://github.com/user-attachments/assets/61da7a3e-a810-4b4e-8eab-1cc46ed47745" />

Kesimpulan
Isi awal: 10 -> 20 -> 30 -> 40 -> 50Output ini membuktikan bahwa fungsi insert_akhir dan tampilkan (traversal) berjalan dengan baik. Setiap iterasi berhasil membuat node baru yang disambungkan ke pointer next dari node terakhir sebelumnya.Insert 5 di awal: 5 -> 10 -> 20 -> 30 -> 40 -> 50Terlihat bahwa angka 5 berhasil menjadi elemen pertama. Hal ini mengonfirmasi bahwa operasi insert di awal sangat efisien ($O(1)$) karena program hanya perlu mengubah node 5 menjadi Head baru yang menunjuk ke Head lama (10), tanpa perlu menggeser posisi node 10 hingga 50 di dalam memori.Hapus nilai 30: 5 -> 10 -> 20 -> 40 -> 50Angka 30 hilang dari rantai. Output ini menyimpulkan bahwa proses deletion berhasil memutus referensi ke node 30 dengan cara mengarahkan pointer next dari node 20 langsung menuju ke node 40.Cari nilai 40: Data 40 ditemukan pada posisi 4Output ini menunjukkan bahwa karena Linked List tidak memiliki indeks bawaan seperti Array, pencarian (search) mengharuskan program untuk menelusuri rantai node satu per satu dari awal (posisi 1) hingga menemukan nilai yang cocok di posisi ke-4. Hal ini membuktikan kompleksitas pencarian pada Linked List adalah $O(n)$.
