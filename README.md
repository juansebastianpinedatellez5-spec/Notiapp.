# Notiapp.
El repositorio del proyecto Notiapp


-NotiApp

Sistema web para la gestión de denuncias ciudadanas sobre daños ambientales, permitiendo a los usuarios reportar incidentes y a las entidades darles seguimiento hasta su solución.

-Interfaz del Sistema


-Descripción

NotiApp es una plataforma diseñada para facilitar la comunicación entre ciudadanos y entidades responsables frente a problemáticas ambientales.

-El sistema permite:

Reportar daños ambientales 
Gestionar denuncias 
Hacer seguimiento en tiempo real 
Notificar el estado del caso 




-Objetivo

Desarrollar una solución tecnológica que mejore la gestión, control y respuesta ante denuncias ambientales, promoviendo la participación ciudadana y la transparencia.


-Funcionalidades principales
-Ciudadano
Registro e inicio de sesión
Creación de denuncias
Envío de reportes con información detallada
Consulta del estado de sus denuncias
-Administrador
Gestión de denuncias
Validación de información
Clasificación de gravedad
Aprobación o rechazo de casos
Notificación a usuarios
-Entidad gestora
Recepción de denuncias
Seguimiento del caso
Ejecución de soluciones
Cierre de denuncias





La aplicación cuenta con varias vistas principales:

Inicio (index.html) → Página principal
Login (login.html) → Inicio de sesión de usuarios
Registro/Usuario (usuario.html) → Gestión de usuario
Reporte (reporte.html) → Creación de reportes
Consulta (consularReporte.html) → Seguimiento de reportes


Funcionalidades
Registro e inicio de sesión
Creación de reportes
Consulta de reportes existentes
Interfaz amigable para el usuario
Navegación entre módulos


Flujo del sistema
El ciudadano crea una denuncia
El administrador valida la información
Se clasifica la gravedad del caso
La entidad gestora da solución
Se cierra la denuncia y se notifica



Notiapp/
│
├── frontend/          # Interfaz de usuario (cliente web)
│   ├── index.html     # Página principal
│   ├── login.html     # Inicio de sesión
│   ├── usuario.html   # Registro / perfil de usuario
│   ├── reporte.html   # Creación de reportes
│   ├── consularReporte.html # Consulta de reportes
│   ├── estilos.css    # Estilos principales
│   └── LoEstilo.css   # Estilos adicionales
│
├── backend/           # (Futuro) lógica del servidor 
│   └── app.js o main.py
│
├── db/                # Base de datos
│   ├── scripts.sql    # Script de creación de la BD
│   └── esquema.png    # Diagrama de la base de datos
│
├── docs/              # Documentación del proyecto
│   └── Informe_AnalisisDiseño.pdf
│
├── README.md          # Documentación principal del proyecto
└── .gitignore         # Archivos ignorados por Git


<img width="764" height="495" alt="image" src="https://github.com/user-attachments/assets/23e5f9f1-1eb1-4542-93b0-818cc57f2405" />




-Roadmap (Mejoras Futuras)
Integración con backend
Base de datos (MySQL/PostgreSQL)
API REST
Sistema de notificaciones
Geolocalización
Versión móvil






Roles del equipo
Juan Sebastián Pineda Téllez
 Rol: Documentación
Wilder Santiago Marulanda
 Rol: Investigador
Hellen Sofía Ariza Serna
 Rol: Líder / Desarrollador
