🤖 Hytryx Userbot Telegram

<p align="center">
  <b>Hytryx Userbot</b><br>
  Telegram Userbot multifungsi berbasis Python & Telethon
</p><p align="center">
  <a href="https://github.com/elllmarley017-pixel/hytrix-userbot-telegram">
    <img src="https://img.shields.io/badge/Hytryx-Userbot-blue?style=for-the-badge&logo=telegram" alt="Hytryx Userbot">
  </a>
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Telethon-Telegram-blue?style=for-the-badge" alt="Telethon">
  <img src="https://img.shields.io/badge/Version-1.0.0-green?style=for-the-badge" alt="Version">
</p>---

📖 Tentang

Hytryx Userbot Telegram adalah Telegram userbot berbasis Python dan Telethon yang dirancang sebagai toolkit multifungsi untuk membantu berbagai aktivitas di Telegram.

Userbot ini memiliki beberapa kategori fitur:

- 🤖 AI Assistant
- 📥 Media Downloader
- 🔎 Search & Checker
- 🕵️ Public Profile Lookup
- 🛠️ Media Converter
- 🖼️ Sticker Tools
- 📊 Bot Information
- 📜 Telegram History Export
- 🐙 GitHub Tools
- 🎵 Spotify Tools
- 🎬 TikTok Tools
- ▶️ YouTube Tools

Project menggunakan sistem handler modular, sehingga setiap kategori fitur dipisahkan ke dalam file Python tersendiri agar lebih mudah dikembangkan dan dirawat.

---

✨ Fitur Utama

🤖 AI

Gunakan AI langsung dari Telegram untuk berbagai kebutuhan seperti:

- Chat
- Tanya jawab
- Coding assistance
- Debugging
- Penjelasan kode
- Bantuan teknis

.ai <pertanyaan>

Contoh:

.ai jelaskan cara kerja async await Python

---

📥 Downloader

▶️ YouTube

🔎 YouTube Search

.ytsearch <query>

Contoh:

.ytsearch lagu indonesia terbaru

🎬 YouTube MP4

.ytmp4 <link>

Contoh:

.ytmp4 https://youtube.com/watch?v=xxxxx

🎵 YouTube MP3

.ytmp3 <link>

Contoh:

.ytmp3 https://youtube.com/watch?v=xxxxx

---

📘 Facebook Downloader

.fb <link>

Contoh:

.fb https://facebook.com/xxxxx

Digunakan untuk memproses video Facebook yang dapat diakses oleh downloader.

---

🎧 Spotify

.spotify <link>

Contoh:

.spotify https://open.spotify.com/track/xxxxx

---

🎬 Videy

.videy <link>

Contoh:

.videy https://videy.co/xxxxx

---

📌 Pinterest

.pin <link>

Contoh:

.pin https://pinterest.com/pin/xxxxx

Digunakan untuk mengambil media dari Pinterest.

---

🎵 TikTok Video

.tt <link>

Contoh:

.tt https://www.tiktok.com/@user/video/xxxxx

---

📷 TikTok Photo / Slide

.ttpic <link>

Contoh:

.ttpic https://www.tiktok.com/@user/photo/xxxxx

---

📁 MediaFire

.mediafire <link>

Contoh:

.mediafire https://www.mediafire.com/file/xxxxx

---

🐙 GitHub Downloader

.github <link>

Contoh:

.github https://github.com/user/repository

Digunakan untuk mengambil repository atau folder GitHub yang dapat diakses secara publik.

---

🔎 Search & Checker

🆔 Telegram ID

.id <username>

Contoh:

.id @username

Fitur ini melakukan resolusi username Telegram dan menampilkan informasi yang dapat diakses, termasuk:

- Nama
- Username
- Tipe entity
- Telegram ID

Username divalidasi sebelum dikirim ke Telegram API.

---

🔎 Telegram Search

.telesearch <text>

Contoh:

.telesearch hanz

Digunakan untuk mencari entity Telegram seperti:

- 👤 User
- 👥 Group
- 📢 Channel

---

📜 Get Chat

.getchat <id/username>

Contoh:

.getchat @username

atau:

.getchat 123456789

Fitur ini digunakan untuk mengekspor riwayat pesan yang dapat diakses oleh akun yang sedang menjalankan userbot.

«⚠️ Fitur tidak dimaksudkan untuk melewati privacy restriction atau mendapatkan pesan yang tidak dapat diakses secara normal.»

---

🎯 TikTok Search

.ttsearch <query> <account|vt>

Contoh:

.ttsearch hanz account

atau:

.ttsearch minecraft vt

---

