# Reorganización Semántica de una Página Web de Harry Potter
---

Este proyecto consiste en reorganizar una página web real del fandom de *Harry Potter y Animales Fantásticos* utilizando correctamente etiquetas semánticas de HTML5.

Escogí esta temática porque me gusta muchísimo *Harry Potter*. He visto las 8 películas varias veces y, aunque todavía no he leído los libros, conozco muy bien los personajes, diálogos, secuencias y gran parte de la historia del universo mágico.

También sabía que muchos de mis compañeros probablemente escogerían temas como Minecraft, Naruto o videojuegos populares, así que quise trabajar con algo que realmente me gusta y conozco bastante bien.

La idea principal fue tomar una página que ya funcionaba visualmente, pero que tenía problemas de organización semántica, y convertirla en una estructura más limpia y profesional.

Además, se aplicaron etiquetas de semántica textual como `strong`, `em`, `u`, `cite` y `abbr`.

---

## Tabla de contenido
---

|Número|Contenido|Descripción|
|---|---|---|
|1|Página Escogida|Página del fandom de Harry Potter|
|2|Estructura Semántica|Uso correcto de etiquetas HTML5|
|3|Semántica de Texto|Aplicación de etiquetas semánticas|
|4|Conclusiones|Reflexión sobre la reorganización|

---

## Uso
---

### Menú Principal
La página funciona mediante navegación interactiva usando enlaces y categorías principales como libros, películas, personajes, lugares y hechizos.

No requiere ingresar palabras, solamente interactuar con enlaces y secciones de navegación.

#### SubMenú
La navegación fue organizada siguiendo el estilo visual del ejemplo original de la página.


> [!NOTE]
> La página utiliza etiquetas semánticas modernas para mejorar organización y comprensión del contenido.

---

## Estructura del Proyecto
---

- Uso correcto de `nav`, `section`, `article`, `aside` y `footer`
- Corrección de errores de sintaxis HTML
- Organización más limpia y fácil de entender
- Aplicación de etiquetas semánticas de texto

### Carpetas y archivos importantes

|Archivo|Descripción|
|---|---|
|index.html|Página principal reorganizada|
|README.md|Documentación del proyecto|
|images/|Imágenes utilizadas en la página|

> [!NOTE]
> El proyecto contiene archivos `.html`, imágenes y documentación de enlaces exteriores.

> [!WARNING]
> Algunas imágenes originales provenían de enlaces externos y podrían dejar de funcionar con el tiempo.

---

## Funcionalidades
---

- Reorganización semántica de contenido
- Corrección de estructura HTML
- Aplicación de etiquetas de texto semánticas
- Mejor jerarquía de títulos
- Navegación más organizada

---

## Página Escogida
---

Escogí una página del fandom de *Harry Potter y Animales Fantásticos Wiki* porque contiene muchísimo contenido real y eso la hacía perfecta para practicar semántica HTML.

La página tenía noticias, artículos, navegación, contenido lateral y diferentes tipos de texto, así que me permitió aplicar muchas etiquetas semánticas correctamente.

Además, como ya conozco bastante bien el universo de Harry Potter, me resultó mucho más fácil identificar personajes, referencias, películas y contenido importante dentro de la página.

---

## Etiquetas Semánticas Utilizadas
---

Durante el proyecto utilicé varias etiquetas semánticas tanto estructurales como de texto.

### Etiquetas estructurales utilizadas

|Etiqueta|Uso|
|---|---|
|`nav`|Menú principal de navegación|
|`section`|Separar contenido por temas|
|`article`|Contenido independiente o destacado|
|`aside`|Información secundaria y curiosidades|
|`footer`|Información final de la página|

---

### Etiquetas de texto utilizadas

|Etiqueta|Uso|
|---|---|
|`strong`|Dar importancia a texto importante|
|`em`|Dar énfasis al texto|
|`u`|Subrayar texto importante|
|`cite`|Mencionar títulos de obras o libros|
|`abbr`|Mostrar abreviaciones con significado completo|

---

## Cómo identifiqué cada parte semántica
---

Para identificar cada parte observé la función real que cumplía el contenido dentro de la página.

Inicialmente visualicé la página original usando la herramienta de inspeccionar elemento del navegador. Sin embargo, me pareció bastante confuso porque gran parte de la estructura estaba hecha solamente con etiquetas `div`, por lo que no lograba entender fácilmente cómo estaba organizada semánticamente la página original.

Debido a eso, decidí no basarme completamente en el código fuente original, sino más bien observar visualmente cómo estaba distribuido el contenido en la página y, a partir de eso, crear mi propia estructura semántica utilizando etiquetas HTML5.

Por ejemplo:

- `nav` → Lo utilicé para organizar el menú principal de navegación.
- `section` → Me ayudó a separar los diferentes temas y bloques de contenido.
- `article` → Lo usé para noticias y contenido destacado independiente.
- `aside` → Lo utilicé para curiosidades e información secundaria.
- `footer` → Se utilizó para la información final de la página.

También identifiqué partes del texto que necesitaban semántica especial:

- `strong` → Información importante.
- `em` → Énfasis.
- `u` → Resaltar advertencias importantes.
- `cite` → Títulos de obras.
- `abbr` → Abreviaciones.

De esta manera pude construir una estructura más organizada y fácil de entender, incluso sin depender completamente del código original de la página.

---

## Por qué usé cada etiqueta semántica importante
---

### `nav`
Se utilizó para agrupar todos los enlaces principales de navegación.

### `section`
Sirve para separar temas diferentes dentro de la página.

### `article`
Lo usé para noticias y contenido que puede entenderse de forma independiente.

### `aside`
Sirve para información complementaria que no es parte central de la página.

### `strong`
Lo utilicé para resaltar información importante como advertencias o nombres relevantes.

Ejemplo:
```html
<strong>prohibido</strong>
```

### `em`
Se utilizó para dar énfasis a títulos o nombres importantes.

Ejemplo:
```html
<em>Harry Potter y Animales Fantásticos Wiki</em>
```

### `u`
Lo utilicé para subrayar palabras importantes dentro de advertencias.

Ejemplo:
```html
<u>prohibido</u>
```

### `cite`
Lo utilicé para títulos de obras como libros, películas o videojuegos.

Ejemplos:
```html
<cite>La magia de MinaLima</cite>
```

```html
<cite>Harry Potter: regreso a Hogwarts</cite>
```

### `abbr`
Se usó para abreviaciones como:

```html
<abbr title="Joanne Kathleen">J. K.</abbr>
```

---

## Conclusiones
---

Este proyecto me ayudó a entender que HTML semántico no solamente se trata de que una página “se vea bien”, sino de que tenga significado y estructura correcta.

Aprendí a identificar cuándo una etiqueta se está usando correctamente y cuándo solamente se está usando por apariencia visual.

También entendí la importancia de organizar el contenido de una manera más profesional y estructurada.

Además, trabajar con una temática que realmente me gusta hizo que el proyecto fuera mucho más entretenido y fácil de desarrollar.

---

> Autor : Stefanny Estevez  
> [Github:](https://github.com/StefannyEstevezSolares/)

![Kirby](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdY6qFAEtUpVLXdsBj30hNfLklKXiwHFkxIA&s)
