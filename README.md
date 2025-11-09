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

1. **Fotografía oficial:** por políticas del repositorio no se distribuyen archivos binarios. Sube manualmente a tu hosting (por ejemplo, mediante el administrador de archivos de cPanel) la fotografía oficial como `assets/images/janet-bonilla.jpg`, manteniendo exactamente ese nombre de archivo. Mientras tanto, el sitio utiliza el retrato vectorial `janet-bonilla-placeholder.svg` para que no aparezcan errores en la interfaz.
2. **Datos de contacto:** ajusta los enlaces de WhatsApp y redes sociales con las cuentas oficiales de campaña.
3. **Plan rectoral 2026–2031:** la sección “Plan Rectorado” incluye el texto completo del plan de trabajo. Actualiza el contenido desde `index.html` si necesitas ajustar metas, indicadores o añadir nuevos anexos.
4. **Plan de gestión y agenda:** añade enlaces a documentos PDF o eventos concretos según se vayan confirmando.

## Deploy en cPanel

1. Comprime el contenido del repositorio o súbelo mediante el administrador de archivos de cPanel al directorio público (por lo general `public_html`).
2. Verifica que la estructura de carpetas se mantenga y que el dominio apunte a `index.html`.
3. Comprueba desde el navegador que los estilos y scripts se cargan correctamente.

## Desarrollo local

Puedes abrir el archivo `index.html` directamente en tu navegador o servirlo con cualquier servidor estático (por ejemplo `npx serve`).

## Licencia

Uso interno para la campaña de Janet Bonilla Freire.