🕵️ Public Profile Tools

Hytryx menyediakan beberapa tool untuk melakukan pengecekan informasi publik dari berbagai platform.

TikTok

.ttstalker <username>

GitHub

.githubstalker <username>

Roblox

.robloxstalker <username>

Instagram

.igstalker <username>

X / Twitter

.xstalker <username>

Facebook

.fbstalker <username>

Multi-platform

.extrastalker <username>

Fitur "extrastalker" digunakan untuk pengecekan keberadaan username pada berbagai platform publik.

«Privacy Notice: fitur-fitur ini hanya ditujukan untuk informasi yang memang tersedia secara publik. Jangan gunakan untuk doxxing, harassment, stalking terhadap individu, atau mengumpulkan data pribadi secara tidak sah.»

---

🛠️ Media Converter

🖼️ Sticker → PNG

Reply sebuah sticker statis kemudian:

.toimg

Contoh:

Reply sticker
→ .toimg

Sticker akan dikonversi menjadi PNG.

---

🎞️ Sticker / Video → GIF

Reply media yang didukung:

.togif

Contoh:

Reply sticker/video
→ .togif

Konversi menggunakan FFmpeg dengan pembatasan durasi dan resolusi untuk menjaga penggunaan resource.

---

🎵 Video / Audio → MP3

Reply video, audio, atau voice:

.tomp3

Contoh:

Reply video
→ .tomp3

Output audio dikonversi menjadi MP3.

---

🎙️ Audio / Video → Voice Note

.tovn

Contoh:

Reply audio/video
→ .tovn

Output dikonversi menjadi format voice note yang sesuai.

---

▣ Text → QR Code

.toqr <text>

Contoh:

.toqr https://example.com

Bot akan membuat QR Code berdasarkan teks atau URL yang diberikan.

---

🖼️ Sticker Tools

Membuat Sticker

Reply gambar/media yang sesuai kemudian:

.stiker

atau:

.s

Sticker akan ditambahkan ke sticker pack:

tenzu_stick

---

ℹ️ Bot Information

Gunakan:

.infobot

Informasi yang ditampilkan meliputi:

- 🤖 Bot Name
- 🔢 Version
- 🟢 Status
- ⏱️ Uptime
- 🐍 Programming Language
- 👤 Owner
- 🌐 Portfolio
- 📢 Channel
- 📦 Archive
- 🐙 GitHub

Versi bot dan uptime diambil secara runtime dari konfigurasi aplikasi.

---

📋 Daftar Command

Command| Fungsi
".start"| Menampilkan menu fitur
".ai <text>"| AI Chat & Coding Assistant
".infobot"| Informasi bot dan uptime
".ytsearch <query>"| Search YouTube
".ytmp4 <link>"| Download YouTube MP4
".ytmp3 <link>"| Download YouTube MP3
".fb <link>"| Facebook Downloader
".spotify <link>"| Spotify Downloader
".videy <link>"| Videy Downloader
".pin <link>"| Pinterest Downloader
".tt <link>"| TikTok Downloader
".ttpic <link>"| TikTok Photo/Slide Downloader
".mediafire <link>"| MediaFire Downloader
".github <link>"| GitHub Downloader
".id <username>"| Telegram ID Checker
".telesearch <text>"| Telegram Search
".getchat <id/username>"| Export accessible chat history
".ttsearch <query> <type>"| TikTok Search
".ttstalker <username>"| TikTok public profile
".githubstalker <username>"| GitHub public profile
".robloxstalker <username>"| Roblox public profile
".igstalker <username>"| Instagram public profile
".xstalker <username>"| X/Twitter public profile
".fbstalker <username>"| Facebook public profile
".extrastalker <username>"| Multi-platform public lookup
".stiker"| Add media to sticker pack
".s"| Shortcut sticker command
".toimg"| Sticker → PNG
".togif"| Media → GIF
".tomp3"| Media → MP3
".toqr <text>"| Text → QR Code
".tovn"| Media → Voice Note

---

🏗️ Struktur Project

hytrix-userbot-telegram/
│
├── handlers/
│   ├── __init__.py
│   │
│   ├── ai.py
│   ├── converter.py
│   ├── facebook.py
│   ├── getchat.py
│   ├── github.py
│   ├── infobot.py
│   ├── mediafire.py
│   ├── pinterest.py
│   ├── social_stalker.py
│   ├── spotify.py
│   ├── start.py
│   ├── sticker.py
│   ├── telegram_tools.py
│   ├── tiktok.py
│   ├── tiktok_search.py
│   ├── ttpic.py
│   ├── videy.py
│   └── youtube.py
│
├── logs/
│   └── activity.log
│
├── utils/
│   ├── ...
│   └── ...
│
├── temp/
│   └── ...
│
├── session/
│   ├── config.json
│   └── userbot.session
│
├── config.py
├── main.py
├── requirements.txt
└── README.md

