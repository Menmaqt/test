# Pesan dariku (WAJIB BACA) terlebih dahulu sebelum memakai

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>

<p align="center"><img src="https://img.shields.io/badge/Service-SSH_Over_Websocket-success.svg">  <img src="https://img.shields.io/badge/Service-SSH_Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel4-success.svg">  <img src="https://img.shields.io/badge/Service-Fail2Ban-brightgreen">  <p align="center"><img src="https://img.shields.io/badge/Service-XRAY-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_Websocket_TLS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_VLESS_VMESS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_gRPC_VLESS_VMESS-success.svg">  <img src="https://img.shields.io/badge/Service-XRAY_TROJAN-success.svg">  <img src= "https://img.shields.io/badge/Service-Shadowsocks-success.svg">  <img src="https://wangchujiang.com/sb/status/stable.svg">
  
# Diperlukan
# VPS masih fresh (WAJIB) / belum pernah install apapun
<br>
- DOMAIN (WAJIB) / RANDOM dari Script<br>
- NOTE domain dari script hanya dilakukan 1x saat proses install untuk mengurangi spam DOMAIN yang sering bergonta-ganti<br>
- Untuk mengubah Domain di menu setelah install menggunakan domain sendiri bukan dari script lagi OK<br>
- DEBIAN 9/10<br>
- Ubuntu 18/20 LTS<br>
- CPU MIN 1 CORE<br>
- RAM 1GB<br>
- Rekomendasi Ubuntu 18 
<br>

# Setting Cloudflare bagi yang punya Domain sendiri, kamu bisa cek di folder [image](https://github.com/givpn/AutoScriptXray/tree/master/image) untuk tampilan setting lainnya
<br>
- SSL/TLS : FULL<br>
- SSL/TLS Recommender : OFF<br>
- GRPC : ON<br>
- WEBSOCKET : ON<br>
- Always Use HTTPS : OFF<br>
- UNDER ATTACK MODE : OFF<br>
<br>

# Pointing
![Pointing](https://raw.githubusercontent.com/Menmaqt/v4/main/image/pointing.png)
  
## Fitur
- Speedtest VPS by [Ookla](https://speedtest.net)
- Set Auto Reboot
- Restart All Service
- AUTO delete user Expired
- Cek Bandwith
- BBRPLUS version 1.4.0 by [Chikage0o0](https://github.com/Chikage0o0/Linux-NetSpeed)
- DNS CHANGER
- Optional [install Panel ADS Block](https://github.com/Menmaqt/v4/tree/main/helium) Helium version 3.0 by [Abi Darwish](https://github.com/abidarwish/helium)
- DLL
- auto backup tidak ada ? ya... dihilangkan permanent
- Terima saja fitur yang ada / kamu bisa tambahkan sendiri secara manual [CARANYA](https://github.com/Menmaqt/v4/tree/main/cara)

# Step INSTALL, NOTE jika sudah root langsung COPAS link dibawah ini saja ya
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Menmaqt/v4/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

# Telegram
[![Telegram-chat](https://img.shields.io/badge/Chat-Telegram-blue)](https://t.me/ZxMenma/)

# PESAN AKHIR
- TERIMAKASIH SUDAH MELUANGKAN WAKTU UNTUK MEMBACA DAN MAAF BILA ADA KATA-KATA YANG TIDAK SEMPURNA
- KARENA SAYA JUGA MANUSIA YANG TIDAK LUPUT DARI KESALAHAN