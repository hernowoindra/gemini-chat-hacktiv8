# InnitChat powered by Gemini

InnitChat adalah aplikasi web chat sederhana yang memanfaatkan **Google Gemini API** untuk menjawab pertanyaan secara interaktif.  
Proyek ini dirancang dengan **Bootstrap 5** dan memiliki fitur **dark/light mode**, sidebar toggle, serta ikon yang intuitif.

---

## ✨ Fitur
- 💬 Chat interaktif menggunakan **Google Gemini API**.
- 🌓 **Toggle Dark/Light Mode** untuk pengalaman penggunaan yang fleksibel.
- 📑 Sidebar yang dapat **ditampilkan atau disembunyikan** dengan tombol ☰.
- 🎨 UI rapi dengan **Bootstrap 5** + Bootstrap Icons.
- 📱 Responsif dan dapat diakses dari berbagai perangkat.

---

## 📂 Struktur Folder
project-root/
│
├── index.html # Halaman utama aplikasi
├── style.css # Styling tambahan
├── script.js # Logika JavaScript (chat, toggle, dsb.)
├── .env # Konfigurasi API Key
└── README.md # Dokumentasi proyek


---

## ⚙️ Konfigurasi `.env`

Buat file `.env` di root project, lalu isi dengan:
```env
# API Key dari Google Gemini
GEMINI_API_KEY=your_gemini_api_key_here

# Model yang digunakan (opsional)
GEMINI_MODEL=gemini-1.5-flash

🚀 **Instalasi & Menjalankan**

1. Clone repository
      git clone https://github.com/username/innitchat.git
      cd innitchat

2. Install dependencies (jika ada backend / Node.js)
      npm install


3. Buat file .env lalu isi seperti konfigurasi di atas.

4. Jalankan menggunakan server lokal Node.js:
      node index.js

🛠️ **Teknologi yang Digunakan**
>> Bootstrap 5
>> Bootstrap Icons
>> Google Gemini API
>>HTML, CSS, JavaScript

📜 **Lisensi**
Proyek ini dirilis di bawah lisensi MIT – bebas digunakan, dimodifikasi, dan didistribusikan dengan tetap mencantumkan kredit.

💡 **Catatan**
Untuk mendapatkan API Key Gemini, silakan daftar di: Google AI Studio
Pastikan API Key tidak dipublikasikan di repositori publik tanpa proteksi.