Struktur handler memang dipisahkan berdasarkan fungsi, sedangkan "main.py" bertugas menginisialisasi client dan mendaftarkan seluruh handler.

---

⚙️ Persyaratan

Sebelum menjalankan project, siapkan:

- Python 3.x
- pip
- Telegram Account
- Telegram API ID
- Telegram API Hash
- FFmpeg
- koneksi internet

Untuk mendapatkan:

API ID
API HASH

gunakan Telegram API development tools:

https://my.telegram.org

---

🚀 Installation

1. Clone Repository

git clone https://github.com/elllmarley017-pixel/hytrix-userbot-telegram.git

Masuk ke directory:

cd hytrix-userbot-telegram

---

2. Install Dependency

pip install -r requirements.txt

Jika menggunakan Linux/Termux dan "pip" mengarah ke versi Python yang berbeda:

python3 -m pip install -r requirements.txt

---

📱 Instalasi di Termux

Hytryx dapat dijalankan pada environment seperti Termux selama dependency yang dibutuhkan tersedia.

Update package:

pkg update && pkg upgrade

Install Python:

pkg install python

Install Git:

pkg install git

Install FFmpeg:

pkg install ffmpeg

Clone repository:

git clone https://github.com/elllmarley017-pixel/hytrix-userbot-telegram.git
cd hytrix-userbot-telegram

Install Python dependencies:

pip install -r requirements.txt

Kemudian jalankan:

python main.py

---

🔐 First Login

Saat pertama kali dijalankan, userbot akan melakukan setup login secara interaktif.

==================================================
 Telegram Userbot - Setup Login
==================================================

Dapatkan API ID & API Hash dari https://my.telegram.org

Masukkan API ID:
Masukkan API Hash:

Setelah itu Telegram akan meminta proses autentikasi akun.

Proses login dapat mencakup:

1. Nomor Telegram
2. OTP Telegram
3. Password Two-Step Verification jika aktif

"main.py" menggunakan "TelegramClient" dan menyimpan konfigurasi API pada directory "session/".

---

▶️ Menjalankan Userbot

Setelah konfigurasi selesai:

python main.py

Jika login berhasil, terminal akan menampilkan informasi akun dan:

🤖 Userbot aktif!

Kemudian buka Telegram dan jalankan:

.start

untuk melihat seluruh menu fitur.

---

🔄 Menjalankan di Background

Untuk server Linux/VPS, kamu dapat menggunakan:

nohup python3 main.py > userbot.log 2>&1 &

Untuk memeriksa proses:

ps aux | grep main.py

Untuk menghentikan proses:

pkill -f "python3 main.py"

Alternatif lain yang lebih cocok untuk deployment jangka panjang adalah menggunakan process manager seperti "systemd", "tmux", atau "screen".

---

📊 Logging

Project memiliki sistem activity logging.

Directory:

logs/

File utama:

logs/activity.log

Logging digunakan untuk membantu mengetahui aktivitas command dan proses error.

Struktur konfigurasi juga menyediakan:

BOT_TIMEZONE
BOT_VERSION

dengan timezone default:

Asia/Jakarta

dan versi default:

1.0.0

---

🧹 Temporary Files

File sementara digunakan selama proses:

- Download
- Conversion
- Processing media
- Generate QR
- Dan proses lainnya

Directory:

temp/

Project menggunakan mekanisme cleanup untuk menghapus file temporary setelah proses selesai.

Contohnya pada converter, file source dan hasil conversion dibersihkan setelah proses selesai.

---

🛡️ Security

Jangan Upload Credential

Jangan pernah mengunggah:

session/

atau credential Telegram ke repository publik.

Secara khusus, jangan membagikan:

