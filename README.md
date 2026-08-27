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

## PERTANYAAN ANALISIS

### 1. Apa fungsi `git pull`?

`git pull` berfungsi untuk mengambil perubahan terbaru dari repository GitHub ke komputer lokal. Dengan melakukan `git pull`, programmer dapat memastikan kode yang digunakan sudah mengikuti perubahan terbaru dari anggota tim.

### 2. Apa yang terjadi jika programmer tidak melakukan `git pull`?

Jika programmer tidak melakukan `git pull`, kode di komputer bisa menjadi **tertinggal dari versi terbaru**. Akibatnya, dapat terjadi perbedaan kode dengan anggota tim lain dan kemungkinan muncul **conflict** saat melakukan `push` atau merge.

### 3. Mengapa `main` harus dijaga agar tetap stabil?

`main` harus dijaga agar tetap stabil karena merupakan **branch utama** yang berisi versi project yang sudah siap digunakan. Jika kode yang masih memiliki error atau belum selesai langsung dimasukkan ke `main`, hal tersebut dapat mengganggu project dan pekerjaan anggota tim lainnya.

## PERTANYAAN CONFLICT

### 1. Mengapa conflict terjadi?

Conflict terjadi ketika dua programmer melakukan perubahan pada bagian kode yang sama, tetapi perubahan tersebut berbeda. Git tidak dapat menentukan perubahan mana yang harus digunakan, sehingga programmer perlu menyelesaikannya secara manual.

### 2. Apakah conflict berarti Git rusak?

Tidak. **Conflict bukan berarti Git rusak.** Conflict merupakan kondisi yang normal dalam kerja tim menggunakan Git. Git hanya memberi tahu bahwa ada perubahan yang bertentangan dan membutuhkan keputusan dari programmer.

### 3. Siapa yang harus menentukan versi kode yang benar?

Versi kode yang benar ditentukan oleh **programmer atau anggota tim yang bertanggung jawab terhadap bagian kode tersebut**. Jika perubahan melibatkan beberapa anggota, keputusan sebaiknya didiskusikan bersama agar hasil akhirnya sesuai dengan kebutuhan project.

### 4. Mengapa komunikasi antar programmer penting?

Komunikasi penting agar setiap programmer mengetahui perubahan yang sedang dikerjakan oleh anggota tim lainnya. Dengan komunikasi yang baik, kesalahan dan conflict dapat dikurangi serta proses pengembangan project menjadi lebih teratur.
