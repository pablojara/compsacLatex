# compsacLatex
Short paper latex version of "Diseño y despliegue de infraestructuras Big Data basadas en tecnologías de virtualización ligera y cloud computing" for COMPSAC application.


La forma de trabajo que sigo es la siguiente:

1. Se edita el fichero paper.tex, que luego se compila con el script LATEAR de la siguiente forma: 

$ ./LATEAR paper


2. El script LATEAR, de forma automática,  genera el fichero paper.pdf, pero también genera automáticamente una copia de la versión actual del paper (fichero tex y pdf) de la siguiente forma. Se copia el fichero paper.tex y paper.pdf en el fichero cuyo nombre es NOMBREPAPER y la fecha actual, donde NOMBREPAPER es un archivo que contiene un nombre descriptivo del paper. Este nuevo fichero se deposita en la carpeta Copias. De esta forma, en la carpeta Copias tendremos ficheros como los siguientes: NetSchedKubernetes-2019.12.25.tex y NetSchedKubernetes-2019.12.25.pdf.


A la hora de trabajar, lo único que hay que hacer es editar el fichero paper.tex con tu editor favorito (yo uso gedit), y luego ejecuto el scrip LATEAR como se indica arriba. De esta forma tendremos el paper en pdf y también la copia del paper (una por cada día que hayamos trabajado en él).

