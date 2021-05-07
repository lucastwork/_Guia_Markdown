_Guía_Markdown

![external-content.duckduckgo.com.png](md.png)

MarkDown es un lenguaje de marcado ligero usado para agregar elementos de formato a documentos de texto sin formato. **MarkDown**, es ahora uno de los lenguajes de marcado más populares del mundo. 

*Esta es mi guía personal de **MarkDown**, conceptos básicos y de uso cotidiano "nada complicado".*

> *Att: Luis A. Castillo UI/UX Designer.*

[Behance](https://www.behance.net/lucastwork)
[Linkedin](https://www.linkedin.com/in/lucastwork/)


# Sintaxis básica

## 1. Encabezados 
Puede utilizar hasta seis niveles escribiendo `#` al comienzo de una línea, el número de hashtags define la jerarquía del encabezado.

> `#` H1
> `##` H2
> `###` H3
> ....

## 2. Énfasis 
El énfasis (“cursiva”) y lo importante (“negrita”) se escriben poniendo `* o _` alrededor del texto que desea ver en un formato diferente.

>`**texto en negrita**`
**texto en negrita**
`*texto en cursiva*`
>*texto en cursiva*

## 3. Destacar
Puede usar signos de doble igual para ==destacar== texto:
`==Destacar texto==`

## Citas de texto
Escriba `>` más un espacio (como el correo electrónico):

```
> Bloque de textos citados
>> Texto citado dentro de una citación
```
# Listas

## 1. Listas numéricas
Escriba `1.` luego un espacio. Se puede utilizar cualquier número (seguido de un punto y un espacio) y los elementos de la lista se ordenarán desde 1 cuando se exporten.

>1. Lista ordenada
>2. Lista ordenada
>3. Lista ordenada

## 2. Listas con viñetas
Escriba `*`, `-` o `+` luego un espacio. Cree una lista con viñetas utilizando un asterisco (*), un guion (-) o un signo más (+), seguido de un espacio.

* Lista con viñeta
* Lista con viñeta

## 3. Listas de tareas
Escriba `-[ ]` o `1.[ ]` luego un espacio. Agregar un `x` entre corchetes marcará un elemento de la lista de tareas en la Vista previa.

>- [ ] Sin completar
>- [x] Completado

## 4. Listas anidadas
Puede anidar listas de varios niveles de profundidad y combinarlos:

````
* Primer nivel 
    * Segundo nivel

1. Primer nivel 
    1. Segundo nivel

* Primer nivel lista desordenada
    1. Segundo nivel lista  desordenada
````

# Avanzado

## 1. Enlaces
Cree un enlace rodeando el texto del enlace entre corchetes, seguido inmediatamente por la URL entre paréntesis:

```
[texto del link](http://ejemplo.com/)
```

## 2. Imágenes
Se admiten URL locales y web. Markdown utiliza la siguiente sintaxis para las imágenes:

```
![](http://ejemplo.com/imagen.jpg)
![](./imagen.jpg)
```
Nota: la sintaxis de la imagen de Markdown y las reglas de nombre de archivo de imagen HTML son diferentes de los bloques de contenido. Al usar imágenes locales, deben estar en una carpeta agregada como ubicación de biblioteca. 

## 3. Código 
Puede marcar el código en línea usando comillas invertidas `(``)`, o agregar un bloque de código agregando al menos cuatro espacios al comienzo de una línea:

> `` Esto es un bloque de código ``

Además, puede usar bloques de código cercado, que comienzan y terminan con comillas triples y no necesitan sangría. Tenga en cuenta que el formato en línea (como _underscores_) se ignora en el código.

```
Esto es un bloque de código múltiple
```

## 4. Notas de pie 
Agregue una nota al pie entre corchetes precedida por un signo de intercalación. Luego agregue el contenido de la nota al pie como un enlace de referencia, por ejemplo:

```
Texto con una nota de pie[^1].
…
[^1]: La nota de pie linkeada aparece al final del documento.
```
## 5. Tablas
Para hacer una tabla, use caracteres de barra vertical para denotar celdas. Comience con los encabezados de columna, sepárelos con una fila de celdas con guiones y luego agregue más filas de celdas. Por ejemplo:

```
|Header |Column 1 | Column 2 | Column 3  | 
|:--- |:---- |:----:| ----:|
|1. Row| is | is | is  |
|2. Row| left | nicely | right  |
|3. Row| aligned | centered | aligned  |
``` 
### La salida es la siguiente: 

|Header |Column 1 | Column 2 | Column 3  | 
|:--- |:---- |:----:| ----:|
|1. Row| is | is | is  |
|2. Row| left | nicely | right  |
|3. Row| aligned | centered | aligned  |  

Sin embargo, hay un truco que puede usar al escribir tablas Markdown con una fuente monoespaciada. Puede fingir el ancho de columna correcto agregando caracteres de espacio para alinear la tabla:

![table.png](table.png)

## 6. Separación de párrafos
Una línea que comienza con una pestaña indica un bloque de código. Debido a esto, actualmente no es posible usar una pestaña de retorno más para indicar un nuevo párrafo En su lugar, utilice dos retornos para separar párrafos.

>Cuando desee insertar una `<br />` etiqueta de ruptura con Markdown, finalice una línea con dos o más espacios y luego escriba return.

## 7. Reglas horizontales
Puede agregar un salto temático que estará representado por una línea divisoria `(<hr>)` cuando se exporta a HTML. Para hacerlo, agregue tres o más asteriscos `( *)`, guiones `( -)` o guiones bajos `( _)` en una línea por sí mismos, opcionalmente separados por espacios. Por ejemplo:

`---------------`

## 8. Saltos de pagina 
A veces, su documento no fluye exactamente como lo desea al imprimir o exportar a PDF. Puede forzar un salto de página utilizando tres signos más `( +)` en una línea por sí mismos:

`+++`
## 9. Comentarios 
Markdown no tiene una sintaxis oficial para los comentarios. Dado que HTML es completamente válido en Markdown, puede usar comentarios HTML en su lugar:

`<!-- Esto es un comentario -->`

## 10. Caracteres de formato de "escape"
Si desea escribir un carácter de formato y que Writer lo trate como texto, no como formato, escriba primero una barra invertida `\`. Este medio `\*`, `*`, `\_` , `_`, etc. Escapar no es necesario en los bloques de código.

# Editores de texto
La mejor manera de comenzar con Markdown es usarlo, eso es más fácil que nunca gracias a una variedad de herramientas gratuitas. Ni siquiera necesitas descargar nada, hay varios editores en línea que puede utilizar. [Dilinger](https://dillinger.io/) es uno de los mejores editores de Markdown en línea, solo entre al sitio y comience a escribir en el panel izquierdo, aparecerá una vista previa del documento renderizado en el panel derecho. 

*Algunas otras alternativas para Desktops incluyendo aplicaciones para cualquier sistema operativo puedes encontrarlas en la tienda [SnapStore](https://snapcraft.io/).*

> ## *"The end..."*
