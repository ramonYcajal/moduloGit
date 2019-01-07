##¿Qué comando utilizaste en el paso 11? ¿Por qué?

utilizo en comando git reset --hard HEAD~1 porque esto deshace el último commit
y porque con el --hard se pierden los cambios en el working copy


##¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 

primero utilizo el comando git reflog para ver en orden todos los commits y ver el que me interesa
lugo utilizo el comando git reset --hard y el identificador del commit para recuperarlo



##El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causa conflictos porque no tiene el mismo archivo con distintas modificaciones
en ramas distintas; es decir no hay el mismo archivo con diferente contenido.





##El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí causa conflicto, un conflicto de contenido porque tiene un archivo  pero
con distinto contenido en dos ramas distintas  y no sabe cuál tiene que quedarse, no queda más 
remedio que solucionarlo
nosotros a mano.


##El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No. no causó ningun conflicto porque ya solucionamos los commits anteriormente


##¿Qué comando o comandos utilizaste en el paso 25?

he utilizado el mismo comando pero con parámetros distintos:
git log --graph
git log --graph --decorate



##El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Sí, porque las ramas forman una lista pero es interesante hacerlo
no fast fordward porque crea un commit y podríamos volver a deshacer 
el merge apuntando hacia ese commit.


##¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1 y comprobar que se ha hecho bien con un git log --graph





##¿Qué comando o comandos utilizaste en el paso 28?
 vuelvo a poner el archivo en el staging area y luego el commit correspondiente
rehago el merge y luego hago un git reset --hard HEAD~1



##¿Qué comando o comandos utilizaste en el paso 29?

primero compruebo que no estoy en la rama title y luego ejecuto git branch -D title


##¿Qué comando o comandos utilizaste en el paso 30?
utilizo el comando git reflog para buscar dónde tengo hecho el merge.
selecciono ese commit y hago un git checkout a ese commit
Luego creo la rama title y me posiciono en ella




##¿Qué comando o comandos usaste en el paso 32?

utilizo el comando git reflog para buscar el commit en cuestión
selecciono el commit y con git checkout me posiciono en él
luego me paso a la rama master con git checkout master



##¿Qué comando o comandos usaste en el punto 33?
 igual que en el anterior punto.
utilizo el comando git reflog para buscar el commit en cuestión
selecciono el commit y con git checkout me posiciono en él
luego me paso a la rama master con git checkout master

