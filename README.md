# 📋 Gestor de Tareas

Una aplicación web moderna y minimalista para la gestión eficiente de tareas personales, desarrollada con tecnologías web estándar (HTML, CSS y JavaScript vanilla).

![Estado del Proyecto](https://img.shields.io/badge/estado-activo-success.svg)
![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---


## 🎯 Descripción

Gestor de Tareas es una aplicación web intuitiva que permite a los usuarios crear, organizar y gestionar sus tareas diarias de manera eficiente. Con una interfaz limpia y responsive, ofrece todas las funcionalidades esenciales para mantener la productividad sin complicaciones innecesarias.

---


## ✨ Características

- ✅ **Crear tareas** con título y descripción detallada
- 🔄 **Marcar tareas como completadas** con feedback visual
- ✏️ **Editar tareas existentes** de forma sencilla
- 🗑️ **Eliminar tareas** que ya no son necesarias
- 💾 **Persistencia de datos** mediante LocalStorage
- 📱 **Diseño responsive** que se adapta a todos los dispositivos
- 🎨 **Interfaz moderna** con transiciones y animaciones suaves
- 🚀 **Rendimiento óptimo** sin dependencias externas

---


## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Flexbox y animaciones
- **JavaScript ES6+**: Lógica de aplicación con programación orientada a objetos
- **LocalStorage API**: Persistencia de datos en el navegador

---


## 📋 Requisitos Previos

Para ejecutar este proyecto solo necesitas:

- Un navegador web moderno (Chrome, Firefox, Safari, Edge)
- Un editor de código (opcional, para modificar el proyecto)

---


## 🚀 Instalación y Uso

### Opción 1: Clonar el repositorio

```bash
# Clonar el repositorio
git clone https://github.com/dulcemariaom1987/gestor-tareas.git

# Navegar al directorio del proyecto
cd gestor-tareas

# Abrir el archivo index.html en tu navegador
# En Windows:
start index.html

# En macOS:
open index.html

# En Linux:
xdg-open index.html
```

### Opción 2: Descarga directa

1. Descarga el repositorio como ZIP desde GitHub
2. Extrae los archivos en tu computadora
3. Abre el archivo `index.html` en tu navegador preferido

### Opción 3: Uso en línea

También puedes usar GitHub Pages si está configurado, accediendo a:
```
https://dulcemariaom1987.github.io/gestor-tareas/
```

---


## 📁 Estructura del Proyecto

```
gestor-tareas/
│
├── index.html
└── README.md

---


## 💡 Uso de la Aplicación

### Agregar una tarea nueva

1. Escribe el título de la tarea en el campo "Título de la tarea"
2. Añade una descripción opcional en el campo correspondiente
3. Haz clic en el botón "Agregar Tarea"
4. La tarea aparecerá inmediatamente en la lista

### Marcar tarea como completada

- Haz clic en el checkbox junto a la tarea
- El texto se tachará indicando que está completada
- El estado se guardará automáticamente

### Editar una tarea

1. Haz clic en el botón "Editar" de la tarea deseada
2. Los campos se rellenarán con la información actual
3. Modifica el contenido según necesites
4. Haz clic en "Actualizar Tarea" para guardar los cambios

### Eliminar una tarea

- Haz clic en el botón "Eliminar" junto a la tarea
- La tarea se eliminará permanentemente de la lista

---


## 🎨 Características Técnicas

### Arquitectura del Código

- **Programación Orientada a Objetos**: Clase `GestorTareas` para encapsular la lógica
- **Separación de Responsabilidades**: HTML para estructura, CSS para presentación, JS para comportamiento
- **Event Delegation**: Manejo eficiente de eventos en elementos dinámicos
- **Gestión del Estado**: Sistema de edición y actualización de tareas

### Persistencia de Datos

```javascript
// Los datos se guardan automáticamente en LocalStorage
// Cada cambio actualiza el almacenamiento local del navegador
localStorage.setItem('tareas', JSON.stringify(tareas));
```

### Responsive Design

- Diseño adaptable mediante Flexbox
- Media queries para diferentes tamaños de pantalla
- Optimización para dispositivos móviles y desktop

---


## 🔧 Personalización

### Modificar colores

Edita el archivo `styles.css` para cambiar el esquema de colores:

```css
:root {
  --color-primario: #4CAF50;
  --color-secundario: #45a049;
  --color-fondo: #f4f4f4;
}
```

### Añadir nuevas funcionalidades

El código está estructurado para facilitar la extensión:

```javascript
class GestorTareas {
  // Añade nuevos métodos aquí
  filtrarTareas(criterio) {
    // Tu código personalizado
  }
}
```

---


## 🐛 Reporte de Bugs

Si encuentras algún error, por favor abre un issue en GitHub incluyendo:

- Descripción detallada del problema
- Pasos para reproducir el error
- Navegador y versión utilizada
- Capturas de pantalla (si aplica)

---


## 📝 Roadmap

Funcionalidades planeadas para futuras versiones:

- [ ] Sistema de categorías y etiquetas
- [ ] Filtros avanzados (completadas, pendientes, por fecha)
- [ ] Fechas límite y recordatorios
- [ ] Priorización de tareas
- [ ] Tema oscuro/claro
- [ ] Exportar/importar tareas (JSON, CSV)
- [ ] Búsqueda de tareas
- [ ] Estadísticas de productividad

---


## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---


## 👩‍💻 Autor

**Dulce María**

- GitHub: [@dulcemariaom1987](https://github.com/dulcemariaom1987)
- Proyecto: [gestor-tareas](https://github.com/dulcemariaom1987/gestor-tareas)

---


## 🙏 Agradecimientos

- Inspirado en la necesidad de herramientas simples y efectivas de gestión de tareas
- Comunidad de desarrolladores web por las mejores prácticas
- Recursos de diseño de interfaz moderna

---


## 📞 Soporte

Si tienes preguntas o necesitas ayuda:

- Abre un [Issue](https://github.com/dulcemariaom1987/gestor-tareas/issues) en GitHub
- Consulta la documentación en este README
- Revisa los issues existentes para ver si tu pregunta ya fue respondida

---

⭐ Si este proyecto te resultó útil, considera darle una estrella en GitHub

**Desarrollado con ❤️ y ☕ por Dulce María**
