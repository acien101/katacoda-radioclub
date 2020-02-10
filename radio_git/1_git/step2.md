Ahora vamos a crear un fichero nuevo. Por ejemplo usando el programa *nano*.

Después de guardarlo, vamos a ver el estado de nuestro repositorio `git status`{{ execute }}

¿Qué sucede?

**Untracked Files**: Ficheros que aún no han sido añadidos al repositorio Git.

Para añadir el fichero a nuestro repositorio git, lo haremos con `git add .`{{ execute }}

La sentencia `git add <file|directory>` se puede utilizar de muchas formas. La anterior añade todo lo del directorio. Examina el manual de git para saber que otras formas tienes para añadir ficheros `git add --help`{{ execute }}.

Vamos a ejecutar ahora `git status`{{ execute }}

¿Qué sucede?
