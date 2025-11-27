# Estructura de proyecto
-------------------------------
#### Esquelo html, css y js
- El index.html se encuentra en la raiz de la carpeta del proyecto, mientras que el css y los archivos .js se encuentran en src/

#### Dependecias necesarias
Tenemos los archivos package para la configuracion de npm y dependencias, la carpeta node_modules con todas las librerias necesarias, siendo esta ultima incluida en .gitignore para no ser subida a la nube.

#### Archivo de configuracion para JSDoc 
He creado un jsdoc.json que es necesario para el correcto funcionamiento de JSDoc para la generación de documentación.

#### Archivos de prueba test
Encontramos un repositorio llamado __ __test__ __ para seguir la nomenclatura con la que mayor compatibilidad tiene Jest. Ahi encontramos un archivo *.test.js para evaluar la logica js de mi app web.

#### Workflow para automatizacion de tareas
Finalmente, en .github/workflows/ encontramos un archivo deploy.yml para automatizar la fase de instalar dependecias, pruebas unitarias, documentación automatica y despliegue en aws s3. Se ejecuta tras commit en deploy.

__URL:__ http://s3.nachodaw.com.s3-website-us-east-1.amazonaws.com/

__documentacion en html de la logica JS:__ http://s3.nachodaw.com.s3-website-us-east-1.amazonaws.com/docs/
