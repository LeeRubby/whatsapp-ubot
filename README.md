<div align="center">
  <img src="https://i.hizliresim.com/6Bbj7i.jpg" width="200" height="200">
  <h1>🐺 WhatsAsena</h1>
  <h3>Remod by @elzeXD</h3>
</div>
<p align="center">
    WhatsAsena project - Makes it easy and fun to use Whatsapp. Also first userbot for Whatsapp.
    <br>
        <a href="https://t.me/elzeXD"> My Telegram</a> |
        <a href="https://elzeXD.github.io">My Website</a> |
        <a href="https://t.me/WHATSASENA">Telegram Channel</a> |
        <a href="https://t.me/AsenaSupport">Telegram Group</a> |
    <br>
</p>

----
![Docker Pulls](https://img.shields.io/docker/pulls/fusuf/whatsasena?style=flat-square) ![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/fusuf/whatsasena?style=flat-square)

**WhatsAsena,** adalah userbot untuk WhatsApp yang ditulis menggunakan API WhatsApp Web.

### ⚠️ Warning! 
```
Akun Anda mungkin akan di-banned.
Saya tidak bertanggung jawab untuk penggunaan bot yang tidak sewajarnya.
Bot ini dibuat hanya untuk senang-senang semata,
dan juga untuk memudahkan dalam mengurus grup.
Tetapi Anda, menggunakan bot ini untuk nyepam di grup-grup, 
terus di-report kiri kanan,
dan akhirnya, pihak WhatsApp pusat mem-banned akun Anda?
Dan setelah itu, Anda menyalahkan kami
setelah mendapati bahwa akun Anda di-banned?
Aduh, bengek hyung 😭
```

## 📢 Cara Instal
### A. String Session

**WAJIB 2 HAPE!**
1. Buka Termux di HP pembantu, ketik ini berurutan, tunggu selesai command yang satu baru lanjut yang lain<br>
  ```apt update
  apt install nodejs --fix-missing
  pkg install git
  git clone https://github.com/Quiec/WhatsAsena
  cd WhatsAsena
  npm install @adiwajshing/baileys
  npm install chalk
  node qr.js
  ```
  Atau cara cepat ketik: 
  ```bash <(curl -L https://t.ly/qYqy)```

  Atau mau lebih cepat lagi, tanpa Terminal? Klik tombol di bawah ini, lalu klik Run.

  [![Run on Repl.it](https://repl.it/badge/github/Quiec/whatsasena)](https://repl.it/@Quiec/whatsasena)

2. **HARUS CEPAT!!!**<br>
Balik ke HP yang WAnya mau dipasang bot, buka **Titik 3 -> Pengaturan -> WhatsApp Web**, lalu scan QR code yang di Termux.<br>
  ***Kenapa harus cepat?***<br>
  ***Soalnya nanti kodenya ganti-ganti cepet banget. Kalo lebih dari 5 menit bisa error. Bila perlu, dari awal HP udah harus siap di menu WA Web.***
3. Setelah scan, nanti ada kode di Termux. Nah copy itu kode, mulai dari `ASENA ;;;` sampai kodenya habis di tanda `= (sama dengan)`. Simpan di notes bila perlu.


### B. Install Bot
1. Klik tombol dibawah ini:

    [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/elzeXD/WhatsAsena-mod)

2. ***Kalo gapunya akun heroku, buat dulu.***<br>
***Kalo udah punya, saya rekomendasikan buat akun baru karena ini rakus makan dyno, dan lu pada juga bakal sering make, kecuali kalo dyno-mu sakti yang bisa 1000 jam atau lebih***
3. Isi `ASENA_SESSIONS` dengan kode dari Termux tadi
4. Kalo mau bahasa Indonesia, di `LANGUAGE` isi `ID`
5. Sisanya isi sesuai hati nurani.
6. Tunggu prosesnya selesai, setelah itu klik **Manage App**, lalu klik **Resources**, nyalain dyno, dan silahkan tonton log.<br>
Kalo berhasil, selamat anda punya bot! Coba tes `.alive` kalo mau tau hidup apa nggaknya.

## F.A.Q
Beberapa pertanyaan yang sering diajukan:
### Ini aman kan? Lo pada bisa baca pesan gw trus mata2in gw kan, ngaku lo!
Ini open source, semua orang bisa analisis kodenya, tidak ada kode untuk mata-matain orang.<br>
**Kani tidak bisa mengakses akun anda, btw sori nih bos, lagian lo siape? Orang penting ae bukan.**

### Serius? Tapi kata temenku, kalo ada notifikasi WhatsApp Web itu tandanya WA gw disadap/dibobol?
Kalo lu pada masih menganut itu, yaudah gausah instal, yaelah ribet amat.<br>
Misal kamu ngerasa WAmu beneran disadap, buka **Whatsapp > Titik 3 > Whatsapp Web**, nah kan ada daftar komputer tuh, keluarin aja semua, tapi yang ada tulisan Baileys jangan, karena itu botnya.<br>
*Tapi kalo udah terlanjur, yaudah balik lagi ke atas, nyari string session, trus atur lagi di Heroku.*

### Mantul banget ini, tapi bayar ga?
**Gak dan gak bakal.** Tapi kalo mau donasi langsung ke pembuatnya aja, bisa hubungi dia via [Telegram](https://t.me/fusuf).<br>
Kalau mau ke saya juga boleh, via [Saweria](https://saweria.co/elzeXD)

## Credit

[![Yusuf Usta](https://github.com/quiec.png?size=100)](https://quiec.tech) | [![Alperen Ç](https://github.com/xacnio.png?size=100)](https://github.com/xacnio) | [![Vincent S](https://github.com/elzeXD.png?size=100)](https://elzeXD.github.io)
---|---|---
[Yusuf Usta](https://t.me/fusuf) | [Alperen Ç](https://t.me/xacnio) | [Vincent S](https://t.me/elzeXD)
Base, Development, Idea, Modules |  Bug Fixes, Modules | Remodder, Re-translate

## Thanks To:

### Tuhan Yang Maha Esa

### 'Pelopor' Userbot 
- [RaphielGang](https://github.com/RaphielGang) - Telegram-Paperplane
- [MoveAngel](https://github.com/MoveAngel/One4uBot) - One4Ubot
- [Mr.Miss](https://github.com/keselekpermen69) - Userbutt
- [X-Newbie](https://github.com/X-Newbie/XBot-Remix) - X-BOT REMIX
- [Userge Team](https://github.com/UsergeTeam/Userge) - Userge

### Asena Dev
- [@adiwajshing](https://github.com/adiwajshing) for coded [Baileys](https://github.com/adiwajshing/Baileys) 
- [@itacirgabral](https://github.com/itacirgabral) for helps
- `Ikarus#7808 (Discord)` for helps
- Translators

### Dan lain-lain


## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark
