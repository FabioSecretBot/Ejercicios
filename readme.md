1.- git reset --hard <commit>, debido a que se pedia mover la 
rama y el HEAD a un commit anterior sin conservar los cambios del 
working copy

2.- git reset --hard <commit>, debido a que se pedia mover la 
rama y el HEAD a un commit especifico y "rehacer" los cambios

3.- No pasa nada puesto que styled ya contiene todos los 
commits de master (already-up-to-date)

4.- Si hay conflicto puesto que en la rama styled y la rama 
htmlify se editaron las mismas lineas

5.- No hay conflicto puesto que la rama main ya esta incluida 
en styled (merge fast-foward)

6.- git log --graph --pretty=oneline, o utilizar alguna 
extension (VSCode) que permita una mejor visualizacion

7.- Si puede ser fast foward puesto que title contiene 
todos los commits de la rama main

8.- git reset <commit>, se pide mover la rama y el HEAD a un 
commit especifico sin perder los cambios del working copy

9.- git restore <file-name>, se pide descartar cambios del 
working copy

10.- git branch -D <branch>, se debe usar "-D" puesto que 
tiene commits que ninguna rama tiene

11.- git reset --hard <commit>, debido a que se pide mover el 
HEAD y la rama a un commit especifico y "rehacer" el commit

12.- git checkout <commit>, debido a que se pide solo visitar 
cierto commit

13.- git checkout <commit>, debido a que se pide solo visitar 
cierto commit

Nota: Aparte de los comandos mencionados tambien se usaron 
"git reflog" para buscar los commits que se solicitaban, "git 
branch" para ver la lista completa de ramas, "git status" para 
comprobar el estado actual de la rama, entre otros.
