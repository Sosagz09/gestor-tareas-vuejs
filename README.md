# 📋 Gestor de Tareas — Vue.js + Bootstrap

Aplicación web sencilla para gestionar tareas, desarrollada como proyecto final del curso **Programación para la Web** en la Universidad Gerardo Barrios.

---

## 🚀 Demo rápida

Abre el archivo `index.html` directamente en tu navegador — no requiere instalación ni servidor.

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura del documento |
| Bootstrap 5 (CDN) | Diseño visual, tabla y componentes |
| Vue.js 3 (CDN) | Lógica reactiva e interactividad |
| CSS personalizado | Dark mode con paleta hexadecimal |

> No se usan archivos externos de JavaScript ni herramientas de compilación. Todo está dentro de un único archivo `index.html`.

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

**Josué Daniel Sosa Godinez** — ISNP066724  
Ingeniería en Desarrollo de Software  
Universidad Gerardo Barrios
