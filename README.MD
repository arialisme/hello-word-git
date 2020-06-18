# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Underlines

## Underline 1

# Underline 2

# Formatos de enfasis

- formato _italica_ de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold** o **strong.**
- formato ~~tachado~~, formato normal.

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes

![Logo Github](https://www.sferalabs.cc/wp-content/uploads/github-logo.png)

# Code Snippets

Código en JSON

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

Código en Javascript

```Javascript
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

export  $initHighlight;
```

# Tablas

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Elaimy | Arias    | 65857555  |
| Nene   | Gabi     | 00004444  |

# Citas

Esto es un texto referente a un cita que pondremos debajo:

> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.

> Esto es otra cita.

# Lineas divisoras

Esto es un texto que sera dividido por tres guiones medios .

---

Esto es otro texto dividido por tres asteriscos .

---

Esto es otro texto que sera dividido por tres guiones bajos.

---

# Saltos de lineas

Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.

- Se realiza con un enter entre cada parrafo
