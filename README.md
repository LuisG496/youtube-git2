# Curso de _Git_ y _Github_

Hola soy Luis E. Gaetàn

# youtube-git2

# youtube-git-main2

# muestra los origenes remotos del repositorio

git reomte

# muestra los origenes remotos con detalle

git remote -v

# agregar un orìgen remoto

git remote add nombhre-origen https://github.com/usuario/repositorio.git

# renombrar un origen remoto

git remote rename nombre-viejo nombre-nuevo

# eliminar un origen remoto

git remote remove nombre-origin

# descargar una rama remota a local diferente a la principal

git checkout --track -b rama-remota origin/rama-remota

# listar etiquetas

git tag

# crea una nueva etiquta

git tag numero-version

# eliminar una etiqueta

git tag -d numero-versiòn

# mostrar informaciòn de una etiqueta

git show numero-versiòn

# sincronizando la etiqueta del repositorio local al remoto

git add .
git tag -m "v1.0.0"
git push origin nùmero-versiòn

# generando una etiqueta anotada (con mensaje de commit)

git add .
git tag -a "v1.0.0" -m "mensaje de la etiqueta"
git push --tag
