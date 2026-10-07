Fork: Creo una copia del repositorio original dentro la cuenta de GitHub. 

Clone: Descargo el repositorio de mi cuenta de GitHub a mi computadora para poder trabajar con los archivos localmente

Branch: Creo una rama nueva para desarrollar la funcionalidad o realizar los cambios sin modificar directamente la rama principal

Modificar archivos: Realizo los cambios necesarios en los archivos del proyecto

Commit: Registro los cambios realizados en el repositorio local mediante un commit con un mensaje descriptivo.

Push: Envío la rama y sus commits desde mi computadora hacia mi repositorio en GitHub.

Pull Request: Creo una solicitud para que los cambios de mi rama sean revisados y,incorporados al repositorio original

Review: El desarrollador o los colaboradores del proyecto revisan los cambios, pueden hacer comentarios y solicitar modificaciones si es necesario

Merge: Si los cambios son aprobados, se realiza el merge para integrar la rama con la rama principal del repositorio original


Pull: Descargar los cambios más recientes del repositorio remoto para mantener mi copia local actualizada.

Fetch: Consultar los cambios existentes en el repositorio remoto sin incorporarlos todavía a mi rama local.

Resolve conflicts: Resolver conflictos cuando los cambios de diferentes ramas afectan las mismas partes de un archivo.

2. Fork y Clone
La afirmación es incorrecta por que Clone copia un repositorio remoto en mi computadora. Después de realizar un git clone, tengo una copia local de los archivos y del historial del repositorio con la que puedo trabajar desde mi computadora.

En cambio, Fork crea una copia del repositorio dentro de mi cuenta de GitHub, se realiza desde GitHub y permite que pueda trabajar sobre mi propia versión del repositorio, especialmente cuando no tengo permisos de escritura sobre el repositorio original.

Fork: crea una copia del repositorio en mi cuenta de GitHub.

Clone: descarga un repositorio desde GitHub a mi computadora.

3. Pull Request
y no , Los cambios todavía no forman parte del repositorio original.

Al realizar Push, los cambios se envían desde mi computadora hacia mi repositorio, que es el Fork del proyecto original.

Para incorporar esos cambios al repositorio original debo crear un Pull Request desde mi rama hacia la rama correspondiente del repositorio original.

Después:

Creo el Pull Request.

Los responsables del repositorio original revisan los cambios.

Pueden solicitar modificaciones o hacer comentarios.

Realizo los cambios solicitados si es necesario y vuelvo a hacer Commit y Push.

Cuando los cambios son aprobados, un responsable del proyecto puede realizar el Merge.

Con el Merge, los cambios pasan a formar parte del repositorio original.

Por lo tanto, Push no incorpora automáticamente los cambios al repositorio original. El Pull Request permite proponer los cambios y el Merge es la operación que finalmente los integra cuando son aprobados :3 

4. Request Change

¿El propietario revisa mi Pull Request y solicita cambios.?

Debo modificar los archivos según las indicaciones, hacer un nuevo commit y ejecutar git push. No necesito crear otro Pull Request; el mismo se actualiza automáticamente con los nuevos cambios.

5. Merge y repositorio local
Esto ocurre porque el repositorio local no se actualiza automáticamente. Debe ejecutar:
                            git pull
Así descargará los cambios de GitHub a su repositorio local.

6. Sync Fork
Mi Fork está desactualizado porque el repositorio original recibió nuevos commits.
Utilizaría Sync Fork en GitHub para actualizar mi Fork con los cambios del repositorio original.
La diferencia es que Sync Fork actualiza mi Fork en GitHub, mientras que git pull actualiza mi repositorio local.

