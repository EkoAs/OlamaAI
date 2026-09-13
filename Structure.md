app/
└── Http/
    └── Controllers/
        ├── Controller.php
        ├── MainController.php
        ├── OlamaAiController.php
        ├── ApiAiController.php
        └── EngineAiController.php




    MainController
│
├── Mengatur request utama
├── Routing logika aplikasi
└── Menjadi penghubung semua controller lain

OlamaAiController
│
├── Mengurus chat user
├── Mengelola prompt
└── Menampilkan hasil chat

ApiAiController
│
├── Koneksi ke AI eksternal
├── Koneksi ke Ollama
├── Koneksi OpenAI/Gemini (jika ada)
└── Mengirim & menerima response AI

EngineAiController
│
├── Memory AI
├── History chat
├── Menyimpan percakapan
├── Mengambil context lama
└── Menyiapkan data sebelum dikirim ke AI

User
 │
 ▼
MainController
 │
 ├─► EngineAiController
 │        │
 │        └─ Ambil history
 │
 ├─► ApiAiController
 │        │
 │        └─ Panggil AI
 │
 └─► OlamaAiController
          │
          └─ Tampilkan hasil chat