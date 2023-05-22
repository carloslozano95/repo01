# Ejercicio 1
## 1.1
Para saber si hemos inicializado el repositorio podemos ver con un
```
git status
```
Que está inicializado, además en el propio nombre de la ruta que nos aparece lo veremos que estamos en el "master"
## 1.2
Creamos el archivo y escribimos toda la documentación necesaria.
## 1.3
En este caso tenemos que añadir con:
```
git add .
```
Nuestro archivo para que pase a el "Staging area", y después haremos el commit con:
```
git commit -m "Primer commit"
```
Actualmente nuestro archivo se encuentra en **"commited"**
## 1.4
Al intentar subir nuestro archivo con push nos dice que no tenemos nuesta rama en remoto, por lo que tiene un error y no es posible ejecutar este push.
## 1.5
Al no tener nada en remoto, no puede obtener información y no devuelve nada por consola
## 1.6
Creamos un repositorio remoto desde nuestra cuenta de github, y seguimos los pasos para "enlazar" nuestro repositorio en la nube con nuestro repositorio local
```
git remote add origin https://github.com/carloslozano95/repo01.git
git branch -M main
git push -u origin main
```
Una vez hagamos este push podremos 
## 1.7
Actualmente ya tenemos un repositorio en remoto, al hacer de nuevo el comando **git remote -v** nos aparecen los cambios que se hayan hecho en nuestro repositorio, en este caso como solo hemos hecho un push nos aparece este y el _fetch_.
## 1.8
Para subir todo volvemos a ejecutar todos los comandos que hemos mencionado, los añadimos todos en un trocito de código pero se tiene que ir añadiendo línea por línea para evitar errores.
