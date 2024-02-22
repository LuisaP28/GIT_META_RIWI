# Comando para listar las ramas

git branch //ver todas las ramas disponibles que están en el proyecto

# Comando para crear una nueva rama

git branch nombre_rama

# Comando para eliminar una rama

git branch -D nombre_rama

# Comando para cambiar entre ramas

git switch nombre_rama
git checkout nombre_rama
git checkout -b nombre_rama  => Creamos la rama y nos cambiamos de una vez a la nueva rama

# Desvincular un arcivo de git que se le estaba dando seguimiento 

git rm --cached nombre_archivo 

# Crear una nueva versión con archivos que ya se le estaban dando seguimiento 

git commit -am "nombre commit"

# Comando para unir ramas

git merge nombre_rama 