# _Actividad_Git_

_Investigación sobre Git_

_Instituto: Sagrado Corazón Al.Cal_

_Materia: Laboratorio de Sistemas Operativos - 4°B_

_Profesor: Anibal Alejandro Recalde_

_1 Investigación básica de Git:_

_a. ¿Qué es Git y para qué se utiliza?_

_En pocas palabras, Git es lo que se conoce como un sistema de control de versiones. Esto significa que cualquier desarrollador que tenga acceso al repositorio (así se le llama a la carpeta que contiene el proyecto) tiene acceso al código fuente del proyecto._

_b. ¿Cuáles son las principales características de Git?_

_desarrollo distribuido - cada desarrollador que participa en un proyecto no está vinculado a un servidor central que mantiene la copia "original" del proyecto.
performance elevate para proyectos grandes - trabajar en proyectos con una larga historia o proyectos compuestos de muchos archivos es tan rápido como trabajar en proyectos más jóvenes o con pocos archivos.
la preservación del historial de cambios - la última versión está dada por la secuencia exacta de todos los cambios realizados a lo largo del tiempo, mientras que es posible insertar un nuevo cambio entre dos cambios ya realizados en el pasado, este cambio en la secuencia de eventos no puede pasar desapercibido_

_c. ¿Qué es un sistema de control de versiones?
Esto significa que cualquier desarrollador que tenga acceso al repositorio (así se le llama a la carpeta que contiene el proyecto) tiene acceso al código fuente del proyecto._

_d. ¿Cuál es la diferencia entre Git y otros sistemas de control de versiones?_

_Por ejemplo esta SVN como otro sistema de control de versiones.
La diferencia fundamental entre Subversion y Git es que el primero es centralizado y el segundo, distribuido. Los sistemas centralizados como Subversión disponen de un servidor donde están los archivos de todo el proyecto, junto con todas las modificaciones. Git se presenta como un sistema distribuido, en el que todos los nodos manejan la información en su totalidad y por lo tanto pueden actuar de cliente o servidor en cualquier momento, es decir, se elimina el concepto de “centralizado”_

_2 Instalación y configuración de Git:_

_a. Investiga cómo instalar Git en diferentes sistemas operativos (Windows, macOS, Linux)._

_Instalar GIT en Windows_

_Descarga el instalador de GIT para Windows.
Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla. Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación._


_Instalar GIT en macOS_

_Descarga el instalador oficial para Mac.
Sigue las instrucciones que te aparecerán en el programa de instalación.
Al finalizar el proceso de instalación del instalador, vuelve a revisar usando el comando git – -version para confirmar si la instalación se ha hecho correctamente.
Ahora ejecuta los siguientes comandos en la terminar para configurar tu correo y el nombre de usuario que 
están asociados a tu cuenta GIT:_


_Instalar GIT en Linux
Abre la terminal y ejecuta los siguientes comandos:_

_Sudo apt-get update_
_Sudo apt-get install git_

_Verifica que la instalación se haya hecho correctamente usando el comando: git –version._

_b. Explica los pasos para configurar tu nombre de usuario y dirección de correo electrónico en Git._

_A continuación, ejecuta los siguientes comandos en la terminal para poder configurar tu correo y nombre de usuario que están asociados a tu cuenta GIT:_

_git config --global user.name "Tu nombre"_
_git config --global user.email "ejemplo@email.com"._

_3 Comandos básicos de Git:_

_a. Investiga los comandos git init, git add, git commit y git status. Explica qué hacen y cómo se utilizan._

_El comando git init crea un nuevo repositorio de Git. Puede utilizarse para convertir un proyecto existente y sin versión en un repositorio de Git, o para inicializar un nuevo repositorio vacío._

_El comando git add añade un cambio del directorio de trabajo en el entorno de ensayo. De este modo, indica a Git que quieres incluir actualizaciones en un archivo concreto en la próxima confirmación._

_El comando git commit sirve para confirmar una instantánea del directorio del entorno de ensayo en el historial de confirmaciones de los repositorios._

_b. Describe los comandos git log y git diff para ver el historial de cambios y las diferencias entre versiones, respectivamente._

_git log:_

_El comando git log es una herramienta básica de Git para explorar el historial del repositorio. Este comando se usa cuando necesitas buscar una versión concreta de un proyecto o saber los cambios que se introducirán mediante la fusión en una rama de función._

_git diff_

_Git diff permite comparar cambios en archivos, ramas y commit. Esto ayuda a descubrir los errores con mayor rapidez y seguir más fácilmente el desarrollo de un proyecto._

_4 Trabajando con repositorios remotos:_

_a. Investiga cómo clonar un repositorio remoto con git clone._

_para clonar un repositorio remoto con git clone hay que hacer lo siguiente:_

_Copiamos el URL del repositorio que queramos clonar
Abrimos la terminal,  ingresamos el comando git clone y a continuación el URL del repositorio a clonar. Y listo._

_b. Explica cómo trabajar con ramas utilizando los comandos git branch, git checkout y git merge._

_**git branch:** Este comando lista y crea ramas._

_**git checkout:** Este otro comando se usa para moverse entre las ramas._

_**git merge:** Este último comando permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama._

_c. Investiga cómo subir tus cambios locales a un repositorio remoto con git push._

 _El git push es el último comando para editar un repositorio remoto, se usarìa:_

_**git push**_

_y si queres guardar por rama seria:_

_**git push -u origin NOMBRE_DE_LA_RAMA**_

_5 Colaboración en Git:_

_a. Investiga cómo trabajar en equipo en un repositorio remoto utilizando ramas y fusiones._

_Para poder colaborar en cualquier proyecto Git, necesitas saber cómo gestionar repositorios remotos. Los repositorios remotos son versiones de tu proyecto que están hospedadas en Internet o en cualquier otra red. Puedes tener varios de ellos, y en cada uno tendrás generalmente permisos de solo lectura o de lectura y escritura. Colaborar con otras personas implica gestionar estos repositorios remotos enviando y trayendo datos de ellos cada vez que necesites compartir tu trabajo. Gestionar repositorios remotos incluye saber cómo añadir un repositorio remoto, eliminar los remotos que ya no son válidos, gestionar varias ramas remotas, definir si deben rastrearse o no y más. En esta sección, trataremos algunas de estas habilidades de gestión de remotos._


_b. Explica qué son las solicitudes de extracción (pull requests) y cómo se utilizan para revisar y aprobar cambios._

_Las solicitudes de extracción le permiten informar a otros sobre los cambios que ha enviado a una rama en un repositorio en GitHub. Una vez que se abre una solicitud de extracción, puede discutir y revisar los posibles cambios con los colaboradores y agregar confirmaciones de seguimiento antes de que sus cambios se fusionen en la rama base._

_**revisar y aprobar cambios**_

_Puedes revisar los cambios de una solicitud de extracción en un archivo por vez. Mientras revisas los archivos en una solicitud de extracción, puedes dejar comentarios individuales en cambios específicos. Después de que terminas de revisar cada archivo, puedes marcarlo como visto. Esto colapsa el archivo, lo cual te ayuda a identificar los archivos que aún debes revisar. Una barra de progreso en el encabezado de la solicitud de cambios muestra la cantidad de archivos que has visto. Después de revisar tantos archivos como quieras, puedes aprobar la solicitud de cambios o solicitar cambios adicionales si emites tu revisión con un comentario de resumen._
