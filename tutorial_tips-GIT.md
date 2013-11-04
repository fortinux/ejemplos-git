# Tutorial comandos y trucos GIT:

## En este tutorial veremos algunos comandos útiles y trucos para GIT.

1. Ignorar archivos temporales de Linux. 
Este sistema operativo cuando trabajamos con un archivo genera automáticamente un archivo temporal del mismo nombre pero terminado con una tilde (~). Para que GIT no los guarde en el siguiente commit creamos el archivo .gitignore (salimos con ctrl + D):

>> `usuario@usuario-portatil:~$ cat > .gitignore
*~`

2. Comparar la diferencia entre tu directorio de trabajo y el área de staging

>> `usuario@usuario-portatil:~/git/ejemplos-git$ git diff --staged`