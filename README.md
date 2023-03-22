# RamasBasico

1. En primer lugar, creamos un repositorio de Git y hacemos dos commits en la rama master para agregar los cambios A y B

git init
git commit -m "A"
git commit -m "B"


2. Luego, creamos una nueva rama llamada exp, nos cambiamos a esa rama y verificamos que hayamos cambiado correctamente:

git branch exp
git checkout exp
git branch


3. Ahora, hacemos un commit en la rama exp para agregar los cambios C:

git commit -m "C"


4. Después, nos cambiamos de nuevo a la rama master y hacemos un commit para agregar los cambios E:

git checkout master
git commit -m "E"

5. Cambiamos a la rama exp de nuevo y hacemos un commit para agregar los cambios D:


git checkout exp
git commit -m "D"


6. Por último, nos cambiamos de nuevo a la rama master y hacemos un merge con la rama exp:


git checkout master
git merge exp



