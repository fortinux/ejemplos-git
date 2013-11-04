# Tutorial subir los cambios a un repositorio remoto en GIT:

## En este tutorial subiremos los cambios realizados en un repositorio local a un repositorio remoto en GIT.

1. Abrimos un terminal y vamos al directorio local de GIT:

> `usuario@usuario-portatil:~$ cd git`

2. Conectamos el repositorio local al repositorio remoto:

> `usuario@usuario-portatil:~/git$ git remote add ejemplos-git https://github.com/fortinux/ejemplos-git.git`

3. Subimos los cambios al mismo:

> `usuario@usuario-portatil:~/git$ git push ejemplos-git master`

4. Por el contrario, si hacemos algún cambio en el repositorio remoto, actualizamos el repositorio local:

> `usuario@usuario-portatil:~/git/ejemplos-git$ git pull ejemplos-git master`

5. Clonar un repositorio significa copiarlo a nuestro ordenador, esto nos permite modificar los archivos y luego subirlos como anteriormente explicado. Para clonarlo:

> `usuario@usuario-portatil:~/git$ git clone git@github.com:fortinux/ejemplos-git.git`

Podemos usar otros protocolos de transferencia de datos como git:// o http(s):// en vez del SSH que acabamos de utilizar.

