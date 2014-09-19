# Tutorial configurar GIT en Linux Ubuntu

## En este tutorial configuramos GIT en Linux Ubuntu.

1. Primero abrimos un terminal y habilitamos los colores para GIT:
> `usuario@usuario-portatil:~$ git config --global color.ui true`

2. Ahora configuramos nuestro nombre de usuario:
> `usuario@usuario-portatil:~$ git config --global user.name "usuario"`

3. Configuramos nuestra dirección de e-mail:
> `usuario@usuario-portatil:~$ git config --global user.email "usuario@email.com"`

4. Creamos una llave SSH:
> `usuario@usuario-portatil:~$ ssh-keygen -t rsa -C "usuario@email.com"`

5. Copiamos la clave SSH en nuestra cuenta en GIT https://github.com/settings/ssh:
> `usuario@usuario-portatil:~$ cat ~/.ssh/id_rsa.pub`

6. Controlamos si esta correcta:
> `usuario@usuario-portatil:~$ ssh -T git@github.com`

7. Recibiremos un mensaje diciendo que autenticamos nuestra cuenta pero que GIT no provee acceso shell.
