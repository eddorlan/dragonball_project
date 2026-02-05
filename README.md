# 🐲 Dragon Ball API - Proyecto Django

Aplicación web para visualizar personajes de Dragon Ball utilizando la API pública de Dragon Ball.

## 🌐 Demo en Vivo

🔗 **[Ver Proyecto en Railway](dragonballproject-production.up.railway.app)**

## 🚀 Características

- ✅ Listado completo de personajes de Dragon Ball
- ✅ Búsqueda por nombre en tiempo real
- ✅ Paginación (12 personajes por página)
- ✅ Modal con detalles de cada personaje
- ✅ Diseño responsive con fondo negro
- ✅ Efectos visuales y animaciones (hover dorado)
- ✅ Integración con API externa

## 🛠️ Tecnologías Utilizadas

- **Backend:** Django 5.2
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **API:** [Dragon Ball API](https://dragonball-api.com/)
- **Estilos:** Bootstrap 5.3
- **Despliegue:** Railway
- **Control de versiones:** Git & GitHub

## 📦 Instalación Local

### 1. Clona el repositorio
```bash
git clone https://github.com/eddorlan/dragonball_project.git
cd dragonball_project
```

### 2. Crea un entorno virtual
```bash
python -m venv venv
```

### 3. Activa el entorno virtual

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### 4. Instala las dependencias
```bash
pip install -r requirements.txt
```

### 5. Ejecuta el servidor
```bash
python manage.py runserver
```

### 6. Abre en tu navegador
```
http://127.0.0.1:8000/
```

## 📁 Estructura del Proyecto
```
dragonball_project/
├── dragronball2/          # Configuración del proyecto
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── dragonball/            # Aplicación principal
│   ├── templates/
│   │   └── dragonball/
│   │       └── characters.html
│   ├── static/
│   │   └── dragonball/
│   │       ├── css/
│   │       ├── js/
│   │       └── images/
│   ├── views.py
│   └── urls.py
├── manage.py
├── requirements.txt
├── Procfile
└── README.md
```

## 🎨 Capturas de Pantalla

![Vista principal](link-a-captura-1.png)
![Vista de personaje](link-a-captura-2.png)

## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [eddorlan](https://github.com/eddorlan)
- LinkedIn: [orlando-riera-6381a3267](www.linkedin.com/in/orlando-riera-6381a3267)

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## 🙏 Agradecimientos

- API de Dragon Ball: [dragonball-api.com](https://dragonball-api.com/)
- Bootstrap 5
- Railway (hosting)

---

⭐ Si te gustó este proyecto, no olvides darle una estrella en GitHub