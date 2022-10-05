# Cara install source code Flutter

### Flutter first

1. Pastikan kalian sudah menginstall Flutter dengan baik
2. Buka Terminal atau Command Prompt kalian dan ketik `flutter doctor` dan pastikan tidak ada yang silang atau belum terinstall.

## Visual Studio Code

### Install Flutter extension
1. Pastikan kedua extension ini sudah terinstall dengan baik.
   
   ![Dart](https://i.ibb.co/tPNgtX7/1.png)
   ![Flutter](https://i.ibb.co/gbYG8b5/2.png)

2. Setelah anda mendapatkan source code dari kami, extract zip tersebut dan buka folder extract tersebut dengan visual studio code
3. Setelah itu tekan `ctrl+shift+p` dan cari `Pub: Get Packages`
   
   ![Pub: Get Packages](https://i.ibb.co/xHCzhL9/3.png)

4. Setelah proses selesai, tekan lagi `ctrl+shift+p` dan cari `Flutter: Select Device` lalu pilih salah satu device yang terdapat disitu.

    ![Flutter: Select Device](https://i.ibb.co/2dbdRJd/4.png)
    ![Emulators](https://i.ibb.co/yW1xSqn/5.png)

5. Setelah emulator sudah jalan, pencet saja `F5` di semua file yang berakhiran `.dart` | ```Jika kalian masih di file .yaml atau yang lainnya maka akan terjadi error```

### Error Handling
1. Error umum yang sering dialami oleh client adalah error SDK, biasanya itu terjadi karena versi SDK client lebih rendah daripada versi SDK yang kita pakai. Untuk menyelesaikan error tersebut, buka Terminal atau Command Prompt kalian dan ketik `flutter upgrade` dan tunggu hingga proses selesai.