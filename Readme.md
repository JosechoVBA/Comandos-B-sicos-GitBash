# COMANDOS BÁSICOS PARA GITBASH 💻

Abrimos la terminal de Git Bash en Window o la terminal de Ubuntu, tambien la terminal de Mac, y comenzamos con los siguientes comandos y creación de directorios

```sh  
pwd  #Vemos la ruta de la carpeta en la que estamos
cd #Es para navegar a una carpeta: change directory -> cambiar de directorio
cd / #Nos llava al home, en la raíz del disco
cd ~ #La virgulilla significa que estamos en el lugar de los documentos o del usuario
ls #Esto es listar los archivos, nos muestra todos los archivos en la raíz
ls -al #El espacio -al significa que es un argumento especial para ver archivos ocultos
ls -l #Muestra casi todos los archivos sin los que están ocultos
ls -a #Muestra el grupo de archivos pero no en una lista
clear #Limpia la consola o ctrl + l
cd .. #Nos devuelve a la carpeta anterior
cd U + tab #Esto se usa para un autocompletado o para buscar una referencia
cd /D #Cambiamos de disco en window
df -h #Muestra todos los directorios en Ubuntu
cd /mnt/d #Cambia de directorio usando WSL Ubuntu en window
git config #Tedremos la lista de como funciona la configuración
git config --list #Configuraciones por defecto, faltan cosas importantes
git config --list --show-origin #Veremos donde están las configuraciones guardadas
git config --global user.name "<nombre y apellido>"
git config --global user.email "<email>" #El correo debe ser el mismo que usaremos en GitHub
git config --list #Ahora veremos que ya están todos los datos completos
git add . #Ingresamos todos los archivos al área de preparación (ram)
git commit -m "<mensaje>" #Comando para registrar los commit
code . #Abrimos VS
git status #muestra el estado de los archivos en tu directorio de trabajo y área de ensayo (staging area)
git log #Vemos los commit existentes
git log --graph  #Para ver como una rama el historial
git log --graph --pretty=oneline  #Para ver el historial a través de los hash
git config --global alias.tree "log --graph --decorate --all --oneline" #Crear un alias que me sirva para lanzar una orden a git
git reset hash-nombre-commit --hard #Es un reset duro, todo vuelve a su estado anterior, es el más usado
git reset hash-nombre-commit --soft #Este es un reset suave, lo que tengamos en staging segirá allí
git checkout #Es una de las herramientas más poderosas y versátiles en Git, que permite deshacer y rehacer cambios en tu control de versiones, revisar historial, cambiar de ramas, etc.
git branch #Se utiliza para gestionar las ramas
git branch <nombre de la rama> #Crea una nueva rama
git checkout <nombre de la rama> #Para cambiar de rama

```
## CREACIÓN DE CARPETAS 📂

```sh
cd <nombre del directorio> #Nos permite navegar por las diferentes directorios
cd .. #Nos permite regresar al directorio anterior
cd /mnt/c
cd ~ #Vamos a la raíz
mkdir <nombre del directorio> #Crea un nuevo directorio
```
## MANIPULACIÓN DE FICHEROS 📝
```sh
touch vacio.txt #Crea un archivo con su extención
./ #Significa la carpeta actual
../ #Significa la carpeta anterior
cat vacio.txt #Vemos el contenido del archivo
history #Veremos la historia completa de los comandos que hemos utilizado
!72 + enter #Veremos el comando que utilizamos en ese número
rm vacio.txt #Borra el archivo seleccionado, ¡¡¡¡CUIDADO EN EL USO DE ESTE COMANDO!!!!
rm --help #Muestra como funciona el comando
touch .gitignore #Creamos un fichero en donde vamos a escribir el nombre de todos aquellos ficheros que queremos que git no tenga en cuenta durante el desarrollo del proyecto.
```


