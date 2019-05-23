### Conocer cuales binarios ejecutables tengo en mi sistema, se guardan en la carpeta /usr/bin

*comando*: `ls /usr/bin`
**Para saber cuantos comandos tengo en total** : `ls /usr/bin | wc -l`

## Árbol de directorios y navegación

Lo principal que hacemos en la terminal es ejecutar comandos que con el tiempo iremos aprendiendo más de estos.

Con `ls` puedes listar un directorio, y ls tiene unas banderas que te permiten listar de ciertas formas: con `l` puedes listar hacia abajo y con `lh` listar de manera humana.

En UNIX es sencillo tener archivos que no salgan a la vista tan fácilmente. Si empezamos un archivo con un punto ls no lo va a mostrar. Para encontrar esos archivos podemos usar `ls -lha`, donde a quiere decir all (todos).

Para movernos podemos utilizar el comando `cd`, que significa change directory (cambiar directorio), que nos permitirá navegar entre archivos.

Recuerda que con … te vas al directorio padre, desde donde estés ubicado, y con `~` te vas al home.

Tip: Para limpiar la pantalla puedes hacer `command+l`, o utilizar el comando `clear`.

*comando*: `ls`= Listar. Flags: -l , -h, -a.

*comando* `pwd`= Muestra la ruta actual en la que estoy en mi arbol de directorios.

*comando* `cd` = me permite navegar entre directorios. (Change directory).


