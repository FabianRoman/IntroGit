### INTRODUCTION TO GIT

### Basics Commands

- <Strong>git init </Strong>(adicionar el proyecto al controlador de versiones git)
- <Strong>git add .</Strong> <i>or</i> <Strong>git add archivo</Strong> (añadir archivos al stage area)
- <Strong>git status</Strong> (visualizar los archivos que están en el stage area)
- <Strong>git commit -m "comentario"</Strong> (guardar los archivos que están en el stage area)
- <Strong>git log</Strong> (visualizar los commits realizados en el proyecto)
- <Strong>git push origin <i>rama</i></Strong>(subir los cambios al repositorio)
- <Strong>git log --oneline</Strong> (visualizar commits y ramas)
- <Strong>git branch nombre-rama</Strong> (crear rama)
- <Strong>git branch </Strong>(visualizar ramas del proyecto y donde estamos ubicados)
- <Strong>git checkout nombre-rama</Strong> (cambiar de rama)
- <Strong>git merge nombre-rama</Strong> (unir cambios de dos ramas)
- <Strong>git branch -d nombre-rama</Strong>(eliminar rama)
- <Strong>git clone <i>uri-repository</i></Strong>(clonar repositorio)
- <Strong>git pull origin nombre-rama</Strong> (traer cambios de github)
- <Strong>git push origin -d nombre-rama</Strong> (eliminar una rama de github)
- <Strong>git reset --hard</Strong> (Devolverse al último commit. Nota: Se elimina el commit actual)
- <Strong>git reset --hard id-commit</Strong> (Devolverse a un commit en específico. Nota: Se elimina el último commit)
- <Strong>git commit --amend -m "comentario"</Strong> (unir cambios al commit anterior)