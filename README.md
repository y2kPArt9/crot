# crotLing

Ini adalah [crotzban](https://github.com/Gozargah/crotzban) yang sudah saya tambahkan nginx untuk konfigurasi koneksi WebSocket dan XHTTP pada single port. </br>
WebSocket sudah support untuk 443 TLS, 80 HTTP dan Wildcard path, contoh /enter-your-custom-path/trojan </br>
XHTTP sudah support untuk 443 TLS Quic </br>

Disclaimer: Proyek ini hanya untuk pembelajaran dan komunikasi pribadi, mohon jangan menggunakannya untuk tujuan ilegal. </br>
Credit aplikasi full to [Gozargah crotzban](https://github.com/Gozargah), saya hanya edit sedikit untuk instalasi sederhana bagi pemula . </br>

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
- VPS dengan minimal spek 1 Core 1 GB ram
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

Buka panel crotzban dengan mengunjungi https://domainmu/dashboard <br>

Jika ingin mengubah konfigurasi env variable 
```html
crotzban edit-env
 ```
Perintah Restart service crotzban 
```html
crotzban restart
 ```
Perintah Cek Logs service crotzban 
```html
crotzban logs
 ```
Perintah ganti Core Xray crotzban
```html
crotzban core-update
 ```
Perintah untuk sett backup crotzban
```html
 crotzban backup-service
 ```
Perintah Cek update service crotzban
```html
crotzban update
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
![image](https://github.com/y2kPArt9/CroT/assets/97426017/3aeedf09-308e-41b0-9640-50e4abb77aa0) </br>

Lalu pada tab **Network** pastikan gRPC dan WebSocket sudah ON 
![image](https://github.com/y2kPArt9/CroT/assets/97426017/65d9b413-fda4-478a-99a5-b33d8e5fec3d)



# Setting Host crotzban
 
 Saat masuk ke panel, setting host di menu kanan atas <br>
 ![image](https://github.com/y2kPArt9/CroT/assets/97426017/6b96bce7-39c7-4b5c-b01e-8dfdea91cb47) </br>

Lalu ubah variabel {SERVER_IP} dibawah menjadi domain yang sudah di pointing tadi <br>
# CONTOH
![image](https://github.com/y2kPArt9/CroT/assets/97426017/191a485c-07a7-4a28-88d3-b66fa403abc7)
</br>

Jika ada typo atau saran bisa PM ke saya di :<a href="https://t.me/EkoLing" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>
Jika anda berminat bisa join ke Telegram channel saya di :<a href="https://t.me/LingVPN" target=”_blank”><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a><br>
