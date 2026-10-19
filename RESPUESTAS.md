# (a) ¿En qué se diferencian git restore y git revert?
git restore descarta los cambios en los archivos del directorio de trabajo o del área de preparación, mientras que git revert crea un nuevo commit que deshace los cambios de un commit anterior.

# (b) ¿Por qué password.txt sigue siendo un problema aunque ya no aparezca en la última versión?
Porque password.txt sigue existiendo en el historial de Git, aunque se haya eliminado de la última versión, por lo que se puede recuperar y acceder a las contraseñas. Además de que se puede ver su contenido desde el commit en Github.

# (c) ¿En qué se diferencian git rm y git rm --cached?
git rm elimina el archivo del disco y del repositorio, mientras que git rm --cached lo elimina solo del seguimiento de Git manteniendolo en el disco.