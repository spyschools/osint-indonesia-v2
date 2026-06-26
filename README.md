# Tools OSINT Indonesia V2

Cek Informasi dari NIK,NO HP
Script ini tidak akan ambil data dari database ilegal, tapi hanya dari sumber OSINT publik. 

Install dependensi:

$ sudo apt update && sudo apt install python3-pip

$ pip3 install --upgrade pip

$ pip3 install requests bs4 colorama

Jalankan
$ git clone https://github.com/spyschools/osint-indonesia-v2.git

$ cd osint-indonesia-v2

$ chmod +x osint_v2.py

$ python3 osint_v2.py 3275124308050003 +6281234567890

Hasil akan muncul di terminal dan tersimpan ke report.html.
gunakan tools ini dengan bijak, tools ini hanya untuk pengetesan dan pengembangan
