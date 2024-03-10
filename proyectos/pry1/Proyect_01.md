Trabajo individual.
1. Crear un repositorio local con la estructura:
2. En Control de Cambios debe estar la versión inicial de la descripción del proceso de control de
cambios con las plantillas en blanco (podéis definir la estructura de subdirectorios que necesitéis
en ese directorio). En la raíz del repositorio incluiremos un archivo historia.txt con los comandos
de git que vayamos utilizando en el transcurso de la práctica. Estos comandos deben estar
correctamente comentados para proporcionar contexto sobre su propósito y aplicación.
3. Actualizar el repositorio local, recordar utilizar comentarios descriptivos en el proceso.
4. Utiliza una etiqueta anotada para este estado y márcalo como la versión “R1”.
5. Creamos una rama denominada “Mejoras” en el que incluimos el fichero pdf con las propuestas
de mejora en la carpeta de ControlDeCambios.
6. Modificamos el documento de Word para que sea la versión que habíamos llamado v2. Si es
necesario también modificaremos los ficheros de las plantillas.
7. Fundimos la rama con el master/main aceptando todos los cambios realizados en ella.
Posteriormente, borramos la rama “Mejoras”.
8. Tras realizar el merge, borramos el pdf de las propuestas de mejora para que en el master/main
sólo quede la versión correcta del documento con la gestión del cambio y sus plantillas.
9. Actualizamos el repositorio y etiquetamos la versión actual con la versión R2.
10. Ahora directamente en la rama principal sustituimos la versión 2 del proceso con la versión 3 y
actualizamos el repositorio local.
11. Nos hemos dado cuenta de que hemos olvidado incluir las plantillas asociadas a la versión del
proceso actualizada, por lo que decidimos devolver la rama principal al estado anterior,
actualizar con la versión 3 y sus plantillas y marcamos con la etiqueta R3.
12. Push la rama principal y los tags a un repositorio en Github.
13. Después de un tiempo, decidimos hacer cambios adicionales. Antes de nada y por si ha habido
cambios en el repositorio remoto, nos aseguramos de que la rama principal está actualizada.
14. Hemos añadido el comando anterior a historia.txt. Queremos comprobar las diferencias de este
fichero respecto a la versión en el repositorio.
15. Actualizar el repositorio remoto con todos los cambios.
