# Muhammad-Iman-Kurnia_Tugas-Praktikum-Ke-6_SK3B

Tugas Praktikum Ke 6

Nama  : Muhammad Iman Kurnia

NIM   : 09011282328044

Kelas : SK3B

Pertama-tama kita ubah dulu settingan network nya di virtual box ke Bridged Adapter. Caranya buka dulu aplikasi virtual box, lalu ke setting, kemudian pilih ke network, dan di bagian Attached to nya ubah ke 
Bridged Adapter
![Screenshot 2024-10-02 102133](https://github.com/user-attachments/assets/4319507a-589e-4491-9639-e4c27639a251)
Kita harus sambungkan dulu perangkat kita ke jaringan/wifi agar bisa terhubung ke server

Selanjutnya pergi ke terminal linux, lalu kita gunakan command ifconfig untuk mengecek ip addres kita
![Screenshot from 2024-10-02 10-25-00](https://github.com/user-attachments/assets/d3fcacae-7cf3-40a0-872e-06879a7d5ba8)
Bisa dilihat di gambar kalau ip addres nya adalah 192.168.1.13 (dibawah tulisan flags=4163)

Kemudian kita menggunakan command ssh yang digunakan untuk melakukan koneksi aman ke sistem lain melalui jaringan. Caranya adalah kita ketik ssh, kemudian nama user, terus @, dan kita masukkan ip addres nya. Contoh : ssh muhammad-iman-kurnia@192.168.1.13
![Screenshot from 2024-10-02 10-25-13](https://github.com/user-attachments/assets/ae3d26ba-26a9-4447-a627-0aacfc408dad)

Kalau kita mau keluar dari server, kita tinggal ketik saja exit
![Screenshot from 2024-10-02 10-25-40](https://github.com/user-attachments/assets/183cea7e-12ae-4559-b49f-b5760f9f269f)



