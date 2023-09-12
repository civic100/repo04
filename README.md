# Repo04 #
***
### 4.1 – Crea un directorio llamado repo04, esta vez tu decides como lo haces. Es decir, tendrás que seleccionar uno de los dos caminos que hemos visto en los dos ejercicios anteriores. Pero si que queremos que exista el repositorio el local y en remoto. ###

Creamos el repositorio desde [GitHub](https://github.com/ "https://github.com")

![❌ Error ❌](./img/Captura1.JPG "New repository")

    Clonar en local:
    $ git clone "https://github.com/civic100/repo04.git"

***

### 4.2 – Añade un fichero readme.md vacío al repositorio local, ejecuta los comandos pertinentes para realizar un commit y finalmente, sube los cambios al repositorio remoto que tendrá el mismo nombre repo04.

    Crear un README.md vacio:  
    $ echo "" >> README.md
    
    Comandos para realizar commit y push:
    $ git add README.md
    $ git commit -m "repo04"
    $ git push  

![❌ Error ❌](./img/Captura2.JPG "New repository")
***

### 4.3 – Crea una rama con tu nombre y la fecha actual (por ejemplo en mi caso la rama se llamará david02032022) desde la cual editaremos el fichero

    Creacion de una nueva rama:
    $ git branch "nombre de la rama"

    Listar ramas:
    $ git branch

![❌ Error ❌](./img/Captura3.JPG "New repository")

***

### 4.4 – Desde tu rama (david02032022) edita el fichero readme.md de tal forma que quede de la siguiente manera:

# Repo04 
***
Mi primer ejercico con ramas
***