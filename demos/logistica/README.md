# Transportes Coronel - Template Web

Template web moderno para empresa de transporte y logística, construido en HTML, CSS (Vanilla) y JavaScript.

## Estructura del Proyecto

```
/
├── index.html        # Página principal (SPA)
├── css/
│   └── styles.css    # Estilos de la página, incluye variables de personalización
├── js/
│   └── main.js       # Interactividad (Scroll suave, menú móvil, animaciones)
└── assets/           # Imágenes y recursos multimedia
```

## Personalización para Clientes

Este template está diseñado para ser fácilmente adaptable a diferentes clientes.

### Colores
Abre `css/styles.css` y modifica las variables en `:root` al principio del archivo:
```css
:root {
    --primary-color: #0A192F; /* Cambiar al color corporativo principal del cliente */
    --accent-color: #FF6B35;  /* Cambiar al color secundario/llamativo */
    /* ... */
}
```

### Información de Contacto
En `index.html`, busca la sección `<section id="contacto">` y actualiza:
- Teléfonos
- Email
- Dirección física
- Enlaces de redes sociales
- Ubicación en Google Maps (reemplazando el enlace `src` del `<iframe>`)
- El número de WhatsApp en el botón flotante: `href="https://wa.me/54911..."`

## Despliegue en GitHub Pages

Dado que este proyecto usa únicamente tecnologías estáticas (HTML/CSS/JS), el despliegue es inmediato con GitHub Pages:

1. Sube este código a tu repositorio de GitHub (ej. `https://github.com/CoronelEzequiel/transportes-web`).
2. En GitHub, ve a **Settings** > **Pages**.
3. Bajo "Build and deployment", selecciona **Deploy from a branch**.
4. En Branch, selecciona `main` y haz clic en **Save**.
5. ¡Listo! En un par de minutos tu sitio estará en vivo.
