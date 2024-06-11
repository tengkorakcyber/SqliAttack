<h1 align="center">
  <img src="images/sqlifinder-logo.png" alt="sqlifinder" width="200px"></a>
  <br>
</h1>

<h4 align="center">Pengimbas SQL Injection dibuat dengan python.</h4>


      
<p align="center">
  <a href="#ciri-ciri">Features</a> •
  <a href="#Penggunaan">Install</a> •
  <a href="#Menjalankan Serangan Sqli Attack">Usage</a> •
</p>

---


Sqli Attack ialah alat dengan fungsi mengesan kelemahan suntikan sql berasaskan GET dalam aplikasi web menggunakan waybackurls, perangkak web dan muatan suntikan sql.


# ciri-ciri

<h1 align="left">
  <img src="static/sqlifinder-run.png" alt="sqlifinder" width="700px"></a>
  <br>
</h1>


 - Pengimbas yang pantas dan berkuasa
 - Bersertakan perangkak web dan waybackurls


# Penggunaan

```sh
python3 sqli-attack.py -h
```
Ini akan memaparkan bantuan untuk alat tersebut. Berikut adalah semua suis yang disokongnya.



# Pemasangan

Sqli Attack memerlukan:
- python3
- huepy
- requests
- tqdm

Untuk memasang jalankan arahan ini:
```sh
▶ sudo apt install git
```
```sh
▶ git clone https://github.com/tengkorakcyber/sqliattack
```
```sh
▶ cd sqli-attack
▶ pip3 install -r requirements.txt
```





# Menjalankan Serangan Sqli Attack

Untuk menjalankan alat pada sasaran, hanya gunakan arahan berikut.
```sh
▶ python3 sqli-attack.py -d example.com
```


Perintah `-s` boleh digunakan untuk menguji suntikan sql dalam subdomain sasaran.

```sh
▶ python3 sqli-attack -d example.com -s
```



# License

Sqli Attack is Recode By [TengkorakCyberCrew](https://tengkorakcyber.org).

