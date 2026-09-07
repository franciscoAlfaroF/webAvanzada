# webAvanzada
Laboratorio 1 Web Avanzada Francisco ALfaro
Pregunta 1:
En general es una buena practica desarrollar cualquier tipo de desarrollo en una rama especifica y no en main, main es la rama principal que recibe versiones finales para producción, además de que, puede crear problemas con la version estable

Pregunta 2:
Con ese comando se evita crear un .git duplicado dentro del proyecto

Pregunta 3:
Prepara y empaqueta la aplicación para producción, en el fondo construye la app verificando que es posible ejecutarla.

Pregunta 4:
git status por un lado, sirve para revisar el estado de la rama actual local comparandola con su version online en github, mientras que git diff muestra el codigo exacto que he alterado además de resaltar errores

Pregunta 5:
El evento que activa el ci es el pull_request en main, ya que así está especificado con el "on"

Pregunta 6:
Respresenta el sistema operativo limpio donde se ejecuta la prueba de la app antes de hacer la subida real.

Pregunta 7:
Primero obtiene el codigo, luego configura node.js, después instala dependecias, ejecuta las pruebas y por ultimo contruye angulas. Ejecuta primeronpm ci porque es lo correcto y así está especificado en el archivo

Pregunta 8:Falla la construcción y la app no se sube.

Pregunta 9:
No debería incluirse ya que el pipeline se asegura precisamente de que la construccion de angular sea correcta por que no tiene sentido subir una version con errores

Pregunta 10:
package.json: versionable
API_URL pública: variable
AWS_REGION: variable
DB_PASSWORD: secreto
API_TOKEN: secreto
terraform.tfstate: secreto

Pregunta 11:
Porque el frontend no debe contener información sensible, ya que es vulnerable y facil acceso.

Pregunta 12:
No queda solucionado, se debve eliminar el archivo del historial de git.

Pregunta 13:
Validate: Verifica sintaxis y consistencia
Plan: cra un plan de ejecucion y muestra los cambios
Apply: aplica los cambios propuestos

Pregunta 14: 
Porque así lo especifica cada archivo con el comando "on"

Pregunta 15: Automatizar la infraestructura

Pregunta 16: por seguridad, privacidad y buenas practicas de desarrollo 
