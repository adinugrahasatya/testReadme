[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ubkbB4F7)
# Modul 9: Tugas Besar

<details>
  <summary>Daftar Isi</summary>
  <ol>
    <li><a href="#Contributors">Contributors</a></li>
    <li><a href="#Deskripsi">Deskripsi</a></li>
    <li><a href="#Kompilasi">Kompilasi</a></li>
    <li><a href="#Perintah Run">Perintah Run</a></li>
    <li><a href="#Panduan Penggunaan">Panduan Penggunaan</a></li>
  </ol>
</details>

### Contributors

Praktikan PPMC Kelompok D3:
- Adi Nugraha (13221077)
- Mochamad Arif Firdaus (13221078)
- M. Zhafran Arrafi Anwar (13221079)
- Danish Muhammad Hafidz (13221080) <br>

Asisten: Aloysius Efrata Sumaryo (13220057) <br>

### Deskripsi
Program disusun untuk menentukan rute pelayaran kapal kargo negara api sehingga negara api dapat menghemat biaya bahan bakar kapal kargo. Program disusun menggunakan algoritma *Travelling Salesman Problem* (TSP).

Program menerima data pelabuhan dari file bernama `pelabuhan.csv` yang memuat daftar nama pelabuhan beserta koordinat lintang bujurnya, seperti tertera berikut:

    Pelabuhan,Lintang,BujurKotaBaSingSe,25.0330,121.5654
    KotaOmashu,10.3157,123.8854
    DesaPulauKyoshi,10.4744,98.9305

Setelah itu, program menampilkan rute paling pendek untuk mengunjungi semua pelabuhan tersebut satu kali saja lalu kembali ke pelabuhan awal dimana kapal tersebut berangkat dan menampilkan jarak total dari rute tersebut.

Kapal kargo standar negara api memiliki jarak tempuh maksimal 2500km setelah berangkat dari satu pelabuhan. Program akan menampilkan daftar pelabuhan yang tidak dapat dikunjungi sehingga negara api dapat menjadwalkan pengiriman menggunakan kapal kargo jarak jauh.

### Kompilasi
Program dapat dikompilasi dengan perintah berikut:

```bash
make main
```

Kompilasi akan menghasilkan *executable* bernama `main` atau `main.exe` pada komputer dengan sistem operasi Windows.

### Perintah Run
File *executable* dapat dijalankan dengan perintah:

```bash
./main
```

atau

```bash
main.exe
```

### Panduan Penggunaan
Jelaskan cara pengguna dapat menggunakan program Anda di bagian ini.
