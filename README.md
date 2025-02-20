# API de Gestión de Tareas 📝

Una API RESTful simple pero poderosa para gestionar tareas, construida con Django REST Framework.

## 🚀 Características

- CRUD completo de tareas
- API RESTful totalmente funcional
- Interfaz de administración de Django integrada
- Documentación de API con CoreAPI
- Soporte para CORS

## 🛠️ Tecnologías Utilizadas

- Django 4.2.6
- Django REST Framework 3.14.0
- SQLite3 (Base de datos)
- Django CORS Headers

## 📋 Estructura de Datos

Cada tarea contiene:
- Título
- Descripción (opcional)
- Estado de completado

## 🔧 Instalación

1. Clona el repositorio:
```bash
git clone [URL del repositorio]
```

2. Crea un entorno virtual e instala las dependencias:
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Realiza las migraciones:
```bash
python manage.py migrate
```

4. Inicia el servidor:
```bash
python manage.py runserver
```

## 🔗 Endpoints de la API

- `GET /api/tasks/`: Lista todas las tareas
- `POST /api/tasks/`: Crea una nueva tarea
- `GET /api/tasks/{id}/`: Obtiene una tarea específica
- `PUT /api/tasks/{id}/`: Actualiza una tarea completa
- `PATCH /api/tasks/{id}/`: Actualiza parcialmente una tarea
- `DELETE /api/tasks/{id}/`: Elimina una tarea

## 💻 Ejemplo de Uso

```python
# Crear una nueva tarea
POST /api/tasks/
{
    "title": "Completar proyecto",
    "description": "Terminar la documentación del proyecto",
    "done": false
}
```

## 👥 Contribuir

Las contribuciones son bienvenidas. Por favor, abre un issue primero para discutir los cambios que te gustaría realizar.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo LICENSE.md para detalles

---
⌨️ con ❤️ por David Alejandro Chentes