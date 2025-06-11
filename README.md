# 📱 HabitFlow

**Aplicación de hábitos para construir una vida más organizada y saludable.**

> Proyecto del curso de Aplicaciones Móviles – Android Studio (Java)  
> Fecha de entrega: 12 de junio de 2025

---

## 👨‍👩‍👧‍👦 Integrantes del equipo

| Nombre Completo       | Participación    |
|-----------------------|------------------|
| Anthony Gutierrez     | ✅ Participó     |
| Cristian Albarracin   | ✅ Participó     |
| David Allcca          | ✅ Participó     |
| Jose Guerrero         | ✅ Participó     |
| Luis Aguirre          | ✅ Participó     |


---

## 🧩 Descripción general

**HabitFlow** es una aplicación móvil desarrollada en **Java con Android Studio** que ayuda al usuario a crear, seguir y mantener hábitos saludables mediante recordatorios, seguimiento diario, motivación y visualización de estadísticas.

---

## 🖼️ Prototipos UI

Los prototipos de todas las pantallas fueron diseñados con [excalidraw].

🔗 [Ver prototipos aquí](https://github.com/luissxd/luissxd/blob/main/UI%20imagen/Prototipo.jpeg) 

---

## 🗃️ Diseño de la Base de Datos

La app se conecta con un backend que gestiona la base de datos relacional robusta. Las entidades principales incluyen:

- Rol
- Usuario
- Categoría
- Hábito
- Frecuencia del Hábito
- Seguimiento
- Insignias
- Asignación de Insignias por Hábito
- Recordatorios
- Frases motivacionales

📌 **SQL Completo:** [Ver entidades (Script)](https://github.com/luissxd/luissxd/blob/main/BD/HabitFlow_BD)  
[Ver diseño de base de datos aquí](https://github.com/luissxd/luissxd/blob/main/BD/Diagrama_HabitFlow.png) 

---

## 🔗 Enlace al repositorio del backend

👉 [Ver backend aquí](https://github.com/usuario/backend-habitflow) <!-- PENDIENTE LINK -->

Incluye:
- Endpoint para listar hábitos
- Endpoint para registrar un nuevo hábito
- Documentación de Postman

---

## 📱 Interfaces desarrolladas

| Pantalla                | Descripción                                               |
|-------------------------|-----------------------------------------------------------|
| Pantalla de Inicio      | Muestra hábitos del día + frase motivacional              |
| Crear / Editar Hábito   | Formulario con frecuencia, hora sugerida, etc.            |
| Estadísticas            | Gráficos, progreso, rachas y medallas desbloqueadas       |
| Historial               | Cumplimiento por día, opción para dejar notas             |

✅ **1 de ellas está conectada con el backend.**

---

## ⚙️ Tecnologías utilizadas

### Android App
- Java
- Android Studio

### Backend
- [LENGUAJE]
- Base de datos SQL Server
- Documentado con Postman

---

## 🧪 Estado del proyecto

✅ Backend funcional  
✅ Diseño de base de datos completo  
✅ 4 interfaces implementadas (1 conectada al backend)  
✅ Endpoints `listar` y `guardar` funcionales  
🚧 README del backend en progreso  
🚧 Documentación en Postman enlazada

---

## 🚀 Cómo ejecutar el proyecto (App móvil)

1. Clonar este repositorio
2. Abrir en Android Studio
3. Conectar un emulador o dispositivo físico
4. Ejecutar el proyecto (`Run > Run 'app'`)
5. Probar funcionalidades básicas de hábitos

---

## 📂 Estructura del proyecto

HabitFlow/

├── app/

│ ├── java/

│ │ └── com.example.habitflow/

│ ├── res/

│ │ ├── layout/

│ │ └── values/

├── README.md

└── ...


---

## 📋 Licencia

Este proyecto es de uso académico. Cualquier uso externo debe contar con permiso de los integrantes del grupo 2.

---

