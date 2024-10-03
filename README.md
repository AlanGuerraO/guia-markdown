# Qué es Markdown y el uso de sus etiquetas

## Índice
1. [Introducción](#introducción)
2. [Encabezados](#encabezados)
3. [Estilos de texto](#estilos-de-texto)
4. [Listas](#listas)
5. [Enlaces](#enlaces)
6. [Imágenes](#imágenes)
7. [Citas](#citas)
8. [Código](#código)
9. [Tablas](#tablas)
10. [Conclusión](#conclusión)

## Introducción
Markdown es un lenguaje de marcado ligero que se utiliza para dar formato a texto simple, convirtiéndolo en texto con formato (HTML) para la web. Su popularidad se debe a su simplicidad y legibilidad, tanto en el texto sin formato como en su versión formateada.

## Encabezados
Markdown permite crear encabezados de diferentes niveles. Los encabezados se crean utilizando el símbolo `#` seguido de un espacio antes del texto.

Ejemplo:
```markdown
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6
```

## Estilos de texto
Puedes dar formato a tu texto usando cursiva, negrita o subrayado. Para cursiva, se encierra el texto entre un solo asterisco `*` o guion bajo `_`. Para negrita, se usa doble asterisco `**` o doble guion bajo `__`. Para subrayado, se usa doble tilde `~~` alrededor del texto.

Ejemplo:
```markdown
*Cursiva* o _Cursiva_
**Negrita** o __Negrita__
~~Subrayado~~
```

## Listas
Se pueden crear listas ordenadas o desordenadas.

- Para listas desordenadas, se utiliza `-`, `+` o `*`.
- Para listas ordenadas, se numeran los elementos con `1.`, `2.`, etc.

Ejemplo:
```markdown
- Elemento 1
- Elemento 2
  - Sub-Elemento

1. Primer elemento
2. Segundo elemento
```

## Enlaces
Se pueden agregar enlaces utilizando corchetes y paréntesis.

Ejemplo:
```markdown
[Texto del enlace](https://ejemplo.com)
```

## Imágenes
Para agregar imágenes, se usa una sintaxis similar a la de los enlaces, pero con un signo de exclamación al inicio.

Ejemplo:
```markdown
Imagenes remotas:
![Texto alternativo](https://ruta-de-la-imagen.com/imagen.png)

Imagenes locales:
![Texto alternativo](img/nombre.png)
```

## Citas
Las citas se crean utilizando el símbolo `>` antes del texto.

Ejemplo:
```markdown
> Esta es una cita en Markdown.
```

## Código
Se puede resaltar código en línea o en bloques.

- Para resaltar código en línea, se usa una sola comilla invertida: ``` ` ```.
- Para bloques de código, se usa triple comilla invertida: ` ``` `

Código en linea
```markdown
    `Texto`
```

Código en bloque
```markdown
    ```Javascript
        funtion Saludo(){
            console.log("Hola");
        }
    ```
```

## Tablas
Las tablas en Markdown se crean con barras verticales (`|`) y guiones para separar el encabezado de la tabla de los datos.

Ejemplo:
```markdown
| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Dato 1       | Dato 2       |
```

## Conclusión
Markdown es una herramienta poderosa para escribir texto que se transforma fácilmente a HTML. Con una sintaxis simple, puedes agregar encabezados, listas, enlaces, imágenes y más.
