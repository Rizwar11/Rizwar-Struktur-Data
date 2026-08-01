# LAPORAN PRAKTIKUM - QUEUE DAN DEQUE

Nama : Rizwar Syaefulloh

NRP : 2C2230009

Prodi : Sains Data

## 1. Judul Praktikum
Praktikum Modul 6: Queue dan Deque (Double Ended Queue)

## 2. Tujuan Praktikum
Praktikum ini bertujuan agar mahasiswa memahami konsep dasar struktur data *Queue* dan *Deque*, menjelaskan prinsip FIFO (*First In First Out*), serta mampu mengimplementasikan dan menganalisis efisiensi operasinya menggunakan bahasa Python[cite: 3].

## 3. Dasar Teori
*   **Queue** merupakan struktur data *linear* yang bekerja berdasarkan prinsip FIFO (*First In First Out*), di mana elemen yang pertama masuk ke dalam antrian akan menjadi elemen pertama yang keluar[cite: 3].
*   Operasi utama dalam sebuah *Queue* meliputi **Enqueue** (menambahkan elemen ke bagian belakang/Rear) dan **Dequeue** (menghapus elemen dari bagian depan/Front)[cite: 3].
*   **Deque** (*Double Ended Queue*) adalah jenis antrian yang lebih fleksibel di mana penambahan dan penghapusan elemen dapat dilakukan dari kedua ujung antrian (depan maupun belakang)[cite: 3].

## 4. Langkah Praktikum
1. Membuat antrian (*Queue*) sederhana menggunakan tipe data *List* bawaan Python[cite: 3].
2. Mengimplementasikan operasi manipulasi data seperti *Enqueue* (menggunakan `append`) dan *Dequeue* (menggunakan `pop(0)`)[cite: 3].
3. Menerapkan antrian dua arah (*Deque*) menggunakan modul `collections.deque` yang menyediakan operasi `popleft()`[cite: 3].
4. Mengukur dan membandingkan waktu eksekusi proses *Dequeue* antara *List* dan *Deque* menggunakan data berjumlah besar[cite: 3].
<img width="416" height="309" alt="image" src="https://github.com/user-attachments/assets/6a8e7b89-22f0-4a7b-bae8-61674cde229c" />
<img width="384" height="333" alt="image" src="https://github.com/user-attachments/assets/a85ac4fd-bc18-4919-a96f-65d2be82cb7f" />
<img width="334" height="94" alt="image" src="https://github.com/user-attachments/assets/860efb2c-61cf-479e-8631-4abf714ad20e" />

## Kesimpulan
Berdasarkan praktikum dan analisis kinerja yang dilakukan, modul collections.deque terbukti jauh lebih efisien untuk operasi antrian (Queue) dibandingkan tipe data List bawaan Python[cite: 3]. Hal ini dikarenakan operasi menghapus data dari depan (Dequeue) pada modul deque menggunakan popleft() memiliki kompleksitas waktu $O(1)$, sedangkan pada List menggunakan pop(0) memerlukan waktu $O(n)$ karena harus menggeser seluruh elemen yang tersisa[cite: 3].
