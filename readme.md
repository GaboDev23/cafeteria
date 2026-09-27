# Cafetería Don Café

Proyecto web básico desarrollado únicamente con **HTML** para practicar la estructura y los elementos fundamentales de una página web.

La página representa una cafetería ficticia llamada **Cafetería Don Café** e incluye información sobre el negocio, menú, horarios, ubicación, redes sociales y formularios de contacto y preferencias.

## Objetivo

El objetivo de este proyecto es practicar los fundamentos de HTML mediante la creación de una página web completa y organizada.

Los principales conceptos utilizados son:

* Estructura de etiquetas HTML
* Estructura básica de una página web
* Encabezados
* Párrafos
* Listas
* Enlaces
* Imágenes
* Rutas relativas
* Formularios
* Inputs
* Labels
* Radio buttons
* Checkboxes
* Textarea
* Botones de envío

## Estructura del proyecto

```text
cafeteria-don-cafe/
│
├── index.html
│
├── README.md
│
└── imagenes/
    ├── don-cafe.png
    ├── cafe.png
    └── torta.png
```

## Funcionalidades

### Página principal

La página incluye una sección inicial con:

* Nombre de la cafetería
* Mensaje de bienvenida
* Imagen principal
* Información sobre el negocio

### Redes sociales

Incluye enlaces externos hacia:

* Facebook
* Twitter
* Instagram
* WhatsApp

Los enlaces se abren en una nueva pestaña utilizando:

```html
target="_blank"
```

### Menú

La página contiene un menú dividido en dos categorías.

#### Bebidas

* Café Espresso
* Café Latte
* Café Americano
* Café Mocha
* Café Capuchino
* Café Frappe

#### Comidas

* Torta de chocolate
* Torta de frutas
* Torta de queso
* Torta de vainilla
* Torta de limón

También se utilizan imágenes para representar algunos productos.

### Horarios

La página muestra los horarios de atención:

* Lunes a viernes: 8:00 AM - 8:00 PM
* Sábados: 9:00 AM - 6:00 PM
* Domingos: Cerrado

### Ubicación

Incluye una dirección ficticia de la cafetería y un enlace hacia Google Maps.

### Formulario de contacto

El formulario permite ingresar:

* Nombre
* Apellido
* Correo electrónico
* Número de teléfono
* Mensaje

Se utilizan distintos tipos de campos HTML:

```html
<input type="text">
<input type="email">
<input type="tel">
<textarea></textarea>
<input type="submit">
```

### Formulario de preferencias

También se incluye un formulario para conocer las preferencias del cliente.

Permite seleccionar una bebida favorita mediante botones de tipo:

```html
<input type="radio">
```

También permite seleccionar varios productos utilizando:

```html
<input type="checkbox">
```

Además, contiene un campo numérico para indicar cuántas veces el usuario ha visitado la cafetería:

```html
<input type="number">
```

## Tecnologías utilizadas

* HTML5

No se utilizó CSS ni JavaScript, ya que el objetivo del proyecto es practicar exclusivamente los fundamentos de HTML.

## Conceptos practicados

* `<!DOCTYPE html>`
* `<html>`
* `<head>`
* `<title>`
* `<body>`
* `<section>`
* `<h1>`
* `<h2>`
* `<h3>`
* `<p>`
* `<ul>`
* `<li>`
* `<a>`
* `<img>`
* `<form>`
* `<label>`
* `<input>`
* `<textarea>`

## Imágenes y rutas

Las imágenes utilizadas en el proyecto se almacenan dentro de la carpeta:

```text
imagenes/
```

Se utilizan rutas relativas para acceder a ellas.

Ejemplo:

```html
<img src="imagenes/cafe.png" alt="Café">
```

## Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir el archivo `index.html` con cualquier navegador web.

No es necesario instalar dependencias ni ejecutar ningún servidor.

## Estado del proyecto

Proyecto finalizado como práctica de HTML básico.

## Posibles mejoras futuras

Cuando se incorporen nuevos conocimientos, el proyecto podría ampliarse con:

* CSS para mejorar el diseño visual
* Diseño responsive
* Barra de navegación
* Tablas de precios
* Validaciones de formularios
* JavaScript para agregar interactividad
* Backend para procesar los formularios

## Autor

**Gabriel**

Proyecto realizado como parte del aprendizaje y práctica de desarrollo web con HTML.
