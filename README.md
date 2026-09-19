# Home & About

<p align="center">
  <img src="https://img.shields.io/badge/Django-6.1.1-092E20?style=for-the-badge&logo=django" alt="Django 6.1.1" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite" alt="SQLite" />
</p>

<p align="center">
  <strong>Un proyecto simple y elegante hecho con Django para mostrar una landing page con secciones de inicio y acerca de.</strong>
</p>

---

## ✨ Descripción

Este proyecto es una base mínima de Django con una app llamada `pages` que incluye:

- Página principal en `/`
- Página de información en `/about/`
- Templates compartidos con un layout base
- Configuración estándar para desarrollo local

Es ideal como punto de partida para proyectos personales, portfolios, landing pages o sitios web pequeños.

---

## 🧩 Estructura del proyecto

```text
home-about/
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
├── django_base/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── pages/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── migrations/
├── templates/
│   ├── _base.html
│   ├── home.html
│   └── about.html
└── .venv/   (si lo creas localmente)
```

---

## 🚀 Inicio rápido

### 1) Clona el repositorio

```bash
git clone <url-del-repositorio>
cd home-about
```

### 2) Crea un entorno virtual

```bash
python -m venv .venv
```

En Windows:

```bash
.venv\Scripts\activate
```

En macOS/Linux:

```bash
source .venv/bin/activate
```

### 3) Instala dependencias

```bash
pip install -r requirements.txt
```

### 4) Ejecuta las migraciones

```bash
python manage.py migrate
```

### 5) Inicia el servidor

```bash
python manage.py runserver
```

Abre tu navegador en:

```text
http://127.0.0.1:8000/
```

---

## 📍 Rutas disponibles

| Ruta | Descripción |
|------|-------------|
| `/` | Página principal |
| `/about/` | Página de información |
| `/admin/` | Panel administrativo de Django |

---

## 🛠️ Tecnologías usadas

- Python
- Django
- SQLite
- HTML + Django Templates

---

## 📁 Archivos principales

- `django_base/settings.py` — configuración principal del proyecto
- `pages/views.py` — vistas para home y about
- `pages/urls.py` — rutas de la app
- `templates/home.html` — contenido de la home
- `templates/about.html` — contenido de la vista about
- `templates/_base.html` — layout base compartido

---

## ✅ Siguientes pasos recomendados

Puedes expandir este proyecto con:

- Diseño moderno y responsivo con CSS
- Formularios de contacto
- API REST o endpoints adicionales
- Bootstrap o Tailwind para estilos
- Autenticación de usuarios
- Deploy en Render, Railway o Vercel

---

## 📝 Nota

Este proyecto está configurado como una base ligera y limpia para empezar a construir una web personal o landing page sin complejidad extra.

Si quieres, puedo ayudarte a continuación con una versión más premium, agregando estilos modernos, navegación, hero section y diseño responsive.
