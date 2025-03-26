## Monad Score auto Run Node 🌌
Script ini digunakan untuk mengotomatiskan pembaruan startTime node di Monad Score setiap 11 jam 15 menit menggunakan wallet dari wallets.json

![photo_2025-03-26_19-37-17](https://github.com/user-attachments/assets/01062714-3a12-42a7-ab0c-d275565f69ab)

## 📌 Fitur
- ✅ Auto update startTime untuk semua wallet di wallets.json ke endpoint Monad Score
- 🔌 Dukungan proxy (proxy.txt) dengan switching otomatis jika gagal (http/socks5)
- ⚡ Rerun otomatis setiap 11 jam 15 menit tanpa intervensi manual
- 🎁 Menampilkan status sukses/gagal untuk setiap wallet
- 🎮 Prompt interaktif untuk penggunaan proxy (y/n) saat pertama kali dijalankan
- 💾 Membaca data autentikasi dari wallets.json (address, privateKey)


## 🚀 Cara Penggunaan

1. **Clone repository ini**
```
git clone https://github.com/marioatmajanugraha/monadScore-Bot.git
cd monadScore-Bot
```

2. **Install Dependencies**
```
npm install axios chalk@4 cfonts http-proxy-agent socks-proxy-agent ethers
```

3. **Siapkan file wallets**
Pastikan file wallets.json sudah ada dan berisi data wallet. Contoh:
```
[
    {
        "address": "0x4d346Eb73EFEE343f76aF0C2449a895b5....",
        "privateKey": "0x..."
    }
]
```

4. **(Opsional) Buat proxy.txt** jika ingin menggunakan proxy. Contoh:
```
http://username:password@host:port
socks5://username:password@host:port
```

5. **Jalankan Script**
```
node node.obf.js
```

6. **Ikuti Instruksi**
Pilih apakah ingin menggunakan proxy (y/n)

Script akan berjalan otomatis dan mengulang setiap 11 jam 15 menit

## ⚠️ Disclaimer
Gunakan script ini dengan bijak dan sesuai aturan Monad Score.

Developer tidak bertanggung jawab atas penyalahgunaan atau konsekuensi lainnya.

Simpan wallets.json dengan aman dan jangan bagikan private key Anda!

## 🤝 Kontribusi
Jika ingin berkontribusi, silakan fork repo ini dan ajukan pull request! Kami terbuka untuk ide baru dan perbaikan.

## 📞 Kontak
Jika ada pertanyaan, hubungi: [@balveerxyz](https://t.me/balveerxyz)

Join channel Telegram gratis: [Airdrop 888](https://t.me/airdroplocked)
