# Jarkom-Modul-4-C12-2021

## VLSM
### Pemetaan Subnet
Pemetaan subnet dilakukan dengan cara mengelompokkan setiap PC yang terhubung ke router. Berikut hasil pemetaan subnet A:<br>
vlsm<br>
|Subnet|Subnet Mask|Length|Jumlah IP|
|---|---|---|---|
|A1|255.255.255.128|/25|101|
|A2|255.255.248.0|/21|2021|
|A3|255.255.255.252|/30|2|
|A4|255.255.252.0|/22|701|
|A5|255.255.255.252|/30|2|
|A6|255.255.252.0|/22|1000|
|A7|255.255.252.0|/22|721|
|A8|255.255.255.0|/24|252|
|A9|255.255.255.252|/30|2|
|A10|255.255.252.0|/22|521|
|A11|255.255.255.240|/28|13|
|A12|255.255.254.0|/23|502|
|A13|255.255.255.252|/30|2|
|A14|255.255.255.252|/30|2|
|A15|255.255.255.252|/30|2|
### Perhitungan IP
Dengan menghitung jumlah total IP yang diperlukan, maka didaptkan bahwa perhitungan VLSM dimulai dari subnet /19. Hasil perhitungan IP sebagai berikut:<br>
vlsmtree<br>
|Subnet|IP Address|Subnet Mask|Length|Jumlah IP|
|---|---|---|---|---|
|A1|10.20.0.128|255.255.255.128|/25|101|
|A2|10.20.8.0|255.255.248.0|/21|2021|
|A3|10.20.0.0|255.255.255.252|/30|2|
|A4|10.20.4.0|255.255.252.0|/22|701|
|A5|10.20.0.4|255.255.255.252|/30|2|
|A6|10.20.24.0|255.255.252.0|/22|1000|
|A7|10.20.16.0|255.255.252.0|/22|721|
|A8|10.20.1.0|255.255.255.0|/24|252|
|A9|10.20.0.8|255.255.255.252|/30|2|
|A10|10.20.20.0|255.255.252.0|/22|521|
|A11|10.20.0.16|255.255.255.240|/28|13|
|A12|10.20.2.0|255.255.254.0|/23|502|
|A13|10.20.0.12|255.255.255.252|/30|2|
|A14|10.20.0.32|255.255.255.252|/30|2|
|A15|10.20.0.36|255.255.255.252|/30|2|
### Langkah Pengerjaan
1. Pembuatan Topologi pada CPT<br>
cpt<br>
2. Konfigurasi Interface<br>
   - Foosha
   - Water7
   - Pucci
   - Guanhao
   - Alabasta
   - Oimo
   - Seastone
   - Jipangu
   - Courtyard
   - Calmbelt
   - Cipher
   - Blueno
   - Doriki
   - Jabra
   - Maingate
   - Jorge
   - Fukurou
   - Enieslobby
   - Elena
3. Kongigurasi Routing<br>
   - Foosha
   - Water7
   - Pucci
   - Guanhao
   - Alabasta
   - Oimo
   - Seastone
4. Test Ping<br>
pingtest<br>


## CIDR
Perhitungan pada teknik CIDR juga didasarkan pada jumlah komputer/ host yang ada di dalam subnet. Tetapi cara mendapatkan subnet besar tidak sama dengan VLSM. Penerapan teknik CIDR dapat dilakukan dengan langkah sebagai berikut.

### Langkah Pengerjaan
1. Pembuatan Topologi pada GNS3<br>
![Screenshot 2021-11-27 184706](https://user-images.githubusercontent.com/73422724/143680016-3d9630a9-7493-4418-b24a-9062ce32c4a8.png)

2. Konfigurasi Interface<br>
   - Foosha
   - Water7
   - Pucci
   - Guanhao
   - Alabasta
   - Oimo
   - Seastone
   - Jipangu
   - Courtyard
   - Calmbelt
   - Cipher
   - Blueno
   - Doriki
   - Jabra
   - Maingate
   - Jorge
   - Fukurou
   - Enieslobby
   - Elena
3. Kongigurasi Routing<br>
   - Foosha
   - Water7
   - Pucci
   - Guanhao
   - Alabasta
   - Oimo
   - Seastone
4. Test Ping<br>
pingtest<br>
