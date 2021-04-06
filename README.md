se utilizo el git init para iniciar mi repositorio local 
-cree el archivo de las respuestas 
con el touch y el nombre de mi archivo
los agrege usando el comando git add .
y el git commit -m 

luego fui agregando pregunta por pregunta de la misma forma agregando la pregunta y respuesta en el archivo que cree antes lo guarde y lo agregue
con el git add . y el git commit -m 

luego de llegar hasta la oregunta 5 revise el log y me aparecieron las 6 inserciones del archivo y de las 5 preguntas
y cre el repositorio de githut 

luego lo que hice fue 
el git remote add y el enlace del repositorio para trabajar desde mi repositorio remoto
luego subi mi archivo local al remoto
con el comando 
-git push -u origin y el nombre de la rama que en este caso es master 
y refresque la pagina de git y ya me aparecio el archivo con las 5 preguntas 

luego de eso cree la rama 2 para responder las otras 5 preguntas 
con el git branch el nombre de rama el cual le puse master2

y para poder trabajar en esa rama tuve que utilizar el 

git checkout master2 y se me cambio a la rama master2
y me aparecio el mismo documento de la rama master y ahi agregue las otras 5 preguntas de la misma manera editando el archivo txt y agregando con el git add y el git commit -m

luego para poder ver las inserciones utilice el git log y ya me aparecieron 
eespues me pase a la rama master que es la rama principal 
de nuevo con 
git checkout master
y desde ahi fusione las dos ramas con el siguiente comando
git merge master2 la cual es la rama 2

y verifiqye si no habi algo mas que guardar y lo subi al repositorio remoto con 

git push -u origin master 

y tambien la rama master 2 

con el git push -u origin master2

y refresquye la pagina y ya me aparecieron ambas ramas 

luego cree el archivo README.md 
con el  touch README.md

edite el archivo en blog de notas y guarde loas cambios y los agregue con el git add .
y el git commit -m 