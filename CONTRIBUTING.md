🤝 Guía de Contribución y Flujo de Trabajo - FEUE ULEAM

¡Bienvenido/a al equipo técnico y de comunicación de la FEUE ULEAM! Esta guía está diseñada para que cualquier miembro de la directiva actual o futura pueda actualizar la página web, subir comunicados o crear nuevos módulos de eventos de forma segura, ordenada y sin necesidad de ser un experto en programación.

📋 Reglas de Oro antes de empezar

Nunca trabajes directamente sobre el servidor en vivo sin probar: Todo cambio que subas a la rama main se publicará automáticamente en feue.uleam.edu.ec en cuestión de 1 a 3 minutos.

Respeta el archivo CNAME: Nunca lo edites ni lo elimines. Si desaparece, el dominio institucional dejará de funcionar.

Cero datos privados: Antes de subir cualquier archivo, verifica que no contenga cédulas, teléfonos, correos personales ni contraseñas (revisa la sección de seguridad en el README.md).

Nombres de archivos limpios: Usa siempre minúsculas, sin tildes, sin la letra "ñ" y sin espacios (usa guiones - en su lugar).

✅ Correcto: congreso-ingenieria-2027.html o afiche-murga.webp

❌ Incorrecto: Congreso Ingeniería 2027 (Final).html o Año Nuevo.jpg

💻 Cómo hacer cambios paso a paso (Flujo Básico)

Paso 1: Descargar la versión más reciente

Antes de tocar cualquier archivo en tu computadora, asegúrate de tener los últimos cambios que hayan hecho otros compañeros:

git pull origin main


Paso 2: Realizar tus cambios y probarlos

Si vas a actualizar la portada, edita el archivo index.html de la raíz.

Si vas a crear un nuevo evento, crea una carpeta nueva en la raíz (ej. semana-estudiante/) y coloca dentro su propio index.html.

Prueba visual: Abre el archivo en tu navegador (si usas Visual Studio Code, haz clic derecho sobre el archivo HTML y selecciona "Open with Live Server"). Verifica que se vea bien tanto en pantalla de computadora como en vista de teléfono celular.

Paso 3: Guardar y subir tus cambios a GitHub

Una vez que comprobaste que todo funciona y se ve bien, abre la terminal en la carpeta del proyecto y ejecuta estos tres comandos en orden:

Preparar los archivos modificados:

git add .


Describir qué hiciste (sé claro y breve):

git commit -m "Actualización: cronograma de eventos en portada"


Subir los cambios a internet:

git push origin main


(Nota: Si no tienes instalado Git en tu computadora y vas a hacer un cambio rápido de texto o subir una imagen, puedes hacerlo directamente desde la web de GitHub entrando al archivo, haciendo clic en el ícono del lápiz ✏️ y guardando con "Commit changes").

🖼️ Estándares para Imágenes y Multimedia

Para evitar que la página web se vuelva lenta para los estudiantes que navegan con datos móviles:

Peso máximo por imagen: Procura que ninguna imagen pese más de 300 KB - 500 KB.

Formatos recomendados: Usa .webp o .jpg para fotografías/afiches, y .svg o .png transparente para logotipos e íconos.

Herramienta gratuita recomendada: Antes de subir un afiche pesado desde Canva o Photoshop, pásalo por TinyPNG o Squoosh para reducir su peso sin perder calidad.

Ubicación: Guarda las imágenes generales en la carpeta /assets/ o dentro de la carpeta específica de tu evento (ej. /murga/assets/).

🔄 Protocolo de Traspaso de Mando (Cambio de Directiva)

Al concluir el período administrativo de la directiva vigente, el Coordinador General y el Secretario de Comunicación / Tecnología salientes deberán cumplir con el siguiente checklist:

[ ] Transferencia de propiedad en GitHub: Agregar a los nuevos representantes como administradores (Admin / Maintainer) en Settings > Collaborators and teams del repositorio.

[ ] Entrega de accesos externos: Transferir las credenciales de la cuenta administradora de Firebase / Base de Datos (si aplica) y verificar con la Dirección de Tecnología (DITIC) de la ULEAM la continuidad del apuntamiento DNS para feue.uleam.edu.ec.

[ ] Limpieza de módulos antiguos: Mover o archivar enlaces de eventos pasados que ya no estén vigentes en la página principal (index.html), manteniendo el historial en el repositorio.

[ ] Actualización del README.md: Actualizar el año y el período de gestión en la sección de créditos institucionales.
