# Jarkom_Modul4_Lapres_T07

Lapres Praktikum Jarkom Modul 3<br />
<br />
![kelompok](https://img.shields.io/badge/Kelompok-T07-00a69a)<br />
<br />
Anggota:<br />
- ![fikri](https://img.shields.io/badge/Fikri%20Haykal-05311840000006-blueviolet)<br />
- ![syarif](https://img.shields.io/badge/Fancista%20Syarif%20H.-05311840000027-blueviolet)<br />

# Cisco Packet Tracer (VLSM)

## Topologi
  Membuat Topologi sesuai dengan soal
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Soal%20Shift%20Modul%204.png?raw=true)<br /><br />
  
## Subneting
  Menghitung IP yang dibutuhkan serta memberi label `AX` untuk setiap netmask
  <table>
    <tr>
      <th>Label</th>
      <th>Jumlah IP</th>
      <th>Netmask</th>
    </tr>
    <tr>
      <td>A1</td>
      <td>2</td>
      <td>/30</td>
    </tr>
    <tr>
      <td>A2</td>
      <td>2</td>
      <td>/30</td>
    </tr>
    <tr>
      <td>A3</td>
      <td>1001</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>A4</td>
      <td>502</td>
      <td>/23</td>
    </tr>
    <tr>
      <td>A5</td>
      <td>521</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>A6</td>
      <td>2</td>
      <td>/30</td>
    </tr>
    <tr>
      <td>A7</td>
      <td>701</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>A8</td>
      <td>2</td>
      <td>/30</td>
    </tr>
    <tr>
      <td>A9</td>
      <td>13</td>
      <td>/28</td>
    </tr>
    <tr>
      <td>A10</td>
      <td>252</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>A11</td>
      <td>721</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>A12</td>
      <td>2021</td>
      <td>/21</td>
    </tr>
    <tr>
      <td>A13</td>
      <td>101</td>
      <td>/25</td>
    </tr>
  </table>
  
  Menghitung pembagian IP berdasarkan NID dan Netmask
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Topologi%20VLSM.png?raw=true)<br /><br />
  
  Menghitung pembagian IP Server dengan IP DMZ
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Topologi%20VLSM-Server.png?raw=true)<br /><br />
  
## Pembagian IP
  Pemberian label `AX` pada topologi
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/VLSM.png?raw=true)<br /><br />
  
  Mengatur IP pada setiap interface berdasarkan subnet yang telah ditentukan
  - Router<br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Router.jpg?raw=true)<br /><br />
  - Client<br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Client.jpg?raw=true)<br /><br />
  - Server<br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Mojokerto.PNG?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Malang.PNG?raw=true)<br /><br />
  
## Routing
  Melakukan routing pada setiap interface router menuju subnet yang belum dikenal
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Surabaya.PNG?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Pasuruan.PNG?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Probolinggo.PNG?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Batu.PNG?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Kediri.PNG?raw=true)<br /><br />
  
# UML (CIDR)

## Topologi
  Membuat Topologi sesuai dengan soal
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Soal%20Shift%20Modul%204.png?raw=true)<br /><br />
  
## Subneting
  Mengelompokkan IP subnet menjadi subnet yang lebih besar. Dimulai dari subnet paling jauh.
  <table>
    <tr>
      <th>Label</th>
      <th>Gabungan</th>
      <th>Netmask</th>
    </tr>
    <tr>
      <td>B1</td>
      <td>A12 dan A13</td>
      <td>/20</td>
    </tr>
    <tr>
      <td>B2</td>
      <td>A9 dan A4</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>B3</td>
      <td>A10 dan A11</td>
      <td>/21</td>
    </tr>
    <tr>
      <td>C1</td>
      <td>A8 dan B1</td>
      <td>/19</td>
    </tr>
    <tr>
      <td>C2</td>
      <td>A5 dan B2</td>
      <td>/21</td>
    </tr>
    <tr>
      <td>C3</td>
      <td>A6 dan B3</td>
      <td>/20</td>
    </tr>
    <tr>
      <td>D1</td>
      <td>A7 dan C1</td>
      <td>/18</td>
    </tr>
    <tr>
      <td>D2</td>
      <td>C2 dan C3</td>
      <td>/19</td>
    </tr>
    <tr>
      <td>E1</td>
      <td>A2 dan D1</td>
      <td>/17</td>
    </tr>
    <tr>
      <td>E2</td>
      <td>A1 dan D2</td>
      <td>/18</td>
    </tr>
    <tr>
      <td>F1</td>
      <td>A3 dan E2</td>
      <td>/17</td>
    </tr>
    <tr>
      <td><b>G1 (total)</b></td>
      <td><b>E1 dan F1</b></td>
      <td><b>/16</b></td>
    </tr>
  </table>
  
  Menghitung pembagian IP berdasarkan NID dan Netmask
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Topologi%20CIDR.png?raw=true)<br /><br />
  
  Lalu berikut adalah command topologi pada UML
  ```
  #Switch
uml_switch –unix switch1 > /dev/null < /dev/null &
uml_switch –unix switch2 > /dev/null < /dev/null &
uml_switch –unix switch3 > /dev/null < /dev/null &
uml_switch –unix switch4 > /dev/null < /dev/null &
uml_switch –unix switch5 > /dev/null < /dev/null &
uml_switch –unix switch6 > /dev/null < /dev/null &
uml_switch –unix switch7 > /dev/null < /dev/null &
uml_switch –unix switch8 > /dev/null < /dev/null &
uml_switch –unix switch9 > /dev/null < /dev/null &
uml_switch –unix switch10 > /dev/null < /dev/null &
uml_switch –unix switch11 > /dev/null < /dev/null &
uml_switch –unix switch12 > /dev/null < /dev/null &
uml_switch –unix switch13 > /dev/null < /dev/null &
uml_switch –unix switch14 > /dev/null < /dev/null &
uml_switch –unix switch15 > /dev/null < /dev/null &

#Router
xterm –T SURABAYA –e linux ubd0=SURABAYA,jarkom umid=SURABAYA eth0=tuntap,,,10.151.74.68 eth1=daemon,,,switch1 eth2=daemon,,,switch2 eth3=daemon,,,switch7 eth4=daemon,,,switch14 mem=64M &
xterm –T PASURUAN –e linux ubd0=PASURUAN,jarkom umid=PASURUAN eth0=daemon,,,switch2 eth1=daemon,,,switch3 eth2=daemon,,,switch5 mem=64M &
xterm –T PROBOLINGGO –e linux ubd0=PROBOLINGGO,jarkom umid=PROBOLINGGO eth0=daemon,,,switch3 eth1=daemon,,,switch4 eth2=daemon,,,switch6 mem=64M &
xterm –T BATU –e linux ubd0=BATU,jarkom umid=BATU eth0=daemon,,,switch7 eth1=daemon,,,switch10 eth2=daemon,,,switch8 eth3=daemon,,,switch11 mem=64M &
xterm –T MADIUN –e linux ubd0=MADIUN,jarkom umid=MADIUN eth0=daemon,,,switch8 eth1=daemon,,,switch9 mem=64M &
xterm –T KEDIRI –e linux ubd0=KEDIRI,jarkom umid=KEDIRI eth0=daemon,,,switch11 eth1=daemon,,,switch15 eth2=daemon,,,switch12 mem=64M &
xterm –T BLITAR –e linux ubd0=BLITAR,jarkom umid=BLITAR eth0=daemon,,,switch12 eth1=daemon,,,switch13 mem=64M &

# Server
xterm -T MOJOKERTO -e linux ubd0=MOJOKERTO,jarkom umid=MOJOKERTO eth0=daemon,,,switch14 mem=64M &
xterm -T MALANG -e linux ubd0=MALANG,jarkom umid=MALANG eth0=daemon,,,switch15 mem=64M &

# Client
xterm -T SAMPANG -e linux ubd0=SAMPANG,jarkom umid=SAMPANG eth0=daemon,,,switch1 mem=64M &
xterm -T SIDOARJO -e linux ubd0=SIDOARJO,jarkom umid=SIDOARJO eth0=daemon,,,switch5 mem=64M &
xterm -T BANYUWANGI -e linux ubd0=BANYUWANGI,jarkom umid=BANYUWANGI eth0=daemon,,,switch6 mem=64M &
xterm -T JEMBER -e linux ubd0=JEMBER,jarkom umid=JEMBER eth0=daemon,,,switch6 mem=64M &
xterm -T BONDOWOSO -e linux ubd0=BONDOWOSO,jarkom umid=BONDOWOSO eth0=daemon,,,switch4 mem=64M &
xterm -T JOMBANG -e linux ubd0=JOMBANG,jarkom umid=JOMBANG eth0=daemon,,,switch8 mem=64M &
xterm -T BOJONEGORO -e linux ubd0=BOJONEGORO,jarkom umid=BOJONEGORO eth0=daemon,,,switch9 mem=64M &
xterm -T NGANJUK -e linux ubd0=NGANJUK,jarkom umid=NGANJUK eth0=daemon,,,switch10 mem=64M &
xterm -T TULUNGAGUNG -e linux ubd0=TULUNGAGUNG,jarkom umid=TULUNGAGUNG eth0=daemon,,,switch13 mem=64M &
xterm -T LUMAJANG -e linux ubd0=LUMAJANG,jarkom umid=LUMAJANG eth0=daemon,,,switch12 mem=64M &
```

NB : Untuk UML terlalu susah, jadi sampai disini saja :)
