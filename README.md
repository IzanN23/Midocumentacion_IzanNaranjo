# Midocumentacion_IzanNaranjo
## Git hub

En git hub debemos saber como crear un repositorio, para ello entraremos en el propio github y le daremos a crear nuevo repositorio.

Una vez creado el repositorio lo deberemos clonar para que lo podamos utilizar, para hacer esto lo que haremos sera ir a la carpeta donde guardemos nuestros repositorios y abrir el cmd. Una vez abierto lo que haremos sera poner __git clone__ seguidamente de la URL del repositorio que se encuentra en Code dentro del repositorio.

Ahora vamos a hablar sobre los comandos de github:

1. __git init__ Esto lo que hace es que iniciemos el github en nuestra carpeta del repositorio
2. __git branch__ Lo que hace es ver la rama en la que estas trabajando, por ejemplo main
3. __git add .__ La funcion que hace es guardar la nueva informacion 
4. __git commit -m (texto)__ Se usa para guardar los cambios realizados en el repositorio local y luego la opcion -m permite agregar un mensaje de commit directamente desde el cmd, describiendo brevemente lo que se ha cambiado.
5. __git push origin__ Su funcion es  trasladar lo que hemos guardado previamente hacia nuestro repositorio de github para que podamos visualizar lo que hemos echo dentro de github

## Markdown

Las Etiquetas en __*markdown*__ y HTML pueden anidarse 

### Como hacer una lista 

Para hacer una lista lo que tenemos que hacer es seguir este codigo:

que basicamente pondremos 1. para senalizar el titulo principal de esa lista y luego le daremos a tabulador para senalizar el subtitulo de la lista.

1.Primer punto de la lista
    1.Primer elemento de la sublista 1
    2.Segundo elemento de la sublista 1
2.Segundo punto de la lista
    *Primer elemento de la sublista 2
    *Segundo elemento de la sublista 2
3.Tercer punto de la lista

#### Puesto en practica la lista 

1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2
3. Tercer punto de la lista

### Como hacer una lista desordenada

* Primer punto de lista desordenada
- Segudno punto de lista desordenada
+ Tercer punto de lista desordenada

### Como poner un link

Lo que haremos sera seguir esta estructura:

[TextoClicable ] (URL "Titulo opcional")
[Pagina web de jesuites Bellvitge] (https://www.fje.edu/ca/fje "Titulo opcional")

Lo unico que tendremos que hacer sera utilizar cualquier link como lo es en mi caso el del instituto y lo ponemos despues de poner el nombre de la pagina.

#### Puesto en practica el link

[Pagina web de jesuites Bellvitge](https://www.fje.edu/ca/fje "Titulo opcional")


### Como poner una imagen

Para colocar una imagen lo primero que haremos sera descargar la imagen desde google o cualquier navegador, acto seguido la pondremos en la carpeta donde tenemos nuestro repositorio y utilizaremos el cmd en esa carpeta para subirla a nuestro repositorio de git hub utilizando los comandos explicados previamente. 

Dentro del repositorio de git hub entraremos a nuetra imagen y copiaremos el link de la url de la imagen que esta dentro del "repositorio" para despues colocarla en visual studio utilizando este codigo:

![Imagen Venom] (https://github.com/IzanN23/Midocumentacion_IzanNaranjo/blob/main/Venom.jpg "Titulo opcional") 

#### Puesto en practica la imagen

![Imagen Venom](https://github.com/IzanN23/Midocumentacion_IzanNaranjo/blob/main/Venom.jpg "Titulo opcional") 


### Como poner una tabla

Para crear una tabla es tan facil como separar los titulos con | y abajo de cada titulo poner |-| seguido de : y otra vez |-|. Para poner contenido dentro de cada celda ponemos |

| Titulo 1 | Titulo 2 | Titulo 3 |
| ----------|:----------:|----------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso 2425|33|
|Daw1 |Curso 2425|32|


## HTML
