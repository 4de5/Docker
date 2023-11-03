# Sebelum Belajar Docker

## Mengerti tentang sistem operasi
### ChatGPT
Sistem operasi adalah seperti otak dari komputer Anda. Sama seperti otak mengendalikan seluruh fungsi tubuh manusia, sistem operasi mengendalikan semua aspek dalam komputer Anda. Sebagai seorang mahasiswa, Anda dapat memahami sistem operasi sebagai "pintu gerbang intelektual" yang memungkinkan Anda mengakses dan menggunakan berbagai alat dan sumber daya komputer Anda.

Bayangkan jika Anda adalah seorang mahasiswa yang ingin mengakses perpustakaan universitas. Tanpa sistem operasi, komputer Anda hanya akan menjadi sekumpulan perangkat keras yang tidak bisa berfungsi secara mandiri, mirip dengan mesin fotokopi atau rak buku tanpa pustakawan. Sistem operasi adalah pustakawan virtual Anda yang membantu Anda mengatur, mengakses, dan menggunakan sumber daya tersebut.

Sistem operasi, seperti Windows, macOS, atau Linux, bertindak sebagai perantara antara Anda (pengguna) dan komponen perangkat keras komputer Anda, seperti CPU, memori, disk, dan perangkat masukan seperti keyboard dan mouse. Ini memungkinkan Anda untuk menjalankan aplikasi, mengelola file, dan melakukan berbagai tugas komputasi dengan lebih mudah.

### BardAI
Sistem operasi adalah perangkat lunak yang mengatur dan mengontrol semua perangkat keras dan perangkat lunak di komputer. Tanpa sistem operasi, komputer tidak dapat berfungsi.

Fungsi sistem operasi antara lain:

- Mengelola perangkat keras, seperti CPU, memori, dan penyimpanan.
- Menyediakan antarmuka antara pengguna dan komputer.
- Menjalankan program aplikasi.

Analogi yang cocok untuk sistem operasi adalah seorang manajer di sebuah perusahaan. Manajer bertanggung jawab untuk mengatur dan mengontrol semua aspek perusahaan, mulai dari karyawan, peralatan, dan sumber daya lainnya. Sistem operasi juga memiliki fungsi yang sama, yaitu mengatur dan mengontrol semua aspek komputer, mulai dari perangkat keras, perangkat lunak, dan pengguna.

## Mengerti cara menginstall aplikasi
- Untuk menginstall di Windows dan Mac, kita bisa menggunakan Docker Desktop https://docs.docker.com/get-docker/ 
- Untuk Linux, kita bisa install dari repository sesuai distro linux masing-masing https://docs.docker.com/engine/install/ 
- Untuk Cek Docker `docker version`(lengkap tapi jalankan dulu app-nya), `docker --version`, `docker -v`


## Mengerti cara menggunakan perintah di terminal / command line
Berikut adalah beberapa perintah Command Line Interface (CLI) dasar yang serupa dan dapat digunakan di berbagai sistem operasi, termasuk Windows, macOS (berbasis Unix), dan Linux:

1. `cd` (Change Directory): Untuk berpindah antara direktori atau folder saat ini ke direktori lain.
   
Contoh:
```bash
cd Documents

```

2. `mkdir` (Make Directory): Untuk membuat direktori atau folder baru.

Contoh:
```bash
mkdir NewFolder

```

3. `ls` (List): Untuk menampilkan daftar file dan folder dalam direktori saat ini di sistem berbasis Unix (termasuk macOS dan Linux), sementara di Windows, Anda dapat menggunakan perintah `dir`.

Contoh (Unix):
```bash
ls

```

Contoh (Windows):
```bash
dir

```

4. `pwd` (Print Working Directory): Untuk menampilkan direktori saat ini.

Contoh:
```bash
pwd

```

5. `rm` (Remove): Untuk menghapus file atau folder.

Contoh:
```bash
rm NamaFile.txt

```

6. `cp` (Copy) dan `mv` (Move): Untuk menyalin file atau memindahkan file dari satu lokasi ke lokasi lain.

Contoh:
```bash
cp file.txt /destination/folder
mv file.txt /destination/folder

```

7. `cat` (Concatenate): Untuk menampilkan isi dari sebuah file di terminal.

Contoh:
```bash
cat file.txt

```

8. `clear` atau `cls` (Clear Screen): Untuk membersihkan tampilan terminal atau command prompt.

Contoh:
```bash
clear

```

9. `history`: Untuk menampilkan daftar perintah yang telah dieksekusi sebelumnya.

