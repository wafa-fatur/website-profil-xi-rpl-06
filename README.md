# Website Profil XI RPL
Website ini merupakan proyek pembelajaran
kolaborasi Git dan GitHub.
## Anggota Tim
1. wafa- Project Manager
2. iman- Developer Profile
3. raisya- Developer Anggota
4. fadli- Developer Kontak
 
# Website Profil XI RPL 06

## Checkpoint 1

**Link GitHub:**
https://github.com/wafa-fatur/website-profil-xi-rpl-06.git

## Checkpoint 2

### Apa arti hasil `git status`?

Perintah `git status` digunakan untuk melihat kondisi terkini dari **working directory** dan **staging area** pada repositori Git. 

## Pertanyaan Analisis

### Mengapa setiap developer tidak langsung bekerja pada `main`?

Setiap developer sebaiknya tidak langsung bekerja pada branch `main` karena `main` biasanya digunakan sebagai branch utama yang berisi kode yang sudah stabil.
Developer menggunakan **branch terpisah** agar dapat mengembangkan fitur atau melakukan perubahan tanpa mengganggu pekerjaan developer lain maupun kode utama.

## Pertanyaan Analisis

### Apa perbedaan pesan commit berikut?

Perbedaannya terletak pada **kejelasan pesan commit**.

* `git commit -m "update"` memiliki pesan yang terlalu umum, sehingga sulit mengetahui perubahan apa yang dilakukan.
* `git commit -m "Menambahkan halaman profil kelas"` memiliki pesan yang lebih spesifik karena menjelaskan bahwa commit tersebut berisi penambahan halaman profil kelas.

## PERTANYAAN ANALISIS

### 1. Apa fungsi `git pull`?

`git pull` berfungsi untuk mengambil perubahan terbaru dari repository GitHub dan menggabungkannya ke branch yang sedang digunakan. Dengan begitu, kode yang ada di komputer kita tetap mengikuti versi terbaru dari project.

### 2. Apa yang terjadi jika programmer tidak melakukan `git pull`?

Jika programmer tidak melakukan `git pull`, kode yang dimiliki bisa menjadi **tidak terbaru**. Hal ini dapat menyebabkan perbedaan kode dengan anggota tim lain dan berpotensi menimbulkan **conflict** saat melakukan `push` atau menggabungkan perubahan.

### 3. Mengapa `main` harus dijaga agar tetap stabil?

Branch `main` harus dijaga agar tetap stabil karena biasanya menjadi versi utama project yang sudah siap digunakan. Jika kode yang belum selesai atau masih memiliki error langsung dimasukkan ke `main`, project dapat mengalami masalah dan mengganggu pekerjaan anggota tim lainnya.


