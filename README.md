# Examen de Miguel Rey

Link del repositorio: https://github.com/MiguelReyy/Rey_Miguel 

1. Que es un Pull Request: Un pull request es cuando un usuario realiza un pull para realizar cambios en un repositorio que ha traido de remoto a local y despues realiza un push y pide que se revisen sus cambios para que cuando se acepten se integren a la rama que ha modificado en local.
2. Que es un conflicto de fusion: Cuando tu realizas un merge entre varios archivos puede ocurrir que en el archivo resultado de realizar ese merge se hayan generado unos conflictos en el codigo por que haya codigo incompatible o porque se corrompa algo del codigo. Esto se puede resolver entrando en el archivo donde se han fusionado y editando el codigo manualmente para finalmente lograr el resultado deseado integrando los archivos deseados.
3. Procedimiento para hacer un merge: Para realizar un merge entre ambas ramas yo me situaria en la rama main y introduciendo el comando "Git merge branch examen_parcial" se fusionando la rama examen_parcial en la rama activa que es la main.
4. Revertir commit: Para revertir un commit existe el comando  Git reset -hard HEAD-1 que te ayuda a deshacer el ultimo commit manteniendo los cambios en tu trabajo.
5. Fork:
   Para realizar un fork de un repositorio en Github basta con acceder al repositorio al que le queremos hacer el fork y existe un boton en el propio Github para realizarlo. El Fork es una herramienta de Github que se utiliza para crear una copia de un repositorio de manera que un usuario pueda realizar las modificaciones que quiera sin que el propietario de el repositorio en el cual se ha relizado el fork sufra modificaciones.
   
6.Te encuentras trabajando en un proyecto y necesitas llegar a un archivo específico llamado "archivo.txt". Este archivo está ubicado dentro de una estructura de directorios en tu sistema.

  a) cd Miguel_Rey/Universidad/UAX. Es una ruta absoluta ya que partes de la raiz y haces todo el recorrido hasta llegar al directorio UAX donde se encuentra el archivo.txt. Esto lo podemos comprobar haciendo       el comando "ls" dentro de UAX y nos apareceria el contenido del directorio.
  
  b) Con el comando "cd UAX" accederia desde el directorio Universidad al directorio UAX que contiene el archivo.txt. Es una ruta relativa ya que no pasamos por la raiz y solo accedemos de un directorio que         no es la raiz a otro que tampoco lo es.
  
7. Comandos:
   1) b.Git clone
   2) a.Git branch
   3) c.Git Checkout
   4) b.Git add
   5) b.Git commit
   6) b.Git push
   7) c.Git pull
   8) d.Git merge
   9) a.Git reset -hard
   10) c.Git log
   
8.Describe detalladamente los pasos y consideraciones que tomarías para lograr esta tarea, incluyendo cómo manejarías los posibles conflictos de fusión y cómo asegurarías que la integración final en develop sea estable y funcional.

En primer lugar añadiria por separado los cambios significativos de ambos equipos en dos archivos (matematicas.html y diseño.html) a la rama develop para comprobar que por separado funcionan y despues de comprobar su funcionalidad crearía un tercer archivo donde integraria primeramente los cambios del equipo de matematicas y realizaria una fusion (git merge diseño.html) de los cambios del equipo de diseño UX ya que estos cambios de diseño estan para complementar las nuevas actualizaciones de el equipo de matematicas comprobaria con el responsable del equipo de diseño que sigue cumpliendo su funcion, en caso de surgir algun conflicto trato de solucionarlo respetando al maximo las funcionalidades del equipo de matematicas y busco soluciones en los conflictos surgidos con el codigo, en caso de no poder lograr una solucion se lo comunico al responsable del equipo de diseño para que puedan proporcionarme una altermativa para lograr un resultado perfecto que se acople perfectamente a la rama main sin dañar los algoritmos nuevos ni su diseño.

9.¿Cuál de las siguientes afirmaciones describe mejor el proceso que seguiste para añadir el botón de "x^4" a tu calculadora web y subir los cambios al repositorio remoto?:
C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).
