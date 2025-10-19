# Sitio web campaña Janet Bonilla Freire

Este repositorio contiene el sitio web estático para la candidatura de Janet Bonilla Freire a Rectora de la Universidad de Guayaquil. Se inspira en el estilo del sitio de la rectora Pilar Aranda, priorizando un diseño limpio, moderno y adaptable a dispositivos móviles.

## Estructura

```
├── index.html                # Página principal
├── assets
│   ├── css
│   │   └── style.css         # Estilos principales del sitio
│   ├── js
│   │   └── main.js           # Interacciones básicas (menú móvil y scroll suave)
│   └── images
│       └── janet-bonilla-placeholder.svg  # Retrato vectorial de respaldo
```

## Personalización

1. **Fotografía oficial:** coloca el archivo `assets/images/janet-bonilla.jpg` con la fotografía oficial de la candidata manteniendo el mismo nombre de archivo. El sitio incluye un fallback vectorial (`janet-bonilla-placeholder.svg`) para garantizar la accesibilidad si la foto no está disponible.
2. **Datos de contacto:** ajusta los enlaces de WhatsApp y redes sociales con las cuentas oficiales de campaña.
3. **Plan de gestión y agenda:** añade enlaces a documentos PDF o eventos concretos según se vayan confirmando.

## Deploy en cPanel

1. Comprime el contenido del repositorio o súbelo mediante el administrador de archivos de cPanel al directorio público (por lo general `public_html`).
2. Verifica que la estructura de carpetas se mantenga y que el dominio apunte a `index.html`.
3. Comprueba desde el navegador que los estilos y scripts se cargan correctamente.

## Desarrollo local

Puedes abrir el archivo `index.html` directamente en tu navegador o servirlo con cualquier servidor estático (por ejemplo `npx serve`).

## Licencia

Uso interno para la campaña de Janet Bonilla Freire.
