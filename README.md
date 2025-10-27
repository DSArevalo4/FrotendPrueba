# 🌊 Liquid Glass Login - Frontend

[![Flask](https://img.shields.io/badge/Flask-3.0.0-black?style=flat-square&logo=flask)](https://flask.palletsprojects.com/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

Frontend moderno con efecto **liquid glass** y animaciones fluidas que simula movimiento de agua. Se conecta a la API [FlaskAPIExample](https://github.com/afmirandad/FlaskAPIExample) mediante un proxy Flask para evitar problemas de CORS.

![Liquid Glass Login Demo](https://img.shields.io/badge/Status-Production%20Ready-success?style=flat-square)

## ✨ Características Principales

- 🎨 **Diseño Liquid Glass**: Efecto glassmorphism con backdrop-filter
- 🌊 **Animaciones Fluidas**: Fondo que simula movimiento de agua
- 🔐 **Autenticación JWT**: Login y registro de usuarios
- 👥 **Gestión de Usuarios**: Visualización de lista de usuarios autenticados
- 🔄 **Proxy Backend**: Evita problemas de CORS
- 💫 **Orbes Flotantes**: Elementos decorativos con animaciones orgánicas
- 📱 **Responsive Design**: Adaptable a diferentes tamaños de pantalla
- ✨ **Efectos Interactivos**: Hover, ripple y transiciones suaves

## 🚀 Demo en Vivo

[Ver Demo](https://your-deployment-url.railway.app) *(Actualizar con tu URL de despliegue)*

## 📸 Screenshots

### Login
![Login Screenshot](docs/screenshots/login.png)

### Registro
![Register Screenshot](docs/screenshots/register.png)

### Panel de Usuario
![User Panel Screenshot](docs/screenshots/user-panel.png)

## 🛠️ Tecnologías Utilizadas

### Frontend
- HTML5
- CSS3 (Glassmorphism, Animations, Backdrop-filter)
- JavaScript (ES6+)
- Fetch API

### Backend
- Python 3.8+
- Flask 3.0.0
- Flask-CORS 4.0.0
- Requests 2.31.0
- Gunicorn 21.2.0

## 📦 Instalación Local

### Prerrequisitos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Git

### Pasos de Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/TU_USUARIO/liquid-glass-login.git
cd liquid-glass-login

# 2. Crear entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Ejecutar servidor de desarrollo
python app.py
```

El servidor estará disponible en `http://localhost:5000`

## 🔧 Configuración

### Variables de Entorno (Opcional)

```bash
# Puerto del servidor
export PORT=5000

# Modo debug (solo desarrollo)
export FLASK_DEBUG=1
```

### Configuración de la API

La aplicación se conecta a:
