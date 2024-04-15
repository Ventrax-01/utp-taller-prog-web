# Descripción del Proyecto

Este es un ejemplo básico de una página HTML que utiliza diferentes elementos para mostrar contenido y funcionalidades variadas.

## Estructura del Código

El código HTML está estructurado de la siguiente manera:

- **`<!DOCTYPE html>`**: Declaración del tipo de documento.
- **`<html>`**: Elemento raíz del documento.
- **`<head>`**: Contiene metadatos y enlaces a recursos externos.
  - **`<title>`**: Define el título de la página.
- **`<body>`**: Contiene el contenido visible de la página.
  - **`<h1>`**: Encabezado principal que muestra el título principal.
  - **`<a>`**: Enlaces que llevan a páginas externas.
  - **`<img>`**: Imagen que se muestra en la página.
  - **`<br>`**: Salto de línea.
  - **`<center>`**: Centro del contenido.
    - **`<map>`**: Define un mapa de imagen para enlaces sensibles.
      - **`<area>`**: Define una región de un mapa de imagen.
    - **`<img>`**: Imagen con enlaces sensibles definidos por el mapa de imagen.
  - **`<table>`**: Tabla que muestra datos tabulares.
    - **`<tr>`**: Fila de la tabla.
      - **`<td>`**: Celda de la tabla.

## Funcionalidades Principales

- **Encabezados**: Se utiliza `<h1>` para mostrar un título principal.
- **Enlaces**: Se utilizan `<a>` para enlazar a páginas externas y para enviar correos electrónicos.
- **Imágenes**: Se utiliza `<img>` para mostrar una imagen, tanto como un enlace como parte de un mapa de imagen.
- **Mapa de Imagen**: Se utiliza `<map>` y `<area>` para definir enlaces sensibles en una imagen.
- **Tabla**: Se utiliza `<table>`, `<tr>` y `<td>` para mostrar datos en forma tabular.

## Atributos de los Elementos HTML

Los elementos HTML utilizados en este código hacen uso de varios atributos que proporcionan funcionalidades adicionales. A continuación, se detallan los atributos utilizados en cada elemento:

- **`<a>` (Enlace)**
  - `href`: Especifica la URL a la que enlaza el hipervínculo.
  - `target`: Especifica dónde abrir la URL vinculada (`_blank` abre la URL en una nueva ventana o pestaña del navegador).
  
- **`<img>` (Imagen)**
  - `src`: Especifica la ruta de la imagen.
  - `width`: Especifica el ancho de la imagen en píxeles.
  - `height`: Especifica la altura de la imagen en píxeles.
  - `usemap`: Especifica el nombre de un mapa de imagen que se utilizará con la imagen.
  
- **`<map>` (Mapa de Imagen)**
  - `name`: Especifica el nombre del mapa de imagen.
  
- **`<area>` (Área del Mapa de Imagen)**
  - `shape`: Especifica la forma de la región.
  - `coords`: Especifica las coordenadas de la región.
  - `href`: Especifica la URL a la que enlaza la región.
  - `target`: Especifica dónde abrir la URL vinculada (`_blank` abre la URL en una nueva ventana o pestaña del navegador).
  
- **`<br>` (Salto de línea)**
  - No tiene atributos específicos.

- **`<table>` (Tabla)**
  - `border`: Especifica el ancho del borde de la tabla (en píxeles o como valor booleano).
  
- **`<tr>` (Fila de la Tabla)**
  - No tiene atributos específicos.
  
- **`<td>` (Celda de la Tabla)**
  - No tiene atributos específicos.

Los atributos proporcionan información adicional y funcionalidades a los elementos HTML, lo que permite una mayor personalización y control sobre la apariencia y el comportamiento de la página web.
