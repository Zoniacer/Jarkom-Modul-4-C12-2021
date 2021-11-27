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
   - Foosha<br>
   - Water7<br>
   - Pucci<br>
   - Guanhao<br>
   - Alabasta<br>
   - Oimo<br>
   - Seastone<br>
   - Jipangu<br>
   - Courtyard<br>
   - Calmbelt<br>
   - Cipher<br>
   - Blueno<br>
   - Doriki<br>
   - Jabra<br>
   - Maingate<br>
   - Jorge<br>
   - Fukurou<br>
   - Enieslobby<br>
   - Elena<br>
3. Konfigurasi Routing<br>
   - Foosha<br>
   - Water7<br>
   - Pucci<br>
   - Guanhao<br>
   - Alabasta<br>
   - Oimo<br>
   - Seastone<br>
4. Test Ping<br>
pingtest<br>


## CIDR
Perhitungan pada teknik CIDR juga didasarkan pada jumlah komputer/ host yang ada di dalam subnet. Tetapi cara mendapatkan subnet besar tidak sama dengan VLSM. Penerapan teknik CIDR dapat dilakukan dengan langkah sebagai berikut.
- Pertama, menentukan pembagian subnet A dimana untuk pembagiaannya sama dengan metode VLSM yaitu sebagai berikut
![ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680304-9ed88e0e-2907-43c9-81b5-92a8b429ac3d.png)

- Kedua, membagi menjadi subnet B dengan pengelompokan sebagai berikut,<br>
B1/20 <-> A1/25 & A2/21<br>
B2/21 <-> A8/24 & A7/22<br>
B3/22 <-> A11/28 & A12/23<br>
![page 9 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680518-8d57ff55-9531-4bd0-b7b1-5901c221cdb5.png)

- Ketiga, membagi menjadi subnet C dengan pengelompokan sebagai berikut,<br>
C1/19 <-> B1/20 & A3/30<br>
C2/20 <-> B2/21 & A15/30<br>
C3/21 <-> B3/22 & A10/22<br>
![page 10 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680798-445c9435-dacf-4139-bdec-e8049ce781be.png)

- Keempat, membagi menjadi subnet D dengan pengelompokan sebagai berikut,<br>
D1/19 <-> C1/19 & A4/22<br>
D2/20 <-> C2/20 & A9/30<br>
![page 11 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680799-60c7b3cb-5c4b-4460-a1b4-0ad95ca5f3bf.png)

- Kelima, membagi menjadi subnet E dengan pengelompokan sebagai berikut,<br>
E1/17 <-> D1/19 & A5/30<br>
E2/18 <-> D2/20 & C3/21<br>
![page 12 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680803-08d61db1-a010-4639-bc4d-0628f6c5be09.png)

- Keenam, membagi menjadi subnet F dengan pengelompokan sebagai berikut,<br>
F1/16 <-> E1/17 & A6/22<br>
F2/17 <-> E2/18 & A13/30<br>
![page 13 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680806-1983923f-8d8b-486f-bcae-e42b892e8812.png)

- Ketujuh, membagi menjadi subnet G dengan pengelompokan sebagai berikut,<br>
G1/16 <-> F2/17 & A14/30<br>
![page 14ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680812-66315ea4-fab0-49fd-99a1-f43fa8f0f2f1.png)

- Delapan, membagi menjadi subnet besar H dengan pengelompokan sebagai berikut,<br>
H1/15 <-> G1/16 & F1/16<br>
![page 15 ShiftModul4 Revisi](https://user-images.githubusercontent.com/73422724/143680823-2718cd60-6c6a-4394-8b3c-5acb8c784ce3.png)

- Dari proses penggabungan yang telah dilakukan, didapatkan sebuah subnet besar dengan netmask /15. Lalu, dilakukan perhitungan pembagian IP dengan tree berdasarkan penggabungan subnet yang telah dilakukan. Untuk IP yang digunakan menggunakan prefix IP sehingga 10.20.0.0/15 untuk subnet terbesar menghasilkan tree berikut,
![ShiftModul4 CIDR tree-Page-2](https://user-images.githubusercontent.com/73422724/143680932-48a575ad-9ecc-416e-bb55-e79ca64e5db3.png)

Dibentuk menjadi tabel sebagai berikut.
|Subnet|Netmask|IP|Subnet Mask|
|---|---|---|---|
|A1|	/25|	10.21.8.0|	255.255.255.128|
|A2|	/21|	10.21.0.0|	255.255.248.0|
|A3|	/30|	10.21.16.0|	255.255.255.252|
|A4|	/22|	10.21.32.0|	255.255.252.0|
|A5|	/30|	10.21.64.0|	255.255.255.252|
|A6|	/22|	10.21.128.0|	255.255.252.0|
|A7|	/22|	10.20.0.0|	255.255.252.0|
|A8|	/24|	10.20.4.0|	255.255.255.0|
|A9|	/30|	10.20.8.0|	255.255.255.252|
|A10|	/22|	10.20.36.0|	255.255.252.0|
|A11|	/28|	10.20.34.0|	255.255.255.240|
|A12|	/23|	10.20.32.0|	255.255.254.0|
|A13|	/30|	10.20.64.0|	255.255.255.252|
|A14|	/30|	10.20.128.0|	255.255.255.252|
|A15|	/30|	10.20.16.0|	255.255.255.252|

### Langkah Pengerjaan
1. Pembuatan Topologi pada GNS3<br>
![Screenshot 2021-11-27 184706](https://user-images.githubusercontent.com/73422724/143680016-3d9630a9-7493-4418-b24a-9062ce32c4a8.png)

2. Konfigurasi Interface<br>
   - Foosha<br>
   - Water7<br>
   - Pucci<br>
   - Guanhao<br>
   - Alabasta<br>
   - Oimo<br>
   - Seastone<br>
   - Jipangu<br>
   - Courtyard<br>
   - Calmbelt<br>
   - Cipher<br>
   - Blueno<br>
   - Doriki<br>
   - Jabra<br>
   - Maingate<br>
   - Jorge<br>
   - Fukurou<br>
   - Enieslobby<br>
   - Elena<br>
3. Konfigurasi Routing<br>
   - Foosha<br>
   - Water7<br>
   - Pucci<br>
   - Guanhao<br>
   - Alabasta<br>
   - Oimo<br>
   - Seastone<br>
4. Test Ping<br>
pingtest<br>
