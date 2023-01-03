# Jobsheet-1-Embedded-System

### DASAR PEMROGRAMAN ESP32 UNTUK PEMROSESAN DATA INPUT/OUTPUT ANALOG DAN DIGITAL

##### I. Teori Dasar
 

ESP-32 adalah mikrokontroler yang dikenalkan oleh Espressif System merupakan penerus dari mikrokontroler ESP8266. Pada mikrokontroler ini sudah tersedia modul WiFi     dalam chip sehingga sangat mendukung untuk membuat sistem aplikasi Internet of Things. Perbedaan antara ESP32 dengan ESP8266 adalah pada bagian prosesornya. ESP32 sudah  Dual-Core 32 bit, jelas lebih cepat ESP32 secara kinerja. Selain itu modul ini juga mempunyai bluetooth, satu fitur yang tidak ada di ESP8266.

##### II. Alat dan Bahan yang Digunakan
1) ESP32
2) Breadboard
3) Kabel jumper
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)

##### III. Percobaan
A. Instalasi Board ESP32 pada Arduino IDE
   1. Buka Arduino IDE
   2. Kemudian klik Menu File > Preferences
   3. Pada kolom Additional ... yang ada dibawah, tambahkan link berikut https://dl.espressif.com/dl/package_esp32_index.json
   4. Klik menu Tools > Board: > Pilih Boards Manager ...
   5. Pada kolom pencarian tulis ESP32 kemudian install dan tunggu sampai selesai.

B. Mengakses GPIO dan PWM ESP32
a) GPIO
1. Buatlah rangkaian seperti pada Gambar di bawah ini.

![GPIO](https://user-images.githubusercontent.com/121251478/210331374-b2cdad6b-fd8e-4c3b-9e9e-efc662318e47.jpeg)


2. Buka program example blink, kemudian modifikasi dan buat agar LED dapat melakukan blink dengan interval 100ms, 1 detik, 2 detik dan 3 detik sekali. Setelah itu, buatlah program agar LED dapat blink 1 detik sekali menggunakan timer milis(). Dokumentasikan hasilnya.
3. Buatlah program seperti pada script GPIO1.ino untuk mengendalikan led menggunakan push button. Kemudian upload program tersebut pada ESP32 dan dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121251478/210331397-cc05c3aa-043a-44c6-84d4-7b6368e8eeb6.mp4



4. Tambahkan 1 LED dan 1 push button pada rangkaian, kemudian kembangkan program agar ketika push button ke-2 ditekan, LED akan melakukan blink setiap 500 ms sekali. Kemudian dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121251478/210331424-20ecace5-2672-4d3c-9c49-abb06ac437ea.mp4



5. Tambahkan 3 LED dan 1 push button pada rangkaian, kemudian kembangkan program agar ketuka push button ke-3 ditekan, LED akan menyala menjadi running led (menyala bergantian dari kiri ke kanan). Setelah itu dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121251478/210331472-19a68e79-4ec7-4edf-977f-0efa4dae4537.mp4



b) PWM

1. Buatlah rangkaian seperti pada gambar di bawah ini.

![PWM](https://user-images.githubusercontent.com/121251478/210331511-b677e00c-f74f-4a9b-b61b-a5f86c7402c7.jpeg)


2. Buatlah script program seperti berikut.
3. Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta dokumentasikan hasilnya



https://user-images.githubusercontent.com/121251478/210331556-96e0c97b-0abc-4ece-b8a3-c7c120bc2db2.mp4



4. Buatlah program lanjutan seperti pada script berikut ini.
5. Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121251478/210331588-bb6a7a25-11b5-4738-a7e3-cad490295c5a.mp4



C. ADC dan DAC
1. Buatlah rangkaian seperti pada gambar di bawah ini.

![ADC_DAC](https://user-images.githubusercontent.com/121251478/210331615-4fbbdd04-0c6c-4c38-9e2b-f9836f7e85c4.jpeg)


2. Buatlah program seperti pada script berikut ini
3. Putar potensiometer secara perlahan agar mendapatkan nilai 0 hingga 4095 pada tampilan serial monitor. Analisis apa yang terjadi dan dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121251478/210331649-fda9f117-1137-40c7-aa22-891ef767dd01.mp4



4. Buatlah program seperti pada script berikut ini.Tambahkan LED pada GPIO5.
5. Upload program, kemudian putar potensiometer dari nilai terendah hingga nilai tertinggi. Amati yang terjadi, analisis dan dokumentasikan hasilnya.




https://user-images.githubusercontent.com/121251478/210331673-525a4614-fe7f-45ac-a4e3-6a4589dedee7.mp4


