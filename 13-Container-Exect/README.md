# Container Exect

- Saat kita membuat container, aplikasi yang terdapat di dalam container hanya bisa diakses dari dalam container
- Oleh karena itu, kadang kita perlu masuk ke dalam container nya itu sendiri
- Untuk masuk ke dalam container, kita bisa menggunakan fitur Container Exec, dimana digunakan untuk mengeksekusi kode program yang terdapat di dalam container

## Masuk ke Container

- Untuk masuk ke dalam container, kita bisa mencoba mengeksekusi program bash script yang terdapat di dalam container dengan bantuan Container Exec:
```bash
docker container exec -i -t containerId/namacontainer /bin/bash
```
- -i adalah argument interaktif, menjaga input tetap aktif
- -t adalah argument untuk alokasi pseudo-TTY (terminal akses)
- Dan /bin/bash contoh kode program yang terdapat di dalam container
