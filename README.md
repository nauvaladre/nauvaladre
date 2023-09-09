    CARA MENGHITUNG IP ADDRESS
Untuk menghitung alamat IP (Internet Protocol), Anda perlu memahami dua versi IP yang paling umum digunakan: IPv4 (Internet Protocol versi 4) dan IPv6 (Internet Protocol versi 6). Mari kita bahas keduanya:

### IPv4 (Internet Protocol versi 4):
IPv4 menggunakan notasi desimal berbasis 10 dan terdiri dari empat oktet (blok) angka desimal yang dipisahkan oleh titik. Contoh alamat IPv4 adalah seperti ini: 192.168.1.1.

1. **Konversi ke Biner:** Ubah setiap oktet (angka antara dua titik) menjadi bentuk biner. Misalnya, alamat IPv4 192.168.1.1 akan menjadi:
   - Oktet 1: 11000000
   - Oktet 2: 10101000
   - Oktet 3: 00000001
   - Oktet 4: 00000001

2. **Hitung Subnet:** Anda juga perlu mengetahui subnet mask. Subnet mask digunakan untuk membagi alamat IP menjadi jaringan (network) dan host. Misalnya, subnet mask 255.255.255.0 berarti 24 bit pertama digunakan untuk jaringan dan 8 bit terakhir untuk host.

3. **Hitung Jumlah Host:** Dalam subnet tersebut, hitung jumlah host yang mungkin dengan formula 2^(jumlah bit host) - 2. Pengurangan 2 adalah untuk alamat jaringan (network address) dan alamat broadcast (broadcast address), yang tidak dapat digunakan untuk host.

### IPv6 (Internet Protocol versi 6):
IPv6 menggunakan notasi heksadesimal berbasis 16 dan terdiri dari delapan blok angka heksadesimal yang dipisahkan oleh titik dua (::). Contoh alamat IPv6 adalah seperti ini: 2001:0db8:85a3:0000:0000:8a2e:0370:7334.

1. **Konversi ke Biner:** Ubah setiap blok heksadesimal menjadi bentuk biner. Misalnya, alamat IPv6 2001:0db8:85a3:0000:0000:8a2e:0370:7334 akan menjadi:

   (Heksadesimal pertama ke biner)
   - 2001: 0010 0000 0000 0001
   - 0db8: 0000 1101 1011 1000
   - 85a3: 1000 0101 1010 0011
   - 0000: 0000 0000 0000 0000
   - 0000: 0000 0000 0000 0000
   - 8a2e: 1000 1010 0010 1110
   - 0370: 0000 0011 0111 0000
   - 7334: 0111 0011 0011 0100

2. **Hitung Jumlah Host:** Alamat IPv6 memiliki jumlah host yang sangat besar, sehingga biasanya tidak perlu menghitung jumlah host secara manual. IPv6 dirancang untuk memiliki ruang alamat yang sangat besar untuk mengatasi kelangkaan alamat IPv4.

Itu adalah langkah-langkah umum untuk menghitung alamat IP. Untuk menghitung subnetting atau rincian lebih lanjut tentang alamat IP, Anda perlu memahami konsep lebih dalam, termasuk pembagian jaringan dan subnet mask.
