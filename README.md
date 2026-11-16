# Sagar Labs — nueva experiencia bilingüe

Sitio ES/EN con CyberCat, inteligencia de infraestructura y catálogo de investigación. HTML generado con Node.js y arte original en Canvas/WebGL.

## Desarrollo

Node.js 20 o posterior. Sin dependencias externas. Ejecutar `npm run dev` y abrir http://127.0.0.1:4173/es/.

`npm test` compila 24 páginas y ejecuta 12 pruebas de rutas, idiomas, metadatos, enlaces y recepción.

## Despliegue

Vercel: preset Other, comando `npm run build`, salida `dist`. Establecer `SITE_URL` al dominio público final. Mientras se configura la recepción persistente, establecer `ENQUIRIES_ENABLED=false` para mostrar contacto directo por correo.

La función `api/enquiries.js` requiere las variables de `.env.example`, solo en servidor. Sin configuración devuelve error explícito y no confirma una recepción falsa. No envía notificaciones por correo.

## Estado comercial

CyberCat es un producto en evolución. Las propuestas de materiales no se presentan como tecnologías industrialmente validadas. La muestra de informe es ilustrativa. Completar el aviso de privacidad y verificar la recepción real antes de activar el formulario.

La publicación mantiene el dominio y los repositorios anteriores. Antes de migrar sagarlabs.com, conservar o redirigir sus rutas editoriales e institucionales.
