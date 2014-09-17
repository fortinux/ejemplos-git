# Tutorial crear una rama en GIT:

## En este tutorial creamos una rama en nuestro repositorio local .

1. Abrimos un terminal y vamos al directorio local de GIT:

> `usuario@usuario-portatil:~$ cd ejemplos-git`

2. Creamos una rama para poder trabajar en ella:

> `usuario@usuario-portatil:~/ejemplos-git$ git branch crear-branch`

3. Para ver las ramas de nuestro projecto escribimos:

> `usuario@usuario-portatil:~/ejemplos-git$ git branch -v`

4. Para cambiar a la rama anteriormente creada:

> `usuario@usuario-portatil:~/ejemplos-git$ git checkout crear-branch`

5. Una vez que terminamos de trabajar en la rama crear-branch integramos los cambios en la rama master:

> `usuario@usuario-portatil:~/ejemplos-git$ git checkout master`

6. Agregamos los cambios a la rama master:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git merge crear-branch`

7. Realizamos el commit escribiendo un resumen de los cambios realizados:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git add .`

8. Realizamos el commit escribiendo un resumen de los cambios realizados:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git commit -m "creado una rama para hacer pruebas"`

9. Con "git status" podemos ver en que estado están nuestros archivos:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git status`



