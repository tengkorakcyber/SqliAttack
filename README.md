<h1 align="center">
  <img src="images/sqliattack-logo.png" alt="Sqli Attack" width="200px"></a>
  </h1>
<div align="center">
<h1><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7E94C&center=true&vCenter=true&width=435&lines=Sqli+Attack; Created+By+Jaring" alt="Typing SVG" /></a></h1>
</div>
<h1>
   <img src="https://img.shields.io/badge/language-python-blue.svg"><p>
   <img src="https://img.shields.io/badge/python-3-blue.svg">
   <img src="https://img.shields.io/badge/Status-Beta-blue"> 
   <img src="https://img.shields.io/badge/telegram-https://t.me/tengkorakcybercrewz-yellow.svg">
   <img src="https://img.shields.io/badge/website-https://tengkorakcyber.org-yellow.svg">
</h1>

<h4 align="center">Pengimbas SQL Injection dibuat dengan python.</h4>

<p align="center">
  <a href="#Pengenalan">About</a> •
  <a href="#Screenshot">Screenshot</a> •
  <a href="#Penggunaan">Install</a> •
  <a href="#Cara-guna">Usage</a> •
  <a href="http://tengkorakcyber.org/dork.txt">Dork</a> 
</p>

---


Sqli Attack ialah alat dengan fungsi mengesan kelemahan suntikan sql berasaskan GET dalam aplikasi web menggunakan waybackurls, perangkak web dan muatan suntikan sql.

# Pengenalan
Secara amnya, penggodam menggunakan arahan atau pertanyaan SQL dengan alat tertentu untuk mengakses pangkalan data. Suntikan kod yang dijalankan membolehkan mereka masuk tanpa proses pengesahan. Setelah berjaya, penggodam bebas untuk menambah, memadam dan menukar data di tapak web.

# Screenshot

<h1 align="left">
  <img src="static/sqlifinder-run.png" alt="Sqli Attack" width="700px"></a>
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
▶ git clone https://github.com/tengkorakcyber/SqliAttack.git
```
```sh
▶ cd sqli-attack
▶ pip3 install -r requirements.txt
```





# Cara-guna

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

