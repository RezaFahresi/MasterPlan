Nama : Reza Fahresi
Nim : 362358302144

#TUGAS PRATIKUM 1
Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian?
Jawab : Agar Mengelola Impor lebih mudah dan memudahkan pemeliharaan dan pengembangan,
        dan juga membantu Strukturisasi yang lebih baik

Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat konstanta ?
Jawab : Agar Efisiensi kerja berjalan dengan lancar dan juga penggunaan data yang tidak berubah
        Konsitensi tampilan 

Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat!
Jawab : yang saya buat adalah hasil dari codingan pada langkah 9

Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?
Jawab : InitState digunakan untuk melakukan inisialisasi sebelum widget ditampilkan pada layar
        dispose digunkan untuk membersihkan sumber daya ketika widget tidak lagi digunakan 

#TUGAS PRATIKUM 2
Jelaskan mana yang dimaksud InheritedWidget pada langkah 1 tersebut! Mengapa yang digunakan InheritedNotifier?
Jawab : adalah widget di flutter yang menyediakan mekanisme untuk mengoper data ke widget turunannya
        di dalam widget tree. Mengapa digunakan karena memiliki fungsi tambahan yaitu dapat mendengarkan
        (listen)perubahan data atau notifkasi objek

Jelaskan maksud dari method di langkah 3 pada praktikum tersebut! Mengapa dilakukan demikian?
Jawab:Pada Langkah 3, Anda menambahkan dua getter di dalam model Plan pada file plan.dart. 
      Kedua getter ini bertujuan untuk menghitung jumlah tugas yang sudah diselesaikan dan memberikan pesan kemajuan dalam 
      format teks yang lebih mudah dibaca

Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat!
Jawab : Untuk Langkah 9, Anda diminta untuk menambahkan widget SafeArea yang menampilkan completenessMessage pada bagian akhir dari widget Column. Dengan menggunakan                SafeArea, Anda memastikan bahwa teks tentang kemajuan tugas (completenessMessage)
        tidak terhalang oleh elemen antarmuka sistem seperti notch, status bar, atau bagian bawah layar 
        (misalnya, pada perangkat dengan layar besar atau perangkat dengan rounded corners).

#PRATIKUM 3
Berdasarkan Praktikum 3 yang telah Anda lakukan, jelaskan maksud dari gambar diagram berikut ini?
Jawab : Diagram ini menggambarkan alur navigasi dan struktur widget dalam aplikasi berbasis Flutter. 
        Pada diagram sebelah kiri, terlihat bahwa aplikasi dimulai dengan MaterialApp, yang berfungsi sebagai widget utama aplikasi. Selanjutnya, 
        terdapat PlanProvider yang mungkin berperan sebagai penyedia data atau manajemen state bagi layar berikutnya, PlanCreatorScreen.
        Dalam PlanCreatorScreen, terdapat struktur Column yang berisi dua widget, yaitu TextField (untuk input teks) dan Expanded (untuk mengisi ruang kosong yang tersedia)         yang mencakup ListView, mungkin untuk menampilkan daftar item secara scrollable.
        Pada diagram sebelah kanan, terlihat bahwa ada navigasi dari PlanCreatorScreen ke PlanScreen menggunakan Navigator.push. PlanScreen juga dimulai dari MaterialApp,           diikuti oleh widget Scaffold yang menyediakan struktur dasar untuk aplikasi seperti AppBar dan body. Di dalam Scaffold, ada Column yang berisi Expanded, SafeArea,           ListView, dan Text. Kesimpulannya, diagram ini menjelaskan bagaimana aplikasi berpindah dari PlanCreatorScreen ke PlanScreen dengan struktur widget yang lebih               kompleks.

Lakukan capture hasil dari Langkah 14 berupa GIF, kemudian jelaskan apa yang telah Anda buat?
Jawab : <img width="344" alt="image" src="https://github.com/user-attachments/assets/464c18ce-2e85-4c42-a2f8-78a6188373a0">
        Judul: Di bagian atas layar, terdapat teks "Master Plans [Reza Fahresi]" yang menunjukkan bahwa aplikasi ini digunakan untuk mengelola rencana milik Anda.
        Tombol "Add a plan": Ada sebuah kartu dengan teks "Add a plan" yang mungkin berfungsi sebagai tombol untuk menambahkan rencana baru. Ketika ditekan, tombol ini              mungkin akan membuka layar atau dialog untuk membuat rencana baru. 
        Daftar Rencana: Di bawah tombol tersebut, ada daftar rencana yang telah ditambahkan, seperti "Flutter dasar" dan "Web Dasar." Setiap rencana menampilkan jumlah              tugas yang terselesaikan dibandingkan total tugas, dalam format "0 out of 0 tasks." Ini menunjukkan bahwa belum ada tugas yang ditambahkan ke dalam rencana tersebut.

INI UNTUK HASIL AKHIR NYA
<img width="340" alt="image" src="https://github.com/user-attachments/assets/9d6a94a2-ff9d-4df1-bb1c-7e2b226bd826">

