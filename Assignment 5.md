# LAPORAN PRAKTIKUM - STACK

Nama : Rizwar Syaefulloh

NRP : 2C2230009

Prodi : Sains Data
## 1. Judul Praktikum
Praktikum Modul 5: Stack (LIFO - Last In First Out)

## 2. Tujuan Praktikum
Praktikum ini bertujuan agar mahasiswa memahami konsep dasar struktur data *Stack*, menjelaskan prinsip kerja LIFO (*Last In First Out*), serta mampu mengimplementasikan dan menganalisis kompleksitas operasinya dalam bahasa Python untuk menyelesaikan permasalahan komputasi.

## 3. Dasar Teori
*   **Stack** merupakan salah satu struktur data linear yang bekerja berdasarkan prinsip LIFO (*Last In First Out*), yang berarti elemen yang terakhir masuk ke dalam struktur akan menjadi elemen pertama yang keluar.
*   Operasi dasar pada *Stack* meliputi **Push** untuk menambahkan elemen ke bagian atas (*TOP*), **Pop** untuk menghapus elemen paling atas, serta **Peek / Top** untuk melihat elemen teratas tanpa menghapusnya.
*   Seluruh operasi dasar *Stack* tersebut memiliki efisiensi atau kompleksitas waktu $O(1)$ karena modifikasi atau akses data hanya dilakukan pada satu titik akses, yaitu elemen teratas.
*   Dalam sistem komputer modern, *Stack* digunakan secara luas pada *Function Call Stack*, pengecekan tanda kurung pada *compiler*, fitur *Undo-Redo*, serta *Browser History*.

## 4. Langkah Praktikum
1. Membuat struktur *Stack* sederhana dengan memanfaatkan tipe data *List* bawaan Python.
2. Mengimplementasikan operasi *Push* dengan memanfaatkan *method* `append()`, dan operasi *Pop* menggunakan *method* `pop().
3. Membaca elemen teratas (*Peek*) dengan mengakses indeks terakhir *List* yaitu `[-1]`[cite: 7].
4. Mengembangkan program berbasis *Stack* untuk menyelesaikan studi kasus nyata seperti validasi pasangan tanda kurung dan simulasi tumpukan piring.
<img width="434" height="380" alt="image" src="https://github.com/user-attachments/assets/5e274527-1582-4f5d-8284-3ef52af98b33" />
<img width="270" height="201" alt="image" src="https://github.com/user-attachments/assets/fe7762e9-7105-44d0-981c-7d4d83b665b9" />

## Kesimpulan
Melalui implementasi program di atas, dapat disimpulkan bahwa Stack sangat efektif untuk menangani data yang memerlukan penelusuran mundur (backtracking) atau pemrosesan berurutan terbalik. Karena menggunakan tipe data List pada Python, pemanggilan operasi penambahan di ujung struktur (append) dan penghapusan di ujung struktur (pop()) dapat diselesaikan dalam kompleksitas waktu konstan sebesar $O(1)$, menjadikannya sangat ringan untuk eksekusi memori seperti pada fitur validasi logika, riwayat browser, maupun undo/redo..
