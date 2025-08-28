## 📝 Listado de tareas. TODO List

Aplicación desarrollada en React.js para gestionar tareas y actividades de forma eficiente. Permite crear, editar, priorizar y organizar tareas en diferentes estados: pendientes, completadas y todas. Ideal para proyectos académicos, personales o laborales.

---

## 🚀 Características principales:

• ✅ Agregar tareas con nombre, prioridad, fecha límite y notas opcionales
• 📌 Filtrado por estado: Todos / Pendientes / Completados
• 🗑️ Eliminar tareas completadas con un solo clic
• ✏️ Editar tareas existentes sin perder información
• 🔄 Persistencia de datos (opcional si usás localStorage o backend)
• 🎨 Interfaz clara y responsiva, pensada para usabilidad y estética

---

## 🖼️ Vista previa

>

## 📱 Diseño responsive

La aplicación se adapta perfectamente a distintos tamaños de pantalla, ofreciendo una experiencia fluida tanto en escritorio como en dispositivos móviles.

<h3>💻 Vista en escritorio</h3>
<img src="/ListadoDeTareas/src/assets/ListadoTareasAmplio.png" alt="Vista escritorio" width="600"/>

<h3>📱 Vista en móvil</h3>
<img src="/ListadoDeTareas/src/assets/ListadoParaCelulares.png" alt="Vista móvil" width="300"/>

---

## 🛠️ Tecnologías utilizadas

```js
| Tecnología     | Uso principal                        |
|----------------|--------------------------------------|
| React.js       | Renderizado de componentes y lógica  |
| Vite           | Entorno de desarrollo rápido         |
| CSS            | Estilos personalizados               |
| useState       | Manejo de estado local               |
| useEffect      | Efectos secundarios (si aplica)      |
```

---

## 📂 Estructura del proyecto

```js
ListadoDeTareas/
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── componentes/
├── index.html
├── package.json
└── README.md
```

---

## 📦 Instalación y ejecución

```bash
# Clonar el repositorio
git clone https://github.com/MaVe1000/ListadoDeTareas-React.git

# Instalar dependencias
npm install

# Ejecutar en modo desarrollo
npm run dev
```

---

## ✨ Próximas mejoras:

• Integración con base de datos o backend

• Autenticación de usuarios

• Guardado automático en localStorage

• Animaciones para transiciones de tareas

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

---

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
