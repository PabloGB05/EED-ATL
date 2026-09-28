# Apuntes de Markdown

[Web de Markdown](https://markdownguide.offshoot.io/basic-syntax)

## Índice

- Cabeceras
- Párrafos
- Saltos de línea 
- Formato de texto
- Citas
- Listas
- etc

### Cabeceras:

Según el número de "#" que introduzcas, de 1 a 6, le das un distinto aumento de tamaño a un texto.

#### Ejemplo
    # Cabecera de nivel 1
    #### Cabecera de nivel 4

Poner siempre un espacio despues de "#" es una buena práctica y prevee errores. También ayuda añadir una línea vacía despues de una cabecera.

### Párrafos:

A la hora de crear párrafos usa una línea en blanco para separar una o más líneas de texto.

Es adecuado evitar poner espacios o tabular al principio de un párrafo a no ser que forme parte de una lista.

### Saltos de línea  

Para hacer un salto de línea o para crear una nueva, termina una línea con dos o más espacios y luego usa la tecla return.

También se puede poner `<br>` y cumple la misma función.

Una buena práctica es usar `<br>` en lugar de los espacios ya que es mas fácil de distinguir a simple vista.

También se puede usar "/" pero no es recomendable ya que no todas las aplicaciones Markdown lo reconocen.

### Formato de texto:

#### Negrita:

Para poner el texto en letra "negrita" puedes añadir "**" o "__" alrededor de la palabra o palabras que quieras resaltar.

#### Ejemplo

    **asteriscos**
    o
    __barra baja__

Las aplicaciones de Markdown no aceptan las "__" entre palabras, usa "**" en su lugar.

#### Ejemplo
    Si-> texto**en**negrita
    No-> texto__en__negrita

#### Cursiva:

Para poner el texto en letra cursiva puedes añadir "*" o "_" alrededor de la palabra o palabras que quieras cambiar a cursiva.

#### Ejemplo

    *asteriscos*
    _barra baja_

Las aplicaciones de Markdown no aceptan "_" entre palabras, usa "*" en su lugar.

#### Ejemplo
    Si-> texto*en*cursiva
    No-> texto_en_cursiva

#### Negrita y cursiva:

Para poner un texto tanto en negrita como en cursiva al mismo tiempo pon "***" o "___".

Al igual que las anteriores, no se debe usar "___" entre palabras.

### Citas:

Para crear una cita añade ">" delante de un párrafo. 

#### Se verá así:
>Esto es una cita de alguien.

Y para citar varios párrafos añade "<" en las líneas en blanco, así:

    >Cita uno
    >
    >Cita dos

También se puede anidar una cita a otra colocando">>" delante del párrafo que quieras anidar, así:

    >Cita
    >
    >>Cita anidada

Y así es como se ve:

>Cita
>
>>Cita anidada

Las citas se pueden mezclar con otros elementos como "#" o "-"

#### Ejemplo

    > #### Esto es una cabecera
    >
    > - Texto1
    > *cursiva* y **negrita**

### Listas:

Puedes organizar información en listas ordenadas y en listas desordenadas.

#### Listas ordenadas:

