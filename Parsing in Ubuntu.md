# Tugas Parsing Cedric 2015630010
Ini adalah contoh program parsing C "using_example" pada ubuntu dan dicompile dengan gcc. Header "csvparser" yang dibuat terdapat di dalam 1 folder dengan program parsing begitu juga input dari program ini terdapat pada file csv "example_file".

![csv](https://user-images.githubusercontent.com/17801070/34302895-955e42c0-e765-11e7-8ef9-f5c0224e6e37.png)

Gambar di atas "example_file" adalah masukan dari program yang dibuat dalam excel dengan extensi .csv. Masukkan tersebut berupa angka.

------------------------------------------------------------------------------------------------------------------------------------------

![program c](https://user-images.githubusercontent.com/17801070/34303614-d42852f4-e768-11e7-91b1-8a3cc43baffb.png)

Ini adalah program parsing yang telah dibuat sebelumnya

------------------------------------------------------------------------------------------------------------------------------------------

![h1](https://user-images.githubusercontent.com/17801070/34303766-80536bae-e769-11e7-9caa-890f0f02a044.png)
Program Header (gambar 1)
![h2](https://user-images.githubusercontent.com/17801070/34303799-9f032774-e769-11e7-9cd6-d5bd6d7f0334.png)
Program Header (gambar 2)

------------------------------------------------------------------------------------------------------------------------------------------

![awal](https://user-images.githubusercontent.com/17801070/34303934-339a565a-e76a-11e7-951f-31ceeb81bb90.png)

Ini adalah langkah awal untuk memulai assembly.

1. gcc usage_example.c -I ../include ../src/csvparser.c -o usage_example adalah untuk mengcompile program utama.
2. nano usage_example.c hanya menampilkan program yang telah dibuat dalam tab baru.
3. gdb usage_example untuk memulai gdb program usage_example

Setelah memasukin tahap gdb maka

4. Ketik "disass main" untuk mendisassemble program main yang telah dibuat, maka akan muncul program yang telah disassembly

Berikut adalah hasil program yang teah disassembly

![disassembly 1](https://user-images.githubusercontent.com/17801070/34304232-6dc37270-e76b-11e7-8fa7-ecb0e8fe7117.png)

![disassembly 2](https://user-images.githubusercontent.com/17801070/34304249-7cf18cf0-e76b-11e7-832d-780a331efece.png)
