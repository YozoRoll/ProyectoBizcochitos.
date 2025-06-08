# ProyectoBizcochitos.
Proyecto para practicar Front y Back.
La ideaología es realizar una pagina web sencilla con un aparto de inicio de sesión para el usuario, para que este pueda modificar sus datos.

**FRONTEND**
Página de bienvenida con información general.

Página de login/registro.

Página de configuración (accesible solo si el usuario inició sesión).

- HTML
- CSS
- JAVASCRIPT

**BACKEND**
Registro e inicio de sesión de usuarios.

Guardado de datos: usuario, correo, contraseña (hasheada), preferencias.

Lectura y modificación de datos del usuario.
- NODE,JS
- EXPRESS.JS
- MONGODB - DOCKER COMPOSE.

**ESTRUCTURA GENERAL DEL PROYECTO**

ProyectoBizcochitos
├── public/
│   ├── index.html         <-- Página principal con info básica
│   ├── login.html         <-- Página de inicio de sesión
│   ├── config.html        <-- Página para editar datos (solo si logueado)
│   └── css/
│       └── styles.css
├── server/
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── auth.js
│   ├── app.js
│   └── .env
├── docker-compose.yml
├── package.json
└── README.md
