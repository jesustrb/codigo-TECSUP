Primer dia con Git y Gitub

Lista de comandos de Git

* Para poder ver la version de git ejecutamos en nuestra terminal:
``````bash
git --version
git -v
``````
* Para configurar el correo y nombre {solo la primera vez en mi maquina}

``````bash
git config --global user.email micorreo@gmail.com
git config --global user.name miNombre
``````
* Para ver la configuracion de Git
``````bash
git config --list
``````
* Para inicializar nuestro repositorio en git:

``````bash
git init
``````

* Para ver el estado de nuestros cambios:

``````bash
git status
``````
* Para preparar nuestros archivos para la zona de stage {prepararlos para commit}

``````bash
git add .
git add nombreDelArchivo.extension
``````