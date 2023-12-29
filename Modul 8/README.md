# Praktikum SO Modul 8

## Instruksi :

1. `nano fork.c` <br>
   `gcc fork.c` <br>
   `./a.out`

2. `./a.out`
3. `./a.out /bin/whoami whoami`
4. `./a.out stat.c`
5. `./a.out /`

### Keterangan 

`nano fork.c`: Membuka teks editor "nano" untuk membuat atau mengedit file dengan nama "fork.c". "nano" adalah editor teks sederhana yang berjalan di terminal.

`gcc fork.c`: Perintah untuk mengompilasi kode sumber dalam file "fork.c" menggunakan compiler GCC. GCC akan menghasilkan file biner yang dapat dieksekusi (biasanya bernama "a.out").

`./a.out`: Setelah proses kompilasi selesai, perintah ini digunakan untuk menjalankan file biner yang dihasilkan ("a.out"). Ini akan melaksanakan program yang telah dikompilasi dari kode dalam file "fork.c".

### Catatan
Sebelum compile pake gcc, kalo nanti ada error stdio.h : No Such File or Directory bisa update & install libc6-dev yaa, pake perintah ini:

`sudo apt update && sudo apt install libc6-dev -y`
