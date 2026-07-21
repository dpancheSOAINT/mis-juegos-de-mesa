readme_content = """# 🎲 Mi Ludoteca - Gestor de Juegos de Mesa

![GitHub release](https://img.shields.io/badge/Release-v1.1.0-indigo?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-22272E?style=for-the-badge&logo=github&logoColor=white)

Una aplicación web moderna, liviana y responsive para organizar tu colección de juegos de mesa, registrar cuándo fue la última vez que jugaste cada uno y mantener tus datos guardados automáticamente en tu navegador.

---

## ✨ Características Principales

- **📸 Tarjetas Visuales con Portada:** Visualiza cada uno de tus juegos con su carátula en alta definición.
- **📅 Calendario Emergente:** Selector de fecha nativo tipo *popup* para registrar fácilmente la fecha de tu última partida.
- **✏️ Edición de Fecha en Tiempo Real:** Modifica la última fecha jugada directamente desde la tarjeta del juego sin necesidad de borrarlo o volverlo a crear.
- **🗑️ Gestión Completa (CRUD):** Agrega nuevos títulos, edita sus registros y elimina juegos con confirmación de seguridad.
- **💾 Persistencia con LocalStorage:** Tus datos se guardan de forma local e inmediata en tu navegador sin requerir registro ni base de datos externa.
- **📱 Diseño Responsive & Dark Mode:** Interfaz construida con Tailwind CSS, optimizada para smartphones, tablets y pantallas de escritorio.
- **🚀 Cero Dependencias Pesadas:** Un solo archivo estático `index.html` listo para alojar gratis en **GitHub Pages** o **Vercel**.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
| :--- | :--- |
| **HTML5** | Estructura semántica de la aplicación |
| **Tailwind CSS (via CDN)** | Estilizado rápido, moderno y responsive con paleta de colores Dark Slate/Indigo |
| **JavaScript Vanilla (ES6+)** | Lógica de la app, manipulación del DOM y persistencia de datos |
| **LocalStorage API** | Almacenamiento local persistente en el navegador del usuario |

---

## 📁 Estructura del Proyecto

El proyecto está diseñado para ser ultra liviano y funcionar con un solo archivo:

```text
mis-juegos-de-mesa/
├── index.html       # Aplicación completa (HTML, CSS Tailwind y JavaScript)
└── README.md        # Documentación del proyecto
