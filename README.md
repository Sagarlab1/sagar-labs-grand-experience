# Sagar Labs — nueva experiencia bilingüe

Sitio ES/EN con CyberCat, inteligencia de infraestructura y catálogo de investigación. HTML generado con Node.js y arte original en Canvas/WebGL.

## Desarrollo

Node.js 20 o posterior. Sin dependencias externas. Ejecutar `npm run dev` y abrir http://127.0.0.1:4173/es/.

`npm test` compila 34 páginas y ejecuta 16 pruebas de rutas, idiomas, metadatos, enlaces y recepción.

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

Nueve propuestas de investigación y desarrollo, incluyendo Sagar BMS Digital Twin SDK y Net-Zero AI Datacenter Architecture. Versiones ES/EN, visuales SVG originales y esculturas interactivas, datos reportados por el propietario, fichas informativas descargables y referencias comerciales sujetas a alcance. Las cifras del informe del 16 de noviembre de 2026 no se presentan como validación experimental ni como evidencia auditada. No se han adjuntado datos primarios, SDK ejecutable ni planos constructivos.

## Procedencia de SL/005 y SL/006

Los JSON originales facilitados por Sagar Labs están incluidos dentro de paquetes de demostración con etiquetas HYPOTHESIS / ESTIMATED, una nota de revisión del generador y muestras normalizadas. El export declara 10,539 registros por producto e incluye 10 filas, no 10,539 modelos entrenados ni diseños validados. La revisión confirmó parámetros asignados con Math.random() y constantes. Las cifras se muestran como ejemplos sintéticos, sin garantías de precisión, latencia, PUE o neutralidad de carbono.

El render conjunto de Blender facilitado por Sagar Labs se publica como imagen conceptual original. La documentación de otros programas de I+D, protocolos y subvenciones se evalúa por separado; esta revisión se limita a los dos generadores mencionados.

## Revisión de los dossiers originales

SL/005 y SL/006 son conceptos de ingeniería HYPOTHESIS / ESTIMATED. La revisión de sus generadores identificó datos sintéticos producidos con selecciones aleatorias y constantes. Los 10,539 registros declarados por cada export no equivalen a modelos entrenados ni a diseños independientemente validados. Cada JSON público conserva el export original, una muestra normalizada y notas de procedencia. El score 99.15 no se presenta como precisión medida. Los valores de PUE, latencia, agua y calor son ejemplos sintéticos. El render conjunto de Blender facilitado por el propietario se incluye sin presentarlo como fotografía de prototipos. Esta revisión se limita a SL/005 y SL/006; no evalúa protocolos de subvenciones o laboratorio.

## Expansión de investigación: Na-S, Fe-Ni y Titan

SL/007, SL/008 y SL/009 añaden conceptos de batería Na-S/MXene, imán Fe-Ni y motor PI-KAN con visuales originales y resúmenes JSON bilingües. El grafeno SL/002 incorpora los valores reportados con su procedencia sintética. Las referencias comerciales son propuestas sujetas a verificación y contrato. No se publican sellos de validación, garantías de cero alucinaciones ni afirmaciones de patentes concedidas. La revisión del prototipo Titan encontró resultados diferentes en tres llamadas con la misma entrada; no se modificó el motor. Las cuatro líneas de investigación de CyberCat son una agenda propuesta, no resultados obtenidos.

## Revisión del checkpoint — 17 de noviembre de 2026

La versión actual de Titan carga pesos persistentes. La revisión comprobó dos entradas, tres procesos CPU por entrada y tres llamadas por proceso con resultados repetibles. El script contiene cuatro ejemplos sintéticos; no se acredita precisión ni validación física. Esto sustituye la observación de falta de repetibilidad de la versión anterior. La oferta Na-S incluye un piloto computacional propuesto con alcance y calendario por confirmar, sin síntesis ni protocolo calibrado.
