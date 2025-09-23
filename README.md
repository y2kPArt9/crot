# CroT...

Ini adalah [Marzban](https://github.com/Gozargah/Marzban) yang sudah saya tambahkan nginx untuk konfigurasi koneksi WebSocket dan XHTTP pada single port. </br>
WebSocket sudah support untuk 443 TLS, 80 HTTP dan Wildcard path, contoh /enter-your-custom-path/trojan </br>
XHTTP sudah support untuk 443 TLS Quic </br>

Disclaimer: Proyek ini hanya untuk pembelajaran dan komunikasi pribadi, mohon jangan menggunakannya untuk tujuan ilegal. </br>
Credit aplikasi full to [Gozargah Marzban](https://github.com/Gozargah), saya hanya edit sedikit untuk instalasi sederhana bagi pemula . </br>

# Special Thanks to
- Tuhan YME Pemilik Bumi,Makhluk dan Semestanya
- [Gozargah](https://github.com/Gozargah/crotzban)
- [hamid-gh98](https://github.com/hamid-gh98)
- [x0sina](https://github.com/x0sina/crotzban-sub)
- Ilham Wahyudi aka bogel11 (https://www.facebook.com/ilham21012023) Donatur Utama
- [AIXXYCODE.ID] ntah sapa nama aslinya

# List Protocol yang support
- VLess
- VMess
- Trojan

# Yang harus dipersiapkan
- VPS dengan minimal spek 1 Core 1 GB ram kalau bisa beli VPS di tempat lain selain dewaweb
- Domain yang sudah di pointing ke CloudFlare
- Pemahaman dasar perintah Linux

# Sistem VM yang dapat digunakan
- Debian 11 </br>
- Debian 12 [**RECOMMENDED**] </br>
- Ubuntu 20.04 </br>

# Instalasi
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
Pastikan anda sudah login sebagai root sebelum menjalankan perintah dibawah
 ```html
 wget https://raw.githubusercontent.com/y2kPArt9/CroT/main/crot.sh && chmod +x crot.sh && ./crot.sh
 ```

Buka panel Marzban dengan mengunjungi https://domainmu/dashboard <br>

Jika ingin mengubah konfigurasi env variable 
```html
marzban edit-env
 ```
Perintah Restart service Marzban 
```html
marzban restart
 ```
Perintah Cek Logs service Marzban 
```html
marzban logs
 ```
Perintah ganti Core Xray marzban
```html
marzban core-update
 ```
Perintah untuk sett backup marzban
```html
 marzban backup-service
 ```
Perintah Cek update service Marzban
```html
marzban update
 ```
Perintah untuk ke Menu Warp
```html
warp
 ```
atau selebih nya bisa cek 
```html
warp --help
 ```

# Cloudflare Sett

Pastikan SSL/TLS Setting pada cloudflare sudah di set menjadi full
<img width="1312" height="797" alt="1" src="https://github.com/user-attachments/assets/0d77c212-454f-47b4-a5e1-024ab34c5417" />

Lalu pada tab **Network** pastikan gRPC dan WebSocket sudah ON 
<img width="1156" height="715" alt="2" src="https://github.com/user-attachments/assets/92791f72-2483-4e9b-a5a3-9457e10da5b3" />

# Setting Host Marzban
 
 Saat masuk ke panel, setting host di menu kanan atas <br>
<img width="568" height="297" alt="3" src="https://github.com/user-attachments/assets/989eac26-5b3f-4f0f-bd8e-b01675f53d6d" />

Lalu ubah variabel {SERVER_IP} dibawah menjadi domain yang sudah di pointing tadi <br>
# CONTOH
<img width="393" height="412" alt="4" src="https://github.com/user-attachments/assets/3f36afdd-68d3-4845-9305-eb2e8ff3a643" />

Jika ada typo atau saran bisa PM ke saya di :<a href="https://t.me/EkoLing" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>
Jika anda berminat bisa join ke Telegram channel saya di :<a href="https://t.me/LingVPN" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>

