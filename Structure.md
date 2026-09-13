OlamaAi
├── app/
│   └── Http/
│       └── Controllers/
│           ├── Controller.php
│           ├── MainController.php
│           ├── LoginController.php
│           ├── SignupController.php
│           ├── OlamaAiController.php
│           ├── ApiAiController.php
│           └── EngineAiController.php
├── database/
│   └── migrations/
│       ├── xxxx_xx_xx_xxxxxx_create_users_table.php
│       ├── xxxx_xx_xx_xxxxxx_create_conversations_table.php
│       ├── xxxx_xx_xx_xxxxxx_create_messages_table.php
│       └── xxxx_xx_xx_xxxxxx_create_memories_table.php
├── routes/
│   ├── web.php
│   └── modules/
│       ├── main.php
│       ├── auth.php
│       ├── chat.php
│       ├── ai.php
│       └── engine.php
├── resources/
│   ├── views/
│   │   ├── auth/
│   │   │   ├── login.blade.php
│   │   │   └── signup.blade.php
│   │   ├── chat/
│   │   │   ├── index.blade.php
│   │   │   ├── history.blade.php
│   │   │   └── partials/
│   │   │       ├── sidebar.blade.php
│   │   │       └── message.blade.php
│   │   │
│   │   ├── layouts/
│   │   │   ├── app.blade.php
│   │   │   ├── auth.blade.php
│   │   │   └── chat.blade.php
│   │   │
│   │   ├── main/
│   │   │   └── dashboard.blade.php
│   │   │
│   │   └── profile/
│   │       ├── index.blade.php
│   │       └── memory.blade.php
│   │
│   ├── css/
│   │   └── (struktur sama persis dengan views)
│   │
│   └── js/
│       └── (struktur sama persis dengan views)
│
└── public/