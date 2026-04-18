# Laporan Pratikum JK IF

## Tujuan Pratikum
Mempelajari python untuk TCP dan UDP

## Langkah Percobaan/Jawaban 

Simple TCP & UDP Socket Programming (Python)
Project ini berisi implementasi sederhana komunikasi Client–Server menggunakan Python Socket dengan dua protokol:
TCP (connection-oriented)
UDP (connectionless)
Program utama: client mengirim pesan → server mengubah menjadi huruf besar → server mengirim kembali ke client.

1. Isi Project

tcp-server.py
tcp-client.py
udp-server.py
udp-client.py

Port yang digunakan: 12000

2. Persiapan
Pastikan Python sudah terinstall.
Cek versi:
python --version


1. Menjalankan TCP

2. Jalankan Server (terminal 1)
python tcp-server.py
Output:
[SYSTEM] Server TCP siap digunakan!

3. Jalankan Client (terminal 2)
python tcp-client.py
Ketik pesan:
halo
Balasan dari server:
HALO
Ketik exit untuk keluar.

1. Menjalankan UDP

2. Jalankan Server (terminal 1)
python udp-server.py

3. Jalankan Client (terminal 2)
python udp-client.py
Ketik pesan:
halo udp
Balasan:
HALO UDP
Perintah keluar:
exit   → mematikan server & client
keluar → hanya client


Menjalankan Antar Laptop (Opsional)
Jika server dan client dijalankan di perangkat berbeda:

1. Cari IP server:
ipconfig
Contoh:
IPv4 Address : 192.168.1.5

2. Ganti di file client:
serverName = "192.168.1.5"
Pastikan kedua perangkat berada di jaringan WiFi yang sama.

Perbedaan Singkat TCP vs UDP

TCP:
-Harus membuat koneksi terlebih dahulu
-Lebih stabil dan data dijamin sampai
-Sedikit lebih lambat

UDP:
-Tidak perlu koneksi
-Lebih cepat dan ringan
-Tidak menjamin data sampai

Tujuan Project
Belajar dasar socket programming, komunikasi jaringan, serta memahami perbedaan TCP dan UDP menggunakan Python.

## Lampiran
[Hasil Percobaan](../assets/image/week7_1.png)
[Hasil Percobaan](../assets/image/week7_2.png)