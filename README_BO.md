
# 🌐 FrontWebMisHabitos – BackOffice Web

**BackOffice Web del Proyecto HabitFlow – Gestión de Hábitos Personales**

Este repositorio corresponde a la interfaz web administrativa del sistema **Mis Hábitos**, donde los usuarios pueden gestionar categorías, hábitos, seguimiento, insignias, frases motivacionales, usuarios y roles.

Este BackOffice permite que tanto administradores como usuarios gestionen toda la información necesaria del sistema de hábitos desde un navegador web de forma visual y sencilla.

---

## 👨‍💻 Equipo de Desarrollo Grupo 2

---

## 🚀 Tecnologías Utilizadas

- HTML
- CSS
- JavaScript (vanilla JS)
- GitHub Pages (para deploy, opcional)
- API REST (consumo de servicios del backend HabitFlow)

---

## 🏛️ ¿Qué es este BackOffice?

Este BackOffice es una **plataforma web de gestión administrativa** que permite controlar todos los datos del sistema HabitFlow, incluyendo:

- Creación y gestión de hábitos
- Gestión de usuarios y roles
- Registro y edición de categorías
- Asignación de insignias y frases motivacionales
- Control de seguimiento de hábitos

👉 Este módulo es la parte administrativa que complementa al sistema.

---

## 🗂️ Estructura del Proyecto

```
FrontWebMisHabitos/
├── src/
│   ├── html/          # Formularios como login y registro
│   ├── content/       # Gestión de datos: categorías, hábitos, usuarios
│   ├── css/           # Estilos personalizados
│   ├── js/            # Funciones y consumo de la API backend
│   └── index.html     # Pantalla principal del sistema
├── .gitignore
├── README.md
```

---

## 🖥️ Páginas disponibles

| Página                        | Funcionalidad                                       |
|-------------------------------|-----------------------------------------------------|
| `index.html`                  | Página principal                                    |
| `html/login.html`             | Formulario de inicio de sesión                      |
| `html/register.html`          | Formulario de registro                              |
| `html/main-gest.html`         | Dashboard de gestión principal                      |
| `content/categorias.html`     | Gestión de categorías de hábitos                    |
| `content/habitos.html`        | Gestión de hábitos                                  |
| `content/usuarios.html`       | Gestión de usuarios                                 |
| `content/roles.html`          | Gestión de roles de usuario                         |
| `content/frases.html`         | Gestión de frases motivacionales                    |
| `content/insignias.html`      | Gestión de insignias (logros del usuario)           |

---

## 🔗 Conexión con Backend

Todas las páginas consumen datos del backend mediante peticiones `fetch` en JavaScript.

**Ejemplo de petición GET para listar hábitos:**

```javascript
fetch('http://localhost:8080/api/habito/listar')
  .then(response => response.json())
  .then(data => console.log(data));
```

**Ejemplo de petición POST para crear un hábito:**

```javascript
fetch('http://localhost:8080/api/habito/guardar', {
    method: 'POST',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify({
        nombre: "Leer",
        descripcion: "Leer 20 min diarios",
        horaSugerida: "20:00"
    })
});
```

---

## 🎨 Diseño

- CSS personalizado en:
  - `login.css` → Login
  - `register.css` → Registro
  - `main-gest.css` → Dashboard

- Diseño responsive básico para pantallas desktop y móvil.

---

## ⚙️ Funcionalidades clave

- Autenticación de usuarios (login y registro)
- CRUD completo de:
  - Categorías
  - Hábitos
  - Usuarios
  - Roles
  - Insignias
  - Frases motivacionales
- Consumo de API REST del backend
- Validación básica de formularios

---

## 🏗️ Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/DavidAtma/FrontWebMisHabitos.git
```

2. Abre la carpeta `src` y ejecuta `index.html` en tu navegador (doble clic o abrir con navegador).

3. Asegúrate de que el backend esté corriendo en `localhost:8080` o cambia las rutas en los archivos `.js` si es necesario.

---

## 💡 Mejoras futuras

- Diseño más responsive.

---

## 📄 Licencia

Este proyecto es de uso académico y no está disponible para distribución comercial.

---
