# PORTA-ME

Sitio web personal (portafolio) construido para mostrar mis proyectos y afianzar habilidades de desarrollo web y systems engineering. Incluye diseno moderno, cursor personalizado con particulas animadas, formulario de contacto, selector de idioma y pagina 404 personalizada.

## Funcionalidades

- Portafolio de proyectos con contenido real
- Selector de idioma (ES/EN)
- Formulario de contacto funcional (Resend)
- Cursor personalizado con particulas animadas
- SEO basico (robots.txt, sitemap.xml) y proteccion anti-spam
- Pagina 404 personalizada

## Stack

- HTML, CSS, JavaScript
- API serverless (carpeta `api/`) para el formulario de contacto (Resend)
- Desplegado en Vercel

## Estructura

```
PORTA-ME/
├── api/          # funciones serverless (contacto)
├── css/          # estilos
├── js/           # logica del sitio (cursor, particulas, idioma)
├── imagenes/     # assets
├── index.html
├── 404.html
├── robots.txt
└── sitemap.xml
```

## Como correrlo

Es un sitio estatico: abre `index.html` en el navegador, o sirvelo con cualquier servidor estatico. El formulario de contacto requiere una API key de Resend configurada como variable de entorno para funcionar en produccion (Vercel).
