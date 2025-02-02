# Suchbots
/project-folder
│
├── /client (Next.js frontend)
│   ├── pages
│   │   ├── index.js
│   │   ├── login.js
│   │   └── dashboard.js
│   └── components
│       ├── Navbar.js
│       └── LoginForm.js
│
├── /server (Express.js API)
│   ├── /controllers
│   │   ├── authController.js
│   │   └── userController.js
│   ├── /models
│   │   └── User.js
│   ├── /routes
│   │   └── authRoutes.js
│   ├── /middlewares
│   │   └── authMiddleware.js
│   ├── app.js (Express.js entry point)
│   └── config.js (MongoDB and JWT config)
│
└── package.json
