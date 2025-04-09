# Midocumentacion_IzanNaranjo

## Índice
- [GitHub](#github)
- [Markdown](#markdown)
- [HTML](#html)
- [CSS](#css)
- [Flexbox](#flexbox)
- [Responsive Design](#responsive-design)
- [XML](#xml)

---


## Git hub

En git hub debemos saber como crear un repositorio, para ello entraremos en el propio github y le daremos a crear nuevo repositorio.

Una vez creado el repositorio lo deberemos clonar para que lo podamos utilizar, para hacer esto lo que haremos sera ir a la carpeta donde guardemos nuestros repositorios y abrir el cmd. Una vez abierto lo que haremos sera poner __git clone__ seguidamente de la URL del repositorio que se encuentra en Code dentro del repositorio.

Ahora vamos a hablar sobre los comandos de github:

1. __git init__ Esto lo que hace es que iniciemos el github en nuestra carpeta del repositorio
2. __git branch__ Lo que hace es ver la rama en la que estas trabajando, por ejemplo main
3. __git add .__ La funcion que hace es guardar la nueva informacion 
4. __git commit -m (texto)__ Se usa para guardar los cambios realizados en el repositorio local y luego la opcion -m permite agregar un mensaje de commit directamente desde el cmd, describiendo brevemente lo que se ha cambiado.
5. __git push origin__ Su funcion es  trasladar lo que hemos guardado previamente hacia nuestro repositorio de github para que podamos visualizar lo que hemos echo dentro de github

Tambien tenemos el github pages que sirve para que nos genere un enlace para ver nuestra pagina web creada con HTML.

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

### Introduccion HTML
- HTML (HyperText Markup Language) es el lenguaje de marcado estandar para crear paginas web. Ademas, es Lenguaje mas importante de Internet dado que sin HTML no se veria nada en el navegador.
- HTML define la estructura y el contenido (es decir, si hay una imagen, una lista de elementos, un enlace, un parrafo, un titular, etc.) de las paginas web mediante etiquetas, describe todo el contenido
- Los elementos HTML son los bloques de construccian de las paginas HTML.
- Cada elemento HTML esta delimitado por etiquetas, como < body>, < head>, < p>, < h1>, etc.
- Este lenguaje de programacion fue creado por Tim Barners-Lee en 1991.

HTML son las siglas de HyperText Markup Language, que tiene el siguiente significado:
* HyperText: Hipertexto, texto que enlaza con otros documentos.
* Markup: Marcar o etiquetar, base del funcionamiento de la web.
* Language: Lenguaje de las paginas web estandarizadas.

El contenido del codigo esta dentro de las primeras versiones hasta la ultima etapa del sistema de un etiquetado en una lengua y el cierre del paragrafo: < html>, < head>, < title>, < body>.
HTML usa una serie de convenciones que lo definen como un lenguaje, pero no es un lenguaje de programacion. No tiene estructuras como bucles, condiciones o funciones.

### Elementos de HTML

HTML es un lenguaje de marcado que define la estructura de su contenido. consiste en una serie de elementos que usaras para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera.

#### Partes de un elemento HTML

* Etiqueta de apertura: Consiste en el nombre del elemento (en este caso, p), encerrado por parentesis angulares < >.
* Etiqueta de cierre: Igual que la etiqueta de apertura, pero incluye una barra / antes del nombre del elemento.
* Contenido: Todo lo que esta dentro del texto.
* Elemento completo: La combinacion de la etiqueta de apertura, el contenido y la etiqueta de cierre.

#### Estructura basica de un fichero html

Una pagina HTML incluye una declaracion DOCTYPE, un elemento < html>, y dentro de este, un < head> y un < body>. El < head> contiene metadatos y enlaces a hojas de estilo y scripts, mientras que el < body> contiene el contenido principal de la pagina web.

#### Ejemplo basico de estructura HTML

HTML
< !DOCTYPE html>
< html>
< head>
    < meta charset="UTF-8">
    < title>Prueba de pagina</ title>
</ head>
<  body>
    < img src="logo.png" alt="mi imagen de prueba">
</ body>
</ html>

__Explicacion:__

<! DOCTYPE html>: Indica el tipo de documento; en este caso, un documento HTML5.
< html>: Elemento raiz que contiene todo el contenido de la pagina.
< head>: Contiene metadatos que no se muestran directamente en la ventana del navegador.
< meta charset="UTF-8">: Especifica la codificacion de caracteres para el documento HTML.
< title>: Define el titulo del documento mostrado en la barra de titulo del navegador o en las pestanas.
< body>: Define el cuerpo del documento y es un contenedor para todos los contenidos visibles como encabezados, parrafos, imagenes, hipervinculos, tablas, listas, etc.
< h1>: Define un encabezado grande; hay seis niveles disponibles: h1 es el mas grande y h6 es el mas pequeno.
< p>: Define un parrafo.

### Introduccion a atributos HTML

- Atributos: Proporcionan informacion adicional sobre los elementos HTML.
Ejemplo: < p class="editor-note">Mi perro es grande</p>
class es el nombre del atributo.
editor-note es el valor del atributo.
- Uso de atributos:
Se incluyen en la etiqueta de apertura.
Deben tener un espacio entre el nombre del elemento y el atributo.
El nombre del atributo va seguido de un signo igual =.
El valor del atributo se encierra entre comillas.
Anidamiento: Colocar elementos dentro de otros elementos.
- Elementos vacios: No tienen contenido, por ejemplo, < img src="images/Venom.png" alt="Mi imagen de prueba">.

#### Estructura basica de un fichero HTML

HTML
< !DOCTYPE html>
< html>
< head>
    < meta charset="UTF-8">
    < meta name="description" content="">
    < meta name="keywords" content="">
    < meta name="author" content="">
    <  link rel="stylesheet" href="#">
    < title>Pagina de prueba</ title>
    < link rel="icon" href="#" type="image/png">
    < script src="script.js"></ script>
< /head>
< body>
    <!-- Contenido de la pagina -->
< /body>1
< footer>
    <!-- Informacian adicional -->
< /footer>
< /html>

__Explicacion:__

__Declaraciones del tipo de caracteres__
* < meta charset="UTF-8"> indica el tipo de codificacion de caracteres que debe usar el navegador para mostrar correctamente los caracteres del documento.
__Descripcion y palabras clave__
* < meta name="description" content=""> y < meta name="keywords" content=""> se usan para proporcionar informacion que los motores de busqueda utilizan para indexar la pagina.
* La descripcion es un breve resumen del contenido del sitio web.
* Las palabras clave son terminos relacionados con el contenido del sitio web.
__Autoria e informacion adicional__
* < meta name="author" content=""> se utiliza para indicar quien es el autor del documento.
* El elemento < footer> se usa para anadir informacion como datos de contacto o derechos de autor al final del documento.
__Palabras clave (keywords)__
* El titulo es la principal etiqueta descriptiva el elemento < title> establece el titulo de la pagina en la pestana del navegador y tiene una gran influencia en SEO.
__Implicaciones importantes en SEO:__
1. Debe ser breve pero descriptivo.
2. No debe contener mas palabras clave de las necesarias.
3. Debe ser unico en cada pagina.
__Enlace a otros ficheros__
* El elemento < link> permite vincular hojas de estilo externas al documento HTML actual mediante su atributo href="#".

### Etiquetas basicas HTML

1. **Encabezados**: (< h1>....< h6>) son encabezados o sub encabezados. Elementos de bloque basicamente
2. **Parrafos**: < p> Se utiliza para encerrar parrafos de texto. Elemento de bloque
3. **Salto de linea**: < br> Permite hacer un salto de linea
4. **Separador de lineas**: < hr> Pone una linea horizontal divisoria.
5. **Enfasis**: < strong>, < em> estas etuiquetas se utilizan para dar enfasis o destacar un texto 
6. **Contenedor en lineas**: < span> se usa para agrupar pequenas partes del texto o contenido dentro de una linea

* Ruta Absoluta: Es una direccion completa, como una URL, que indica la ubicacion exacta de un archivo, sin importar en que carpeta estes. Ejemplo: https://www.ejemplo.com/images/logo.png o /imagenes/logo.png (desde la raiz del servidor).

* Ruta Relativa: Es una direccion que depende de la ubicacion actual de tu archivo. Se utiliza para navegar entre carpetas dentro de tu proyecto. Ejemplo: ../imagenes/logo.png (sube un nivel y accede a la carpeta imagenes).

### Elementos semanticos HTML 5

Es la clave de saber usar HTML correctament. por ejemplo, < span> permite agrupar contenido en linea y < div> contenido en bloque.
El HTML semantico permite describir el contenido dandole un significado de forma correcta.

* Ejemplos de elementos semanticos HTML: < header>, < footer> , < article> , < section>
* Estos elemntos proporcionan informacion sobre el tipo de contenido que contienen.

### Formularios

Los formularios web nos sirven para interactuar con el usuario y para que este usuario pueda transmitirnos informacion.
__Cada uno de los controles de un formulario debe tener el atributo name, con el cual se idetnifica el dato que se quiere enviar__

#### Etiquetas de formularios 

| **Tag**   | **Descripcion**                                                                            | **Atributos comunes**                                                                                               |
|-----------|--------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| `<form>`  | Se utiliza para crear formularios que permiten al usuario crear datos.                     | `action`: define la URL donde se enviaran los datos. <br> `method`: especifica el metodo de envio de datos. <br> `target`: indica como se debe mostrar la respuesta al enviar el formulario. |

#### Etiquetas de formularios (Input)
| **Tag**   | **Descripcion**                                                                            | **Atributos comunes**                                                                                               |
|-----------|--------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| `<input>` | Se utiliza para crear diferentes tipos de campos interactivos.                             | `type`: define el tipo de entrada que se debe mostrar. <br> `id`: identificador unico para el campo. <br> `name`: nombre del campo de entrada. <br> `value`: valor predeterminado del campo de entrada. <br> `placeholder`: texto que aparece en el campo cuando esta vacio. <br> `required`: indica que el campo debe completarse antes de enviar el formulario. <br> `disabled`: desactiva el campo, evitando que el usuario interactue con el. <br> `readonly`: hace que el campo sea solo de lectura. |


## CSS

### ¿Qué es CSS?
CSS, que significa **Hojas de Estilo en Cascada** (Cascading Style Sheets), es un lenguaje que se utiliza para definir el diseño visual de las páginas web. Su principal objetivo es separar el contenido estructurado en HTML de su presentación, facilitando así el mantenimiento y la personalización del diseño.

---

### Evolución y propósito
Antes de la llegada de CSS, el diseño y la estructura de las páginas web se gestionaban directamente en HTML, lo que hacía que el código fuera más complicado y difícil de mantener. CSS se introdujo para solucionar este problema, permitiendo aplicar estilos de manera más eficiente y sin alterar el contenido.

---

### Ventajas y desventajas

**Ventajas:**
- Mejora la experiencia del usuario al permitir diseños más atractivos y dinámicos.
- Facilita la implementación de diseños responsivos para adaptarse a diferentes dispositivos.
- Reduce el tamaño del archivo HTML al separar el contenido del diseño.
- Permite la personalización rápida de estilos mediante el uso de variables CSS.
- Ofrece soporte para animaciones y transiciones, mejorando la interactividad.

**Desventajas:**
- Puede ser complicado de dominar cuando se trabaja con diseños complejos.
- La compatibilidad con navegadores antiguos puede requerir soluciones adicionales.
- Los errores en las hojas de estilo pueden ser difíciles de depurar.
- La cascada y la especificidad pueden generar conflictos entre reglas de estilo.
- Requiere un conocimiento avanzado para aprovechar al máximo sus capacidades.

---

### Formas de incluir CSS

1. **CSS en línea (inline):** Se aplica directamente en la etiqueta HTML mediante el atributo `style`.
   ```html 

   <-p style="color: green; text-align: center;">Texto centrado y verde<-/p>

2. __CSS interno:__ Se escribe dentro de la etiqueta ``<style>`` en la sección ``<head>`` del documento HTML.
   
<head>
    <style>
        p {
            color: blue;
            font-size: 16px;
        }
    </style>
</head>

1. __CSS externo:__ Se guarda en un archivo separado con extensión .css y se enlaza al documento HTML mediante la etiqueta ``<link>``

<head>
    <link rel="stylesheet" href="estilos.css">
</head>

### Prioridad en CSS

Cuando se aplican varios estilos a un mismo elemento, CSS sigue un orden de prioridad:

1. __Estilos en línea:__ Tienen la mayor prioridad.
2. **Estilos internos:** Se aplican si no hay estilos en línea.
3. __Estilos externos:__ Se aplican si no hay estilos internos ni en línea.
4. __Herencia:__ Algunos estilos se heredan de los elementos padres.
5. __Regla !important:__ Sobrescribe cualquier otro estilo, independientemente de su origen.

### Sintaxis CSS

CSS consta de:

__Selector:__ Indica a qué elementos se aplicará el estilo.

__Propiedades y valores:__ Definen el estilo que se aplicará.

Ejemplo:

p {
    color: red;
    font-size: 14px;
}

__Comentarios:__ Se utilizan para añadir notas en el código que no serán interpretadas por el navegador.

/* Hola me llamo Izan N */

__Agrupación de selectores:__ Permite aplicar el mismo estilo a varios elementos.

h1, p {
    color: blue;
}

### Tipos de selectores

1. __Selector de elementos:__ Aplica estilos a todas las etiquetas de un tipo específico.

h1 {
    color: green;
}

2. __Selector de clase:__ Aplica estilos a elementos con una clase específica.

.titulo {
    font-weight: bold;
}

3. __Selector de ID:__ Aplica estilos a un elemento único identificado por un ID.

#principal {
    background-color: yellow;
}

### Selectores avanzados

1. __Selectores universales:__ Aplica un estilo a todos los elementos del documento.

* {
    margin: 0;
    padding: 0;
}

2. __Selector de atributos:__ Aplica estilos a elementos que contienen un atributo específico.

input[type="text"] {
    border: 1px solid black;
}

3. __Selector de hijos directos:__ Aplica estilos a los hijos inmediatos de un elemento.

div > p {
    color: red;
}

4. __Selector de descendientes:__ Aplica estilos a todos los elementos descendientes de un contenedor.

div p {
    font-size: 12px;
}

5. __Selector de hermanos adyacentes:__ Aplica estilos al elemento que sigue inmediatamente a otro.

h1 + p {
    margin-top: 10px;
}

6. __Pseudoclases:__

Las pseudoclases permiten aplicar estilos a elementos en un estado específico.

a:hover 
{
    color: green;
}

### Pseudoelementos

Los pseudoelementos permiten aplicar estilos a partes específicas de un elemento sin necesidad de modificar el contenido HTML. Se identifican con dos puntos dobles `::` seguidos del nombre del pseudoelemento.

---

#### Ejemplos de pseudoelementos:

1. **`::first-letter`**  
   Aplica estilos a la primera letra de un elemento.

   p::first-letter {
       font-size: 200%;
       color: blue;
       font-weight: bold;
   }

## FLEXBOX

### Introducción

**Flexbox** Flexbox (o "Modelo de Caja Flexible") es una herramienta de diseño en CSS pensada para organizar elementos dentro de un contenedor de manera más ágil y dinámica. Su principal ventaja es que se adapta fácilmente a distintos tamaños de pantalla, lo que lo convierte en una excelente opción para construir interfaces modernas y responsivas.

Antes de que existiera Flexbox, los desarrolladores web solían apoyarse en métodos como float o inline-block, que requerían más esfuerzo y trucos para lograr diseños complejos. Con Flexbox, todo ese proceso se vuelve mucho más sencillo, ya que ofrece un sistema claro para controlar la alineación, el espacio entre elementos y su distribución en el contenedor.

---

### Conceptos clave

1. **Contenedor:**  
   Es el elemento padre que contiene los elementos flexibles. Para activar Flexbox, se utiliza la propiedad `display: flex;`.

2. **Ítems:**  
   Son los elementos hijos directos del contenedor. Estos se alinean y distribuyen según las propiedades definidas en el contenedor.

3. **Eje principal:**  
   Es la dirección principal en la que se distribuyen los ítems. Por defecto, es horizontal (de izquierda a derecha).

4. **Eje secundario:**  
   Es perpendicular al eje principal. Si el eje principal es horizontal, el eje secundario será vertical.

---

### Propiedades del contenedor

El contenedor Flexbox tiene varias propiedades que controlan cómo se distribuyen y alinean los ítems:

1. **`display: flex;`**  
   Activa el modelo Flexbox en el contenedor.

2. **`flex-direction`**  
   Define la dirección del eje principal.  
   Valores:
   - `row` (por defecto): Los ítems se alinean en una fila horizontal.
   - `row-reverse`: Los ítems se alinean en una fila horizontal, pero en orden inverso.
   - `column`: Los ítems se alinean en una columna vertical.
   - `column-reverse`: Los ítems se alinean en una columna vertical, pero en orden inverso.

   ```css
   .contenedor {
       display: flex;
       flex-direction: row;
   }
   ```

   3. __`justify-content`__
Controla la alineación de los ítems a lo largo del eje principal.
Valores:

__`flex-start` (por defecto):__ Los ítems se alinean al inicio.
__`flex-end`:__ Los ítems se alinean al final.
__`center`:__ Los ítems se centran.
__`space-between`:__ Espacio igual entre los ítems.
__`space-around`:__ Espacio igual alrededor de los ítems.

.contenedor {
    justify-content: center;
}

4. __`align-items`__
Controla la alineación de los ítems a lo largo del eje secundario.
Valores:

__`stretch` (por defecto):__ Los ítems se estiran para llenar el contenedor.
__`flex-start`:__ Los ítems se alinean al inicio.
__`flex-end`:__ Los ítems se alinean al final.
__`center`:__ Los ítems se centran.

.contenedor {
    align-items: flex-start;
}

5. __`flex-wrap`__
Define si los ítems deben ajustarse a una nueva línea cuando no caben en el contenedor.
Valores:

__`nowrap` (por defecto):__ Los ítems no se ajustan.
__`wrap`:__ Los ítems se ajustan a una nueva línea.
__`wrap-reverse`:__ Los ítems se ajustan a una nueva línea en orden inverso.

.contenedor {
    flex-wrap: wrap;
}

6. __`align-content`__
Controla la alineación de las líneas cuando hay múltiples filas o columnas.
Valores:

__`stretch` (por defecto):__ Las líneas se estiran para llenar el espacio.
__`flex-start`:__ Las líneas se alinean al inicio.
__`flex-end`:__ Las líneas se alinean al final.
__`center`:__ Las líneas se centran.
__`space-between`:__ Espacio igual entre las líneas.
__`space-around`:__ Espacio igual alrededor de las líneas.

.contenedor {
    align-content: space-between;
}

### Propiedades de los ítems
Los ítems dentro de un contenedor Flexbox también tienen propiedades específicas:

1. __`order`__
Cambia el orden de los ítems. Por defecto, todos los ítems tienen un valor de 0.

.item {
    order: 1;
}

2. __`flex-grow`__
Define cuánto puede crecer un ítem en relación con los demás.

.item {
    flex-grow: 2;
}

3. __`flex-shrink`__
Define cuánto puede reducirse un ítem en relación con los demás.

.item {
    flex-shrink: 1;
}

4. __`flex-basis`__
Define el tamaño inicial de un ítem antes de que se distribuya el espacio restante.

.item {
    flex-basis: 100px;
}

5. __`align-self`__
Permite alinear un ítem de manera diferente al resto.
Valores:

__`auto` (por defecto):__ Hereda el valor de align-items.
__`flex-start`:__ Se alinea al inicio.
__`flex-end`:__ Se alinea al final.
__`center`:__ Se centra.
__`stretch`:__ Se estira.

.item {
    align-self: center;
}

Ejemplo práctico de Flexbox

A continuación, un ejemplo de cómo usar Flexbox para crear un diseño simple:

<div class="contenedor">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
</div>

.contenedor {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 200px;
    background-color: lightgray;
}

.item {
    width: 50px;
    height: 50px;
    background-color: blue;
    color: white;
    text-align: center;
    line-height: 50px;
}

## RESPONSIVE DESIGN

### Introducción

**Responsive Design** es una estrategia que permite que un sitio web se transforme visualmente según el dispositivo desde el que se accede. En lugar de crear versiones distintas para cada pantalla, se utiliza un solo diseño capaz de reorganizar y redimensionar los elementos para adaptarse a cualquier resolución. Esto garantiza que la web se vea bien y funcione correctamente tanto en una pantalla grande como en una pequeña, sin necesidad de hacer zoom o desplazarse en exceso.

---

### Características principales

1. **Flexibilidad y adaptabilidad:**  
   Los componentes del sitio, como el texto, las imágenes o los menús, se reorganizan y redimensionan de forma automática según el espacio disponible en la pantalla del dispositivo.

2. **Media Queries:**  
   Permiten aplicar estilos específicos según las características del dispositivo, como el ancho o la orientación de la pantalla.

3. **Rejillas fluidas:**  
   Utilizan porcentajes en lugar de valores fijos para definir el tamaño de los elementos, lo que facilita la adaptación a diferentes resoluciones.

4. **Imágenes y fuentes escalables:**  
   Garantizan que las imágenes y el texto mantengan su proporción y legibilidad en cualquier tamaño de pantalla.

---

### ¿Qué son las Media Queries?

Las __Media Queries__ en CSS permiten modificar los estilos dependiendo de las características del dispositivo o del tamaño de la ventana del navegador. Con ellas, es posible adaptar el diseño en función de aspectos como el ancho, alto, orientación de la pantalla o su resolución.

**Ventajas de las Media Queries:**
- Permiten personalizar el diseño para diferentes dispositivos.
- Mejoran la experiencia del usuario al adaptar el contenido automáticamente.
- Reducen la necesidad de crear múltiples versiones de una misma página.

**Desventajas de las Media Queries:**
- Pueden aumentar la complejidad del código CSS, especialmente en proyectos grandes.
- Requieren pruebas exhaustivas en diferentes dispositivos y navegadores para garantizar la compatibilidad.
- Si no se implementan correctamente, pueden generar inconsistencias en el diseño.
- Dependiendo del diseño, pueden aumentar el tiempo de carga al incluir múltiples estilos en un solo archivo CSS.

---

### Funcionamiento

Las Media Queries detectan las características del dispositivo y aplican los estilos definidos si se cumplen las condiciones especificadas.

**Sintaxis básica:**
```css
@media (condición) {
    /* Estilos aplicados si se cumple la condición */
}
```

**Ejemplos de uso de `@media` en diferentes dispositivos:**

1. **Pantallas grandes (escritorio):**
   ```css
   @media (min-width: 1024px) {
       body {
           background-color: lightblue;
       }
   }

2. __Móviles__:

    ```css
    @media (max-width: 480px) {
    body {
        background-color: lightyellow;
    }
    }
3. __tablets__:

 ```css
 
@media (max-width: 768px) {
    body {
        background-color: lightgreen;
    }
}