Contoh:
```bash
history

```

## Mengerti tentang Virtual Machine
### PZN
- Saat membuat sebuah VM, biasanya kita akan menginstall sistem operasi juga di VM nya
- Masalah ketika kita menggunakan VM adalah proses yang lambat ketika pembuatan VM nya, dan butuh waktu untuk boot sistem operasi di dalam VM tersebut ketika kita menjalankan VM atau me-restart VM tersebut

### ChatGPT
Virtual Machine (VM) adalah teknologi yang memungkinkan Anda untuk menjalankan sistem operasi dan aplikasi komputer di dalam lingkungan virtual yang terisolasi pada komputer fisik Anda. Ini mirip dengan memiliki komputer dalam komputer, di mana komputer virtual (VM) berfungsi seperti mesin fisik yang independen. Sebagai mahasiswa, Anda dapat menganggap VM sebagai "kelas tambahan yang dapat diakses secara virtual" yang ditempatkan dalam gedung universitas utama Anda.

Bayangkan jika universitas Anda memiliki sebuah bangunan khusus yang berisi laboratorium komputer dengan sistem operasi yang berbeda-beda, seperti Windows, macOS, dan Linux. Anda ingin mengakses dan belajar menggunakan semua sistem operasi ini, tetapi tidak mungkin memiliki tiga komputer fisik yang berbeda untuk setiap sistem operasi.

Di sinilah VM masuk. Dengan teknologi VM, Anda dapat membuat tiga kelas virtual yang masing-masing memiliki sistem operasi yang berbeda di dalam komputer Anda. Anda dapat masuk ke setiap kelas virtual ini kapan saja, belajar, melakukan eksperimen, dan kemudian menghentikan kelas virtual ketika selesai. Semua ini terjadi dalam komputer fisik Anda tanpa perlu memiliki tiga komputer sebenarnya.

### BardAI
Virtual machine (VM) adalah perangkat lunak yang menciptakan komputer virtual di dalam komputer fisik. VM dapat menjalankan sistem operasi dan aplikasi yang berbeda dari sistem operasi yang berjalan di komputer fisik.

Fungsi VM antara lain:

- Meningkatkan efisiensi penggunaan sumber daya komputer. VM dapat berbagi sumber daya komputer fisik, seperti CPU, memori, dan penyimpanan.
- Meningkatkan keamanan komputer. VM dapat diisolasi dari sistem operasi dan aplikasi yang berjalan di komputer fisik.
- Meningkatkan fleksibilitas penggunaan komputer. VM dapat digunakan untuk menjalankan sistem operasi dan aplikasi yang tidak kompatibel dengan sistem operasi yang berjalan di komputer fisik.

Analogi yang cocok untuk VM adalah seperti rumah boneka. Rumah boneka adalah replika kecil dari rumah yang sebenarnya. VM adalah replika kecil dari komputer yang sebenarnya.

Berikut adalah analogi yang lebih kreatif:

- VM adalah seperti kamar di asrama.
- Komputer fisik adalah seperti asrama.
- VM adalah seperti kamar di asrama.
- Sistem operasi adalah seperti penghuni kamar.

Analogi ini mungkin dapat membantu Anda untuk memahami VM dengan lebih mudah.

Sebagai mahasiswa, Anda dapat menggunakan VM untuk berbagai keperluan, seperti:

- Menjalankan sistem operasi yang berbeda. Anda dapat menjalankan sistem operasi Windows, Linux, atau macOS di VM yang sama.
- Menjalankan aplikasi yang tidak kompatibel dengan sistem operasi Anda. Anda dapat menjalankan aplikasi Windows di VM macOS atau aplikasi macOS di VM Windows.
- Melakukan pengujian dan pengembangan software. Anda dapat membuat lingkungan pengujian yang terisolasi untuk menguji aplikasi Anda.

Berikut adalah beberapa tips untuk menggunakan VM:

- Pilih perangkat lunak VM yang tepat. Ada banyak perangkat lunak VM yang tersedia, seperti VMware, VirtualBox, dan Hyper-V. Pilih perangkat lunak yang sesuai dengan kebutuhan Anda.
- Alokasikan sumber daya yang cukup untuk VM Anda. VM membutuhkan sumber daya komputer, seperti CPU, memori, dan penyimpanan. Alokasikan sumber daya yang cukup agar VM Anda dapat berjalan dengan lancar.
- Buat cadangan VM Anda. VM dapat rusak atau hilang. Buat cadangan VM Anda secara berkala agar Anda dapat memulihkannya jika terjadi kerusakan.