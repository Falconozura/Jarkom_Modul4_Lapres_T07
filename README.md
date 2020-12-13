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
  - Router
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Router.jpg?raw=true)<br /><br />
  - Client
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Client.jpg?raw=true)<br /><br />
  - Server
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Mojokerto.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Malang.png?raw=true)<br /><br />
  
## Routing
  Melakukan routing pada setiap interface router menuju subnet yang belum dikenal
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Surabaya.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Pasuruan.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Probolinggo.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Batu.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Madiun.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Kediri.png?raw=true)<br /><br />
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Blitar.png?raw=true)<br /><br />
  
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
      <td>A10 dengan A11</td>
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
    <tr>
      <td>A13</td>
      <td>101</td>
      <td>/25</td>
    </tr>
  </table>
  
  Menghitung pembagian IP berdasarkan NID dan Netmask
  ![img](https://github.com/Falconozura/JARKOM_Modul4_Lapres_T07/blob/main/img/Topologi%20CIDR.png?raw=true)<br /><br />
  