session/*.session
session/config.json

Session file dapat memberikan akses ke akun Telegram.

---

Gunakan ".gitignore"

Disarankan menggunakan:

__pycache__/
*.pyc

session/
temp/
logs/

*.session

.env

Jika "config.json" berisi credential:

session/config.json

---

⚠️ Disclaimer

Hytryx Userbot menggunakan akun Telegram pengguna melalui Telegram API.

Penggunaan userbot sepenuhnya menjadi tanggung jawab pengguna.

Jangan gunakan project ini untuk:

- Spam
- Flooding
- Harassment
- Phishing
- Doxxing
- Pengumpulan data pribadi tanpa izin
- Penyalahgunaan akun
- Aktivitas ilegal
- Menghindari sistem keamanan/privacy Telegram
- Melanggar Terms of Service platform yang digunakan

Gunakan fitur downloader dan public-profile tools hanya pada konten dan informasi yang memang boleh kamu akses atau gunakan.

Developer tidak bertanggung jawab atas:

- Account restriction
- Account ban
- Kehilangan session
- Penyalahgunaan credential
- Pelanggaran Terms of Service
- Kerugian akibat penggunaan project

---

🐛 Troubleshooting

"ModuleNotFoundError"

Jalankan:

pip install -r requirements.txt

---

FFmpeg Tidak Ditemukan

Cek:

ffmpeg -version

Jika belum tersedia pada Termux:

pkg install ffmpeg

Pada Debian/Ubuntu:

sudo apt update
sudo apt install ffmpeg

---

Telegram API Error

Pastikan:

API_ID
API_HASH

benar.

Credential Telegram API dapat diperoleh melalui:

https://my.telegram.org

---

Session Bermasalah

Hentikan userbot:

Ctrl+C

Kemudian backup atau hapus session jika memang diperlukan:

rm -f session/userbot.session

Lalu jalankan kembali:

python main.py

«Jangan menghapus session secara sembarangan jika akun sedang digunakan oleh instance lain.»

---

Download Gagal

Downloader bergantung pada layanan/API eksternal serta ketersediaan URL.

Periksa:

ping google.com

dan coba command dengan URL publik yang valid.

---

🧩 Arsitektur

Hytryx menggunakan pola modular:

                ┌───────────────┐
                │    main.py    │
                └───────┬───────┘
                        │
                ┌───────▼───────┐
                │   Telethon    │
                │ TelegramClient │
                └───────┬───────┘
                        │
        ┌───────────────┼────────────────┐
        │               │                │
        ▼               ▼                ▼
   Downloader         AI             Converter
        │               │                │
        ▼               ▼                ▼
   YouTube          AI API          FFmpeg/QR
   TikTok
   Spotify
   Facebook
   Videy
   Pinterest
   MediaFire
   GitHub

                        │
                        ▼
                ┌───────────────┐
                │ Utils / Logs  │
                └───────────────┘

"main.py" mendaftarkan handler seperti:

start.register(client)
youtube.register(client)
facebook.register(client)
spotify.register(client)
ai.register(client)
videy.register(client)
pinterest.register(client)
tiktok.register(client)
ttpic.register(client)
mediafire.register(client)
github.register(client)
telegram_tools.register(client)
tiktok_search.register(client)
getchat.register(client)
social_stalker.register(client)
sticker.register(client)
converter.register(client)
infobot.register(client)

---

🔧 Development

Untuk menambahkan fitur baru:

1. Buat handler

Contoh:

handlers/example.py

2. Buat fungsi register

from telethon import events

def register(client):

    @client.on(
        events.NewMessage(
            pattern=r"^\.example$",
            outgoing=True
        )
    )
    async def example_handler(event):
        await event.edit("Hello from Hytryx!")

3. Import pada "main.py"

from handlers import example

4. Register handler

example.register(client)

5. Restart userbot

python main.py

---

📝 Menambahkan Command ke ".start"

Jika membuat command baru, tambahkan juga informasinya ke:

handlers/start.py

Contoh:

• ⚡ .example — Example command

Dengan demikian pengguna dapat melihat command baru melalui:

.start

---

📦 Dependency

Dependency project dikelola melalui:

requirements.txt

Install semuanya dengan:

pip install -r requirements.txt

Beberapa fitur juga menggunakan binary/system dependency seperti:

FFmpeg

untuk pemrosesan media.

---

🌐 Repository

Source code:

https://github.com/elllmarley017-pixel/hytrix-userbot-telegram

---

👤 Owner

HanzTenzX

Telegram:

https://t.me/HanzTenzX

Portfolio:

https://hanzx-portofolio.vercel.app/

Channel:

https://t.me/TenzXrepro

Archive:

https://t.me/despiselonelyy

---

❤️ Support

Jika project ini bermanfaat:

- ⭐ Star repository
- 🍴 Fork repository
- 🐛 Laporkan bug melalui Issues
- 💡 Ajukan feature request
- 🔧 Contribute melalui Pull Request

---

📜 Version

Current version:

v1.0.0

Project repository saat ini ditandai sebagai v1.0.

---

<p align="center">
  <b>Hytryx Userbot</b><br>
  Built with Python ❤️ & Telethon
</p><p align="center">
  © 2026 Hytryx Userbot
</p>
