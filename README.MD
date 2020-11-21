# Version del curso
Version actual v1.2.2
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

Underline 1
-----------
Underline 2
====

# Formatos de enphasis
- letra *italica* de la primera forma
- letra _italica_ de la segunda forma
- Formato **bold o strong** primera forma
- Formato __bold o strong__ segunda forma
- formato ~~tachado~~
- podemos usar *Italica*, **bold** o ~~Tachado~~ en la misma linea

# Listas

1. esto es un item de lista ordenada
2. esto es un item de lista ordenada
3. esto es un item de lista ordenada

- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada
# Links
- <a href="https://google.com">Esto es un link html</a>
- [Esto es un link en markdown](http://www.google.com)
- [esto es un link al index](index.html) 

# Imagen

![Logo github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
JavaScript
```JAVASCRIPT
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Ari      | 01225533  |
| Tomas  | Toms     | 02232100  |

# Citas
Este es una cita
> Esto es una cita

este ya no pertenece a la cita
> este es otra cita

# Lineas Divisoras
Este es la linea divisora

---
Este es otro texto dividido

***

Otro texto dividido

___

# Saltas de lineas
Este primer parrafo.

Segundo parrafo.