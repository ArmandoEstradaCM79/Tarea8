# 🔐 Login y Registro con Django

Proyecto sencillo de autenticación de usuarios en Django.

## 🎨 Características

- Registro de usuarios con validación de contraseña
- Inicio y cierre de sesión
- Redirecciones seguras según el estado de sesión


### Página de registro
![image](https://github.com/user-attachments/assets/dc1916f1-a835-45c3-8656-870ef4a89459)



### Página de inicio de sesión
![image](https://github.com/user-attachments/assets/a0821bcd-7167-4ec7-a05c-4119d3052901)


### Página principal después del login
![image](https://github.com/user-attachments/assets/fad58a5b-1cc1-42dc-b90c-3c4fd190361d)


---

## 🚀 Cómo ejecutar el proyecto localmente

### 1. Clonar el repositorio

```bash
git clone https://github.com/ArmandoEstradaCM79/Tarea8.git
cd Tarea8
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
