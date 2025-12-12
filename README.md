# Bazar Frontend

Interfaz de usuario para la plataforma de e-commerce "Bazar". Esta aplicación permite a los usuarios buscar productos desde una caja de búsqueda, ver un listado de resultados y acceder al detalle de cada producto de forma rápida y amigable.

Este proyecto consume los datos servidos por el repositorio [Bazar_backend](https://github.com/Angel-Ascencio/Bazar_backend).

## DEMO
https://690c2f9364cd5def364d38bd--bazar-examen.netlify.app/?classId=935bd026-36b4-4e5b-81bd-b64cf17b6123&assignmentId=c34d615e-8970-4217-a87d-735bd68c4543&submissionId=38add25c-2222-56a3-78fd-8535d4f2ceb2


## Tecnologías y Herramientas

* **Core:** React.js [Hooks, Context API]
* **Routing:** React Router DOM
* **HTTP Client:** Axios (o Fetch)
* **Empaquetador:** Vite

## Funcionalidades

* **Caja de Búsqueda:** Input controlado que redirige a la vista de resultados.
* **Resultados de Búsqueda:** Renderizado dinámico de tarjetas de productos (muestra 4 ítems).
* **Detalle del Producto:** Vista profunda con precio, descripción, imagen en alta calidad y condición del producto.
* **Diseño Responsivo:** Adaptable a dispositivos móviles y escritorio.
* **Breadcrumbs:** Navegación por categorías basada en la respuesta del backend.

## Instalación y Ejecución

Sigue estos pasos para levantar el frontend:

  **Instalar dependencias:**
    ```bash
    npm install
    ```
