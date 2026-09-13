
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

    main.php
│
└── Route utama aplikasi

auth.php
│
├── Login
├── Signup
└── Logout

chat.php
│
├── Chat user
└── History chat

ai.php
│
├── API AI
├── Ollama
└── AI eksternal

engine.php
│
├── Memory
├── Context
└── Engine AI

===============================================
OlamaAi
│
├── app/
│   └── Http/
│       └── Controllers/
│
│           MainController.php
│           LoginController.php
│           SignupController.php
│           OlamaAiController.php
│           ApiAiController.php
│           EngineAiController.php
│
├── database/
│   └── migrations/
│
│       create_users_table.php
│       create_conversations_table.php
│       create_messages_table.php
│       create_memories_table.php
│
└── routes/
    │
    ├── web.php
    │
    └── modules/
        │
        ├── main.php
        ├── auth.php
        ├── chat.php
        ├── ai.php
        └── engine.php


 =============================
resources\views
├── auth
│   ├── login.blade.php
│   └── signup.blade.php
├── chat
│   ├── history.blade.php
│   ├── index.blade.php
│   └── partials
│       ├── message.blade.php
│       └── sidebar.blade.php
├── layouts
│   ├── app.blade.php
│   ├── auth.blade.php
│   └── chat.blade.php
├── main
│   └── dashboard.blade.php
└── profile
    ├── index.blade.php
    └── memory.blade.php