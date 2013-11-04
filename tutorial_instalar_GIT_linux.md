# Tutorial instalando git en Linux Ubuntu 12.04

## En este tutorial instalamos la última versión de Git en Linux Ubuntu 12.04 (Podeis igualmente instalar la versión que viene con Ubuntu simplemente con: sudo apt-get install git).

1. Primero abrimos un terminal y actualizamos la lista de paquetes:
> `usuario@usuario-portatil:~$ sudo apt-get update`

2. Instalamos las dependencias:
> `usuario@usuario-portatil:~$ sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext libz-dev libssl-dev build-essential`

3. Instalamos la última versión de Git desde googlecode:
> `usuario@usuario-portatil:~$ wget https://git-core.googlecode.com/files/git-1.8.2.tar.gz`

4. Descomprimimos el archivo:
> `usuario@usuario-portatil:~$ tar -zxf git-1.8.2.tar.gz`

5. Cambiamos de directorio:
> `usuario@usuario-portatil:~$ cd git-1.8.2`

6. Para hacer una instalación global lo instalamos como usuario y como root:
> `usuario@usuario-portatil~/git-1.8.2$: make prefix=/usr/local all`
> `usuario@usuario-portatil~/git-1.8.2$: sudo make prefix=/usr/local install`

7. Finalmente para actualizar git en el futuro usamos esta orden:
> `usuario@usuario-portatil:~$ git clone git://git.kernel.org/pub/scm/git/git.git`
