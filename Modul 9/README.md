# Praktikum Sistem Operasi Modul 9

## Instruksi :

### Create
1. `nano fcreate.c`
2. `gcc -o fcreate fcreate.c`
3. `./fcreate test.txt` -> Masukkan isi file
4. `Ctrl+C`

### Read
1. `nano fread.c`
2. `gcc -o fread fread.c`
3. `./fread test.txt` -> Menampilkan isi dari file
4. `Enter`

### Append
1. `nano fappend.c`
2. `gcc -o fappend fappend.c`
3. `./fappend test.txt` -> Masukkan isi file untuk menambahkan ke dalam file
4. `Enter / Ctrl+C`




### Catatan
sebelum compile pake gcc, kalo nanti ada error stdio.h : No Such File or Directory bisa update & install libc6-dev yaa, pake perintah ini:

`sudo apt update && sudo apt install libc6-dev -y`
