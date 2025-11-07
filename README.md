# 🐾 Portal Web Avanzado: Carnet Digital de Mascotas "ANIMALADAS"

Proyecto de desarrollo web **Front-End Avanzado** (HTML, CSS, JavaScript) que implementa el portal completo de la empresa ficticia **ANIMALADAS**.

Desarrollado en el marco del Taller de Tecnologías Web (Examen Final), este sistema demuestra la aplicación rigurosa de **diseño responsivo**, **estructura modular**, **integración de librerías de terceros (Bootstrap, SweetAlert2)** y **consumo de APIs externas**.

---

## Habilidades Clave Demostradas

###  Integración de Datos y Librerías
* **Consumo de API Externa:** La página de contacto/registro (`index10.html`) utiliza **Fetch API (AJAX)** para obtener y mostrar datos de razas de perros (API Dog CEO) en tiempo real.
* **DataTables y JQuery:** Implementación de la librería **DataTables** para gestionar y visualizar grandes conjuntos de datos de la API, ofreciendo funcionalidades de búsqueda, paginación y exportación (CSV, PDF, etc.).
* **SweetAlert2:** Uso de modales personalizados en las páginas de gestión (Controles, Vacunas, Dueño) para manejar las interacciones de **"Agregar"** y **"Eliminar"** registros de forma dinámica en la tabla (simulación de CRUD en el DOM), mejorando la UX.

###  Diseño y Arquitectura Front-End
* **Estructura Modular:** El portal se compone de una página principal (`index.html`) y **nueve páginas internas** dedicadas a módulos específicos (Controles Médicos, Vacunas, Perfiles, etc.), enlazadas mediante una barra de navegación completa.
* **Diseño Responsivo con Bootstrap 5:** Uso extensivo del framework CSS para maquetación, carruseles, *accordions* y componentes interactivos, garantizando la **adaptación total** a dispositivos móviles y de escritorio.
* **Estilo y Branding:** Aplicación de **CSS personalizado** (`estilo.css`) para establecer la identidad de marca (fondo unificado: `rgb(65, 156, 177)`, tipografía `'Comic Sans MS'`) y mantener la consistencia visual.
* **Manipulación del DOM:** Funcionalidades JavaScript dedicadas a la gestión de datos en las tablas (adición y eliminación de filas) en las páginas de gestión.

---

## Características Funcionales del Portal

* **Barra de Navegación Completa:** Enlaces directos a los 10 módulos principales del portal.
* **Módulos de Gestión:** Páginas dedicadas al registro tabular de: **Controles Médicos**, **Medicamentos**, **Tratamientos**, **Vacunas**, **Dueño** y **Perfil del Dueño**, con funcionalidad de eliminación dinámica.
* **Componentes de Interacción:** Utilización de Modales de Bootstrap en el *Home* para la información de registro y servicios de GPS.

---

##  Ejecución en Línea con GitHub Pages

Este proyecto es completamente estático (HTML, CSS, JS), lo que permite publicarlo fácilmente mediante el servicio gratuito y profesional **GitHub Pages**.

 Puedes ver el resultado final haciendo clic en el siguiente enlace:

[![Ver Portal Web](https://img.shields.io/badge/DEMO%20EN%20VIVO-Abrir-blue?style=for-the-badge&logo=githubpages&logoColor=white)](https://ejts29.github.io/Carnet-Mascotas-Web-Bootstrap-Animaladas-HTML-CSS/index.html?embed=true)


---

### Ejecución Local

1.  Clonar el repositorio.
2.  Abrir el archivo **`index.html`** directamente en cualquier navegador.

##  Estructura del Proyecto

La estructura

```

.
├── css/  
│   └── estilo.css             \# Estilos personalizados y responsivos
├── img/                       \# Archivos de Imagen (Logos, fondos, iconos, mascotas)
├── paginas/                   \# 9 Páginas internas con módulos de gestión
│   └── index10.html           \# Página de Registro/Contacto/API (JQuery, DataTables)
├── index.html                 \# Página Principal (Home)
└── README.md
