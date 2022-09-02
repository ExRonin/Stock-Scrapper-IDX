# Scrapper Saham Indonesia

## Overview

IDX Scrapper merupakan sebuah scrapper yang dibuat menggunakan bahasa Python. Scrapper ini memanfaatkan endpoint-endpoint dari API yang dimiliki oleh PT Bursa Efek Indonesia (BEI) pada websitenya yaitu [idx.co.id](https://idx.co.id).

## Cara Penggunaan

Anda dapat langsung menggunakan script yang ada dengan meng-clone atau download repository ini. Setelah berhasil di-download, masuk ke dalam folder dan install library yang dibutuhkan oleh program untuk bekerja. Anda dapat dengan mudah menginstalnya dengan menggunakan pip.

```
pip install -r requirements.txt
```

Setelah melakukan instalasi library, Anda sudah bisa menjalankan script yang ada di file ini. Pastikan untuk mengambil list emiten terlebih dahulu sebelum mengambil data dari emiten tersebut.

```
python get-list-emiten.py
python get-data-emiten.py
```

Download data bisa sampai dengan 3-4 jam. Jadi harap bersabar :)

### Penggunaan Untuk Komersial

Mengacu pada [Syarat Penggunaan](https://idx.co.id/footer-menu/tautan-langsung/syarat-penggunaan/) PT Bursa Efek Indonesia Nomor 5:

> Pengguna dilarang menggunakan atau menyebarluaskan Informasi yang diperoleh dari Website kepada pihak lain untuk tujuan komersial tanpa izin tertulis terlebih dahulu dari Bursa Efek Indonesia dan/atau pemilik asal dari Informasi dan atau data tersebut.

Pengguna scrapper ini dilarang keras untuk menggunakan informasi untuk tujuan komersial apapun tanpa persetujuan tertulis dari PT Bursa Efek Indonesia dan/atau pemilik asal data yang Anda ambil. Pemilik projek ini tidak bertanggungjawab apapun apabila pengguna menyalahi aturan ini dan tidak dapat dituntut secara hukum.

## Lisensi

Projek ini dilisensikan dengan CC BY-NC 4.0. Lisensi ini membatasi Anda untuk tidak menggunakan data atau apapun yang berhubungan dengan projek ini untuk tujuan komersial.

Anda dapat membaca lisensi di [sini](LICENSE.md). Rangkuman pendek dari lisensi ini dapat Anda baca di [sini](https://creativecommons.org/licenses/by-nc/4.0/)
