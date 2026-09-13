
app/Http/Controllers/

Controller.php
MainController.php
LoginController.php
SignupController.php
OlamaAiController.php
ApiAiController.php
EngineAiController.php



MainController
│
├─ Pusat aplikasi

LoginController
│
├─ Login
├─ Logout
└─ Verifikasi user

SignupController
│
├─ Registrasi user
└─ Pembuatan kode login

OlamaAiController
│
├─ Chat user
└─ Tampilan percakapan

ApiAiController
│
├─ Hubungan ke AI
└─ Request/Response AI

EngineAiController
│
├─ History
├─ Memory
├─ Context AI
└─ Penyimpanan percakapan





==================================================================
database/
└── migrations/

xxxx_xx_xx_xxxxxx_create_users_table.php
xxxx_xx_xx_xxxxxx_create_conversations_table.php
xxxx_xx_xx_xxxxxx_create_messages_table.php
xxxx_xx_xx_xxxxxx_create_memories_table.php

==========================================================

routes/
│
├── web.php
│
└── modules/
    ├── main.php
    ├── auth.php
    ├── chat.php
    ├── ai.php
    └── engine.php