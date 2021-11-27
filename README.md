# Jarkom-Modul-4-C12-2021

### C12
Daffa Amanullah Setyawan - 05111940000071\
Satrio Hanif Wicaksono - 05111940000103\
Shidqi Dhaifullah - 05111940000108

### PRAKTIKUM MODUL 4

## VLSM
### Pemetaan Subnet
Pemetaan subnet dilakukan dengan cara mengelompokkan setiap PC yang terhubung ke router. Berikut hasil pemetaan subnet A:<br>
![4-vlsm](https://user-images.githubusercontent.com/81344394/143682439-fa963f2a-c0c9-4fc1-a436-80d296485b73.png)<br>
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
![4-vlsmtree](https://user-images.githubusercontent.com/81344394/143682453-f7c4537e-0f18-41bc-b86d-13c1ceb095d9.png)<br>
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
![4-cpt](https://user-images.githubusercontent.com/81344394/143682466-369c6f14-8c7b-41c7-bc26-ea41ea76d018.png)<br>
2. Konfigurasi Interface<br>
   - Foosha<br>
![4-foosha1](https://user-images.githubusercontent.com/81344394/143682477-ea00243e-7963-43fe-89f1-980808fa8606.png)
![4-foosha2](https://user-images.githubusercontent.com/81344394/143682478-34861350-5799-45b6-a3fd-da34e9bb6c7b.png)
![4-foosha3](https://user-images.githubusercontent.com/81344394/143682479-8d7ca89b-9676-405c-a27b-ab22c2edfa95.png)
![4-foosha4](https://user-images.githubusercontent.com/81344394/143682481-419332a4-cff2-4c19-b82a-8170379dc04d.png)
   - Water7<br>
![4-water71](https://user-images.githubusercontent.com/81344394/143682499-4996fc7c-be0e-4d82-b0fb-f92a1584c76a.png)
![4-water72](https://user-images.githubusercontent.com/81344394/143682500-23bdfb53-2c10-4746-9a9c-d2fbf5a5fe3f.png)
![4-water73](https://user-images.githubusercontent.com/81344394/143682501-a7608e77-869f-4479-88de-e6bf072775de.png)
   - Pucci<br>
![4-pucci1](https://user-images.githubusercontent.com/81344394/143682512-21203aca-22b9-4147-b499-90fdb143af18.png)
![4-pucci2](https://user-images.githubusercontent.com/81344394/143682513-b308ce25-736a-4a42-abb7-ccb5d71f9400.png)
![4-pucci3](https://user-images.githubusercontent.com/81344394/143682515-467d4b10-43f0-41ca-865a-e342055e7f30.png)
   - Guanhao<br>
![4-guanhao1](https://user-images.githubusercontent.com/81344394/143682528-3babcb2f-0c46-4a1a-844e-003cbaad06c5.png)
![4-guanhao2](https://user-images.githubusercontent.com/81344394/143682529-e6d06a19-b9d7-4290-859c-4b1e376ceeca.png)
![4-guanhao3](https://user-images.githubusercontent.com/81344394/143682531-8c543537-402c-478c-802f-6bd69638a62b.png)
![4-guanhao4](https://user-images.githubusercontent.com/81344394/143682532-21ad166b-41c8-4ef4-bb09-22789dbb515b.png)
   - Alabasta<br>
![4-alabasta1](https://user-images.githubusercontent.com/81344394/143682540-6c88c670-7a6b-4e7b-a800-e7f67b4f66bb.png)
![4-alabasta2](https://user-images.githubusercontent.com/81344394/143682542-89307fff-52be-4266-8e29-0d9a343cf767.png)
   - Oimo<br>
![4-oimo1](https://user-images.githubusercontent.com/81344394/143682548-75e521ee-fb30-4af2-837e-b05b80402b6f.png)
![4-oimo2](https://user-images.githubusercontent.com/81344394/143682549-33001f3f-acf4-454d-9c04-cdaa76438ed8.png)
![4-oimo3](https://user-images.githubusercontent.com/81344394/143682551-50629a96-db85-4e46-b256-dd63628d4875.png)
   - Seastone<br>
![4-seastone1](https://user-images.githubusercontent.com/81344394/143682555-f15e385d-9909-4800-af07-53996d407f59.png)
![4-seastone2](https://user-images.githubusercontent.com/81344394/143682556-93cb5bce-ce34-4e2e-a3ef-f6526579e59e.png)
   - Jipangu<br>
![4-jipangu](https://user-images.githubusercontent.com/81344394/143682559-4a720b15-e0dd-4e06-b118-ff2b298c7692.png)
   - Courtyard<br>
![4-courtyard](https://user-images.githubusercontent.com/81344394/143682568-83341934-deb2-4f38-beed-25cf75682040.png)
   - Calmbelt<br>
![4-calmbelt](https://user-images.githubusercontent.com/81344394/143682581-65d6b624-8511-4d47-8b33-2485312643b8.png)
   - Cipher<br>
![4-cipher](https://user-images.githubusercontent.com/81344394/143682584-d1c6bc9d-0276-4bff-9660-188f943c176f.png)
   - Blueno<br>
 ![4-blueno](https://user-images.githubusercontent.com/81344394/143682591-22b479c2-b4c4-4965-ad1a-a9428c425ba6.png)
   - Doriki<br>
![4-doriki](https://user-images.githubusercontent.com/81344394/143682603-eac17f0e-866c-46e2-bcd8-c0b7149993bb.png)
   - Jabra<br>
![4-jabra](https://user-images.githubusercontent.com/81344394/143682611-9e60eb60-54a9-4cd9-a594-4a0edb6aade8.png)
   - Maingate<br>
![4-maingate](https://user-images.githubusercontent.com/81344394/143682617-3d56bc8d-be8f-4a80-a28b-497746904456.png)
   - Jorge<br>
![4-jorge](https://user-images.githubusercontent.com/81344394/143682622-e9b5efab-a7dc-4e51-b98e-aafb0cafc783.png)
   - Fukurou<br>
![4-fukurou](https://user-images.githubusercontent.com/81344394/143682626-1b2db219-56eb-4f6a-9549-f595ab5a47d9.png)
   - Enieslobby<br>
![4-enieslobby](https://user-images.githubusercontent.com/81344394/143682627-469da078-e0c2-464c-8f94-d36433d80123.png)
   - Elena<br>
![4-elena](https://user-images.githubusercontent.com/81344394/143682630-4d1dfe80-dba7-46eb-907f-272754f3ce90.png)
3. Konfigurasi Routing<br>
   - Foosha<br>
![4-fooshar1](https://user-images.githubusercontent.com/81344394/143682665-f135ca32-9a25-457e-b430-216b9be7a13f.png)
![4-fooshar2](https://user-images.githubusercontent.com/81344394/143682667-ae328707-0c8e-409c-98e5-a0525b23cdee.png)
![4-fooshar3](https://user-images.githubusercontent.com/81344394/143682668-78075b2a-60a0-4ac2-8181-bdb81958d30e.png)
   - Water7<br>
![4-water7r](https://user-images.githubusercontent.com/81344394/143682671-c6bda48b-82d3-4ac1-992e-604fc5c9b226.png)
   - Pucci<br>
![4-puccir](https://user-images.githubusercontent.com/81344394/143682675-772df000-40d1-44f3-8dde-8543e67859d9.png)
   - Guanhao<br>
![4-guanhaor1](https://user-images.githubusercontent.com/81344394/143682677-4db6d703-de12-4358-b3f1-04a495ddc9aa.png)
![4-guanhaor2](https://user-images.githubusercontent.com/81344394/143682678-7713ff03-5717-470a-8a0b-e360c84e2228.png)
   - Alabasta<br>
![4-alabastar](https://user-images.githubusercontent.com/81344394/143682680-0226f18a-d103-4d6f-9b96-06c41f142f48.png)
   - Oimo<br>
![4-oimor](https://user-images.githubusercontent.com/81344394/143682681-b9ca7f14-84e9-4aeb-bbb5-ac9a075dec70.png)
   - Seastone<br>
![4-seastoner](https://user-images.githubusercontent.com/81344394/143682684-bebb9e89-7629-45cd-bea4-a54fc0beb6d9.png)
4. Test Ping<br>
![4-pingtest](https://user-images.githubusercontent.com/81344394/143682686-9bc2bf77-0b08-49eb-829e-2c91cf45f75a.png)<br>


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

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet dhcp<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.21.128.1<br>
netmask 255.255.252.0<br>

auto eth2<br>
iface eth2 inet static<br>
address 10.21.64.1<br>
netmask 255.255.255.252<br>

auto eth3<br>
iface eth3 inet static<br>
address 10.20.64.1<br>
netmask 255.255.255.252<br>

auto eth4<br>
iface eth4 inet static<br>
address 10.20.128.1<br>
netmask 255.255.255.252<br>

   - Water7<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.64.2<br>
netmask 255.255.255.252<br>
gateway 10.21.64.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.21.32.1<br>
netmask 255.255.252.0<br>

auto eth2<br>
iface eth2 inet static<br>
address 10.21.16.1<br>
netmask 255.255.255.252<br>

   - Pucci<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.16.2<br>
netmask 255.255.255.252<br>
gateway 10.21.16.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.21.8.1<br>
netmask 255.255.255.128<br>

auto eth2<br>
iface eth2 inet static<br>
address 10.21.0.1<br>
netmask 255.255.248.0<br>

   - Guanhao<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.64.2<br>
netmask 255.255.255.252<br>
gateway 10.20.64.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.20.36.1<br>
netmask 255.255.252.0<br>

auto eth2<br>
iface eth2 inet static<br>
address 10.20.8.1<br>
netmask 255.255.255.252<br>

auto eth3<br>
iface eth3 inet static<br>
address 10.20.32.1<br>
netmask 255.255.254.0<br>

   - Alabasta<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.32.2<br>
netmask 255.255.254.0<br>
gateway 10.20.32.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.20.34.1<br>
netmask 255.255.255.240<br>

   - Oimo<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.8.2<br>
netmask 255.255.255.252<br>
gateway 10.20.8.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.20.4.1<br>
netmask 255.255.255.0<br>

auto eth2<br>
iface eth2 inet static<br>
address 10.20.16.1<br>
netmask 255.255.255.252<br>

   - Seastone<br>

auto lo<br>
iface lo inet loopback<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.4.3<br>
netmask 255.255.255.0<br>
gateway 10.20.4.1<br>

auto eth1<br>
iface eth1 inet static<br>
address 10.20.0.1<br>
netmask 255.255.252.0<br>

   - Jipangu<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.8.2<br>
netmask 255.255.255.128<br>
gateway 10.21.8.1<br>

   - Courtyard<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.0.3<br>
netmask 255.255.248.0<br>
gateway 10.21.0.1<br>

   - Calmbelt<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.0.2<br>
netmask 255.255.248.0<br>
gateway 10.21.0.1<br>

   - Cipher<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.32.2<br>
netmask 255.255.252.0<br>
gateway 10.21.32.1<br>

   - Blueno<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.21.128.2<br>
netmask 255.255.252.0<br>
gateway 10.21.128.1<br>

   - Doriki<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.128.2<br>
netmask 255.255.255.252<br>
gateway 10.20.128.1<br>

   - Jabra<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.36.2<br>
netmask 255.255.252.0<br>
gateway 10.20.36.1<br>

   - Maingate<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.32.3<br>
netmask 255.255.254.0<br>
gateway 10.20.32.1<br>

   - Jorge<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.34.2<br>
netmask 255.255.255.240<br>
gateway 10.20.34.1<br>

   - Fukurou<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.16.2<br>
netmask 255.255.254.0<br>
gateway 10.20.16.1<br>

   - Enieslobby<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.4.2<br>
netmask 255.255.255.0<br>
gateway 10.20.4.1<br>

   - Elena<br>

auto eth0<br>
iface eth0 inet static<br>
address 10.20.0.2<br>
netmask 255.255.252.0<br>
gateway 10.20.0.1<br>

3. Konfigurasi Routing<br>
   - Foosha<br>

route add -net 10.21.0.0 netmask 255.255.248.0 gw 10.21.64.2<br>
route add -net 10.21.8.0 netmask 255.255.255.128 gw 10.21.64.2<br>
route add -net 10.21.16.0 netmask 255.255.255.252 gw 10.21.64.2<br>
route add -net 10.21.32.0 netmask 255.255.252.0 gw 10.21.64.2<br>
route add -net 10.20.36.0 netmask 255.255.252.0 gw 10.20.64.2<br>
route add -net 10.20.8.0 netmask 255.255.255.252 gw 10.20.64.2<br>
route add -net 10.20.32.0 netmask 255.255.254.0 gw 10.20.64.2<br>
route add -net 10.20.34.0 netmask 255.255.255.240 gw 10.20.64.2<br>
route add -net 10.20.4.0 netmask 255.255.255.0 gw 10.20.64.2<br>
route add -net 10.20.0.0 netmask 255.255.252.0 gw 10.20.64.2<br>
route add -net 10.20.16.0 netmask 255.255.254.0 gw 10.20.64.2<br>

   - Water7<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.64.1<br>
route add -net 10.21.0.0 netmask 255.255.248.0 gw 10.21.16.2<br>
route add -net 10.21.8.0 netmask 255.255.255.128 gw 10.21.16.2<br>

   - Pucci<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.21.16.1<br>

   - Guanhao<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.20.64.1<br>
route add -net 10.20.0.0 netmask 255.255.252.0 gw 10.20.8.2<br>
route add -net 10.20.4.0 netmask 255.255.255.0 gw 10.20.8.2<br>
route add -net 10.20.16.0 netmask 255.255.254.0 gw 10.20.8.2<br>
route add -net 10.20.34.0 netmask 255.255.255.240 gw 10.20.32.2<br>

   - Alabasta<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.20.32.1<br>

   - Oimo<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.20.8.1<br>
route add -net 10.20.0.0 netmask 255.255.252.0 gw 10.20.4.3<br>

   - Seastone<br>

route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.20.4.1<br>


4. Test Ping<br>
- Sebelum testing lakukan perintah berikut pada Foosha
iptables -t nat -A POSTROUTING  -o eth0 -j MASQUERADE -s 10.20.0.0/15

- Lalu, lakukan perintah berikut untuk semua pc yang terhubung
echo nameserver 192.168.122.1 > /etc/resolv.conf

- Setelah itu, testing dengan ping ke suatu situs atau yang IP yang terhubung dimisalkan sebagai berikut.<br>

Elena --> ping its.ac.id, ping google.com, ping my.its.ac.id
![elena Screenshot 2021-11-27 165750](https://user-images.githubusercontent.com/73422724/143683077-75f389b0-98b8-48bc-8e2a-cfd58abc9936.png)

Elena --> ping its.ac.id, ping google.com, ping my.its.ac.id
![enieslobby Screenshot 2021-11-27 162105](https://user-images.githubusercontent.com/73422724/143683080-5a2d76b0-ca3e-4434-90a6-b155bc8d2e85.png)

Elena --> ping its.ac.id, ping google.com, ping my.its.ac.id
![Blueno Screenshot 2021-11-27 155350](https://user-images.githubusercontent.com/73422724/143683088-c7d51979-abbb-45d7-acb1-d17f6160bdd7.png)
