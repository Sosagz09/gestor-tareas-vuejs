# 📋 Gestor de Tareas — Vue.js + Bootstrap

Aplicación web sencilla para gestionar tareas, desarrollada como proyecto final del curso **Programación para la Web** en la Universidad Gerardo Barrios.

---

## 🛠️ Tecnologías

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)

| Tecnología | Versión | Uso |
|---|---|---|
| HTML5 | — | Estructura del documento |
| CSS3 | — | Dark mode con paleta hexadecimal |
| Bootstrap | 5.3 (CDN) | Diseño visual, tabla y componentes |
| Vue.js | 3 (CDN) | Lógica reactiva e interactividad |

> No se usan archivos externos de JavaScript ni herramientas de compilación. Todo está dentro de un único archivo `index.html`.

---

## 🚀 Demo rápida

Abre el archivo `index.html` directamente en tu navegador — no requiere instalación ni servidor.

---

## ✨ Funcionalidades

- ✅ Agregar tareas con nombre y prioridad (Alta, Media, Baja)
- ✅ Tabla con colores según prioridad:
  - 🔴 Alta → `table-danger`
  - 🟡 Media → `table-warning`
  - 🟢 Baja → `table-success`
- ✅ Eliminar tareas individualmente
- ✅ Editar nombre y prioridad de una tarea existente
- ✅ Marcar tareas como completadas
- ✅ Filtrar tareas por prioridad
- ✅ Contadores: total y por nivel de prioridad
- ✅ Fecha de creación de cada tarea
- ✅ Botón "Limpiar todo" con confirmación
- ✅ Validación visual inline (sin alertas del navegador)
- ✅ Mensaje "No hay tareas registradas" cuando la lista está vacía
- ✅ Diseño Dark Mode moderno

---

## 📂 Estructura del proyecto

```
gestor-tareas-vuejs/
└── index.html    ← Toda la aplicación en un solo archivo
└── README.md
```

---

## ▶️ Cómo usar

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/gestor-tareas-vuejs.git
```

2. Abre `index.html` en tu navegador.

¡Listo! No necesitas instalar nada más.

---

## 💡 Conceptos de Vue.js aplicados

- **Reactividad** — `data()` actualiza la interfaz automáticamente
- **Eventos** — `@click`, `v-model`
- **Condiciones** — `v-if`, `v-else`
- **Listas** — `v-for`
- **Estilos dinámicos** — `:class`
- **Propiedades computadas** — `computed` para filtrado

---

## 👨‍💻 Autor

**Josué Daniel Sosa Godinez** 
