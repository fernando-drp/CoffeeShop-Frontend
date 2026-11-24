
CoffeeShop

Sitio web de una cafetería desarrollado con Astro como frontend y WordPress como gestor de contenido (backend).

El proyecto permite mostrar información de la cafetería y administrar contenido dinámico desde WordPress, consumido mediante su API REST.

Tecnologías utilizadas

Frontend
- Astro
- TypeScript
- Tailwind CSS
- JavaScript

Backend y contenido
- WordPress
- WordPress REST API
- Contact Form 7
- Zod para validación de datos

Librerías
- Leaflet
- PhotoSwipe
- Notyf

Características

- Consumo de contenido dinámico desde WordPress.
- Obtención y visualización de publicaciones y categorías.
- Rutas dinámicas para mostrar contenido.
- Validación de datos mediante esquemas.
- Formulario de contacto integrado con Contact Form 7.
- Mapa interactivo con Leaflet.
- Galería de imágenes con PhotoSwipe.
- Notificaciones con Notyf.
- Diseño adaptable a distintos dispositivos.
- Animaciones CSS.

Estructura del proyecto

```text
CoffeeShopAstro_CodeWordPress/
├── coffeeshopastro/       # Aplicación frontend en Astro
└── wordpress-theme/       # Tema personalizado de WordPress
    └── coffeeshop/
```

Ejecución local

1. Clonar el repositorio.
2. Instalar las dependencias del frontend:

   ```bash
   cd coffeeshopastro
   npm install
   ```

3. Crear el archivo `.env.development` con las direcciones locales correspondientes de WordPress y la API.
4. Iniciar el servidor de desarrollo:

   ```bash
   npm run dev
   ```

5. Abrir en el navegador la dirección local que muestra Astro.

> Nota: El proyecto utiliza una instalación local de WordPress como backend. Es necesario configurar WordPress y el tema personalizado para que el contenido y el formulario funcionen correctamente.
 Autor

Proyecto desarrollado por Ing.Fernando De La Rosa Palma, como parte de mi aprendizaje y práctica en desarrollo web.
