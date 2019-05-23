# INTRODUCCION A TERMINAL Y LINEA DE COMANDOS

## (C1) Conocer cuales binarios ejecutables tengo en mi sistema, se guardan en la carpeta /usr/bin

*comando*: `ls /usr/bin`
**Para saber cuantos comandos tengo en total** : `ls /usr/bin | wc -l`

## (C2) Árbol de directorios y navegación

Lo principal que hacemos en la terminal es ejecutar comandos que con el tiempo iremos aprendiendo más de estos.

Con `ls` puedes listar un directorio, y ls tiene unas banderas que te permiten listar de ciertas formas: con `l` puedes listar hacia abajo y con `lh` listar de manera humana.

En UNIX es sencillo tener archivos que no salgan a la vista tan fácilmente. Si empezamos un archivo con un punto ls no lo va a mostrar. Para encontrar esos archivos podemos usar `ls -lha`, donde a quiere decir all (todos).

Para movernos podemos utilizar el comando `cd`, que significa change directory (cambiar directorio), que nos permitirá navegar entre archivos.

Recuerda que con … te vas al directorio padre, desde donde estés ubicado, y con `~` te vas al home.

Tip: Para limpiar la pantalla puedes hacer `command+l`, o utilizar el comando `clear`.

*comando*: `ls`= Listar. Flags: -l , -h, -a. Si hago `ls ..` puedo listar los archivos del directorio anterior.

*comando* `pwd`= Muestra la ruta actual en la que estoy en mi arbol de directorios.

*comando* `cd` = me permite navegar entre directorios. (Change directory).

## (C3) Manipulación y modificación del árbol de directorios.

Ya vimos cómo navegar dentro del árbol de directorios. En esta clase vamos a ver cómo crearlos y modificarlos.

*comando* `mkdir`: crea un directorio.

*comando* `touch`: crea un archivo. Si no existe el archivo lo va a crear, y si existe le cambia la fecha de modificación

*comando* `mv`: mueve un archivo, te ayuda a modificarlo

*comando* `rm`: elimina archivos o links, no funciona para eliminar un directorio, para esto necesitas un poco más.

*comando* `rm -rf`: elimina un directorio recursivamente

*comando* `man`: es el manual de la terminal, puedes utilizarlo cuando tu quieras para entender qué hace un comando y sus banderas. Con espacio pasas una página, - con b te regresas una página y con q sales del manual.

*comando* `cp`: copia un archivo a otros directorios

*comando* `pushd y popd` : te permiten navegar entre dos directorios fácilmente como con links.

## (C4) Herramientas básicas

En esta clase vamos a ver las herramientas que más se utilizan en la línea de comandos.

*comando* `more`: te da las primeras líneas de lo que hay en el archivo. Para ver la siguiente página hacemos lo mismo que con el man, utilizamos espacio para avanzar de pagin y "b" para ir hacia atrás.

*comando* `cat`: imprime todo el contenido de un archivo en pantalla.

*comando* `tail`: te muestra las últimas 10 líneas de un archivo. Puedes agregarle un número con el - y pedir más que 10 líneas.

Ya no solo navegamos en el árbol de nodos sino que podemos modificar y ver qué hay dentro de los archivos. En la siguiente clase veremos temas más técnicos como variables y algunas formas de utilizar de forma más cómoda la terminal.





