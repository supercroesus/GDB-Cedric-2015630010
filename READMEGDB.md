# GDB-Cedric-2015630010
Program c pada ubuntu

![virtualbox_ubuntu1_21_12_2017_20_27_49](https://user-images.githubusercontent.com/17801070/34258333-0bd3ffc0-e690-11e7-9c40-76c2c9a52855.png)
Program c dan compile menggunakan GDB ini dibuat dengan Operating System Ubuntu.
Gambar di atas menunjukkan program "coba.c" sedang dicompile dengan gcc lalu dengan gdb. Untuk memulai debug maka command yang pertama diberikan adalah gdb coba. Command "run" untuk memulai gdb program coba.c. Lalu nilai a akan dicetak dan hasilnya 0. Fungsi command "list" untuk menampilkan baris per baris program (hanya 10 baris pertama). Untuk menampilkan semua baris maka harus ditulis "list 1,4" yang berarti menampilkan baris program dari 1 sampai 14.

![virtualbox_ubuntu1_21_12_2017_23_03_58](https://user-images.githubusercontent.com/17801070/34263822-5bfaecbc-e6a3-11e7-91ca-5f79d2eef7ef.png)

"break 7" berfungsi untuk memberi patokan pada baris yang diinginkan kemudian dapat dijalankan kembali programmnya dengan "run" agar memulai pemeriksaan dari baris prgram ke 7. Berikutnya adalah "info locals" untuk mencetak variabel dan nilainya. Akan tetapi nilai yang dicetak masih belum menunjukkan nilai yang sebenarnya karena belum diexcute. Setelah memberi command "next" maka akan mencetak baris selanjutnya int = 2. Lalu info locals lagi maka nilai b akan menjadi 1 yang tadinya mempunyai nilai acak sebelum diberi perintah next. "Print a" akan mencetak nilai a dan "print b" akan mencetak nilai b.

![virtualbox_ubuntu1_21_12_2017_23_32_35](https://user-images.githubusercontent.com/17801070/34265025-57d3e414-e6a7-11e7-8960-ed92fda92a65.png)

Gambar di atas mulai dari command "b 11" yaitu memberikan breakpoint pada baris 11 kemudian dilanjutkan dengan "continue" untuk melanjutkan program dari baris 11 dan mencetaknya.
"Info b" atau juga "info breakpoint" yang akan mencetak semua break point. Pada gambar menjukkan break point dicetak sebanyak 2 kali juga terdapat informasi seperti alamat kode program tersebut dan terletak pada baris ke berapa. Jika ingin menghapus breakpoint nomor 2 maka dilakukan perintah "d 2" agar breakpoint baris ke 2 bisa dihapus.
Dilanjutkan dengan "continue" untuk melanjutkan program,pada saat continue maka "value of a is 0" akan selalu dicetak.

![virtualbox_ubuntu1_21_12_2017_23_55_42](https://user-images.githubusercontent.com/17801070/34266049-81a0e474-e6aa-11e7-8575-426024a521b1.png)

Saat melakukan command "run" maka program dijalankan kembali dimulai dari breakpoint 1 karena breakpoint 2 sudah dihapus pada perintah sebelumnya. Lalu "continue" dan "info b" untuk menampilkan breakpoint kembali. Jika ingin menghapus breakpoint nomor 1 maka digunakan perintah "d 1" kemudian "info breakpoint" agar menampilkan breakpoint yang tersedia.

![virtualbox_ubuntu1_22_12_2017_00_08_42](https://user-images.githubusercontent.com/17801070/34266585-5673fa50-e6ac-11e7-9405-3a706df55e39.png)
