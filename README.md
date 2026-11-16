# Sagar Labs — nueva experiencia bilingüe

Sitio ES/EN con CyberCat, inteligencia de infraestructura y catálogo de investigación. HTML generado con Node.js y arte original en Canvas/WebGL.

## Desarrollo

Node.js 20 o posterior. Sin dependencias externas. Ejecutar `npm run dev` y abrir http://127.0.0.1:4173/es/.

`npm test` compila 28 páginas y ejecuta 14 pruebas de rutas, idiomas, metadatos, enlaces y recepción.

## Despliegue

Vercel: preset Other, comando `npm run build`, salida `dist`. Establecer `SITE_URL` al dominio público final. Mientras se configura la recepción persistente, establecer `ENQUIRIES_ENABLED=false` para mostrar contacto directo por correo.

La función `api/enquiries.js` requiere las variables de `.env.example`, solo en servidor. Sin configuración devuelve error explícito y no confirma una recepción falsa. No envía notificaciones por correo.

## Estado comercial

CyberCat es un producto en evolución. Las propuestas de materiales no se presentan como tecnologías industrialmente validadas. La muestra de informe es ilustrativa. Completar el aviso de privacidad y verificar la recepción real antes de activar el formulario.

La publicación mantiene el dominio y los repositorios anteriores. Antes de migrar sagarlabs.com, conservar o redirigir sus rutas editoriales e institucionales.

## Dominio principal y páginas anteriores

Dominio canónico: https://www.sagarlabs.com. Vercel mantiene la redirección del dominio raíz a www. El catálogo de materiales inglés usa `/en/materials/`, dejando `/en/research/` para los informes anteriores. `vercel.json` conserva las páginas de Atlas, Capital, Learn, productos e informes mediante rewrites al despliegue anterior `sagar-labs-website-jz3r.vercel.app`; mantener ese proyecto activo. Las rutas de contacto, equipo y plataforma con equivalentes nuevos redirigen a sus destinos.

Para rollback, volver a asignar ambos dominios al proyecto anterior conservando la redirección del raíz a www. No se cambian los nameservers ni los registros de correo.

## Catálogo actualizado

Seis propuestas de investigación y desarrollo, incluyendo Sagar BMS Digital Twin SDK y Net-Zero AI Datacenter Architecture. Versiones ES/EN, visuales SVG originales y esculturas interactivas, datos reportados por el propietario, fichas informativas descargables y referencias comerciales sujetas a alcance. Las cifras del informe del 16 de noviembre de 2026 no se presentan como validación experimental ni como evidencia auditada. No se han adjuntado datos primarios, SDK ejecutable ni planos constructivos.
