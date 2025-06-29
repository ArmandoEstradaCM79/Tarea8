# 🔐 Login y Registro con Django (Diseño Rojo Pastel)

Proyecto sencillo de autenticación de usuarios en Django con un diseño limpio y minimalista basado en tonos rojos pastel.

## 🎨 Características

- Registro de usuarios con validación de contraseña
- Inicio y cierre de sesión
- Redirecciones seguras según el estado de sesión
- Interfaz visual suave y accesible
- Código limpio y modular con buenas prácticas

---

## 🖼️ Capturas de Pantalla

### Página de registro
![Registro](https://url-de-tu-captura.com/registro.png)

### Página de inicio de sesión
![Login](https://url-de-tu-captura.com/login.png)

### Página principal después del login
![Inicio](https://url-de-tu-captura.com/home.png)

---

## 🚀 Cómo ejecutar el proyecto localmente

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/nombre-del-repo.git
cd nombre-del-repo
```

### 2. Crear entorno virtual e instalar dependencias

```bash
python -m venv env
env\Scripts\activate      # En Windows
# source env/bin/activate   # En macOS/Linux

pip install django
```

### 3. Migrar la base de datos

```bash
python manage.py migrate
```

### 4. (Opcional) Crear un superusuario

```bash
python manage.py createsuperuser
```

### 5. Ejecutar el servidor

```bash
python manage.py runserver
```

Abre tu navegador en: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📁 Estructura del Proyecto

```
login_red_rojo/
├── accounts/
│   ├── forms.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── accounts/
│           ├── base.html
│           ├── login.html
│           ├── register.html
│           └── home.html
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── static/
│   └── style.css
├── manage.py
└── README.md
```

---

## 🛡️ Recomendaciones

- Usa `python-decouple` para manejar `SECRET_KEY` en producción.
- Usa `LOGIN_URL`, `LOGIN_REDIRECT_URL`, y `LOGOUT_REDIRECT_URL` para gestionar rutas de autenticación.
- Si vas a desplegar en la web, usa HTTPS y configura CSRF correctamente.

---

## 📚 Requisitos

- Python 3.8+
- Django 5.x
- Navegador moderno

---

## 📌 Autor

Desarrollado como práctica de integración de Django con diseño minimalista.

**Repositorio original del diseño base**: _Este proyecto es de uso libre y educativo._

---

## ✨ Personaliza

- Cambia los colores en `static/style.css`
- Modifica los formularios con Bootstrap o Tailwind si deseas más estilo

---

## 🔗 Enlace al proyecto

[https://github.com/tu-usuario/nombre-del-repo](https://github.com/tu-usuario/nombre-del-repo)
