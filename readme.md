##�Qu� comando utilizaste en el paso 11? �Por qu�?

utilizo en comando git reset --hard HEAD~1 porque esto deshace el �ltimo commit
y porque con el --hard se pierden los cambios en el working copy


##�Qu� comando o comandos utilizaste en el paso 12? �Por qu�? 

primero utilizo el comando git reflog para ver en orden todos los commits y ver el que me interesa
lugo utilizo el comando git reset --hard y el identificador del commit para recuperarlo



##El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?

No causa conflictos porque no tiene el mismo archivo con distintas modificaciones
en ramas distintas; es decir no hay el mismo archivo con diferente contenido.





##El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?

S� causa conflicto, un conflicto de contenido porque tiene un archivo  pero
con distinto contenido en dos ramas distintas  y no sabe cu�l tiene que quedarse, no queda m�s 
remedio que solucionarlo
nosotros a mano.


##El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?

No. no caus� ningun conflicto porque ya solucionamos los commits anteriormente


##�Qu� comando o comandos utilizaste en el paso 25?

he utilizado el mismo comando pero con par�metros distintos:
git log --graph
git log --graph --decorate



##El merge del paso 26, �Podr�a ser fast forward? �Por qu�?

S�, porque las ramas forman una lista pero es interesante hacerlo
no fast fordward porque crea un commit y podr�amos volver a deshacer 
el merge apuntando hacia ese commit.


##�Qu� comando o comandos utilizaste en el paso 27?
git reset HEAD~1 y comprobar que se ha hecho bien con un git log --graph





##�Qu� comando o comandos utilizaste en el paso 28?
 vuelvo a poner el archivo en el staging area y luego el commit correspondiente
rehago el merge y luego hago un git reset --hard HEAD~1



##�Qu� comando o comandos utilizaste en el paso 29?

primero compruebo que no estoy en la rama title y luego ejecuto git branch -D title


##�Qu� comando o comandos utilizaste en el paso 30?
utilizo el comando git reflog para buscar d�nde tengo hecho el merge.
selecciono ese commit y hago un git checkout a ese commit
Luego creo la rama title y me posiciono en ella




##�Qu� comando o comandos usaste en el paso 32?

utilizo el comando git reflog para buscar el commit en cuesti�n
selecciono el commit y con git checkout me posiciono en �l
luego me paso a la rama master con git checkout master



##�Qu� comando o comandos usaste en el punto 33?
 igual que en el anterior punto.
utilizo el comando git reflog para buscar el commit en cuesti�n
selecciono el commit y con git checkout me posiciono en �l
luego me paso a la rama master con git checkout master

