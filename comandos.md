## Ejercicio 2

### Paso 1

Crear un repositorio nuevo (todo desde línea de comandos) con el nombre pagina_web y muestra su contenido desde línea de comandos.

(Dentro de la carpeta creada "pagina_web")

    git init

Para verificar el que se creo correctamente y el contenido:

    ls -a


### Paso 2

Comprueba y explica el estado del repositorio.


    git status


Ahora el repositorio está creado, pero está vacío.


### Paso 3

Crear un fichero index.html con el siguiente contenido:


    touch index.html

    nano index.html



### Paso 4

Realizar un commit con el mensaje “Primera página html”.


    git status

    git add comandos.md

    git add index.html

    git commit -m "Primera página html"


### Paso 5

Muestra y explica el estado del repositorio.

    git status

Ahora el commit está hecho localmente, solo faltaría subir los cambios a github con un push si quisieramos.


### Paso 6

Cambiar la página web para que muestre en un listado 3 ciudades que te gustaría visitar:


Lo podemos hacer usando:

    nano index.html

O desde el Visual Studio.


### Paso 7

Hacer un commit de los cambios, con el mensaje “Añadidas 3 ciudades que visitar”.


    git status

    git add comandos.html
    git add index.html

    git commit -m "Añadidas 3 ciudades que visitar"


### Paso 8

Muestra el historial de commits del repositorio.

    git log


### Paso 9

Crea una carpeta por cada ciudad que hayas indicado en el listado anterior. Introduce dentro de cada carpeta un fichero index.html con información por cada ciudad.


    mkdir berlin
    cd berlin
    touch index.html

Asi con las 3 ciudades.

La informacion la introducimos desde Visual Studio.


### Paso 10

Hacer un commit de los cambios, con el mensaje “Añadida información sobre las ciudades a visitar”.

    git status

    git add paris
    git add oslo
    git add berlin

    git commit -m "Añadida informacion sobre las ciudades a visitar"

### Paso 11

Volver a mostrar el historial de cambios.


    git log





