# Universidad de San Carlos de Guatemala
## Facultad de Ingeniería
## Introducción a la programación y computación 2
### Segundo Semestre

```js
Universidad San Carlos de Guatemala
Programador: Javier Andrés Monjes Solórzano 
Carné: 202100081
Correo:3020696740101@ingenieria.usac.edu.gt
Guatemala, Mixco 14/09/2023
```
## Este proyecto implica el diseño de una página de inicio de sesión utilizando Bootstrap, un marco de diseño popular que facilita la creación de sitios web con un aspecto profesional. Aquí hay una descripción general de los pasos que podrías seguir:

### **Instalación de Bootstrap:** Primero, necesitarás instalar Bootstrap en tu entorno de desarrollo. Esto generalmente implica descargar los archivos CSS y JS de Bootstrap e incluirlos en tu proyecto.

# **Guia de instalación de Bootstrap**
---
## **Paso 1: Descargar Bootstrap**

1.En su explorador busque el sitio web de [Bootstrap](https://getbootstrap.com/) y selecione el primer enlace.
<p align="center">
    <img src="new img/Proyecto nuevo.jpg">
</p>

o bien seleccione el siguiente enlance [Bootstrap](https://getbootstrap.com/)
<p align="center">
    <img src="new img/Proyecto nuevo (1).jpg">
</p>

2.Haga clic en el texto de [Download](https://getbootstrap.com/docs/4.5/getting-started/download/) para descargar Bootstrap.
<p align="center">
    <img src="new img/Proyecto nuevo (2).jpg">
</p>

3.Seleccione la versión que desea descargar y haga clic en botón de "Download".
<p align="center">
    <img src="new img/Proyecto nuevo (3).jpg">  
</p>
O bien, puede utilizar un CDN para cargar Bootstrap en su sitio web sin necesidad de descargar los archivos. 

Por ejemplo, puede utilizar el siguiente código para cargar Bootstrap desde un CDN de Google:

```HTML
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>

```
## **Paso 2: Incluir Boostrap en un Proyecto**
Si se optó por descargar los archivos proceda a:
>
>**Descomprime el archivo descargado**
   Una vez descargado, descomprima el archivo .zip. Dentro de la carpeta descomprimida, se encontraran tres carpetas: `css`, `js` y `fonts`.
>
>1. **Incorpora los archivos en tu proyecto**
   Copia las carpetas `css` y `js` en la carpeta de el proyecto.
>
>2. **Vincula los archivos de Bootstrap en tu HTML**
   En el archivo HTML donde quieras usar Bootstrap, necesitas vincular los archivos CSS y JS. Asegúrate de que los archivos estén correctamente vinculados en tu archivo HTML.
>
>Para el CSS, añade esto en la sección `<head>` de el HTML:
>   ```html
>   <link rel="stylesheet" href="ruta/a/bootstrap.min.css">
>   ```
>   Y para el JS, añade esto justo antes del cierre de la etiqueta `</body>`:
>   ```html
>   <script src="ruta/a/bootstrap.min.js"></script>
>   ```
>

Si se uso solamente el CDN, la incorporación de Boostrap estaría completa con la copia del codigo mencionado en la parte superior.

Adicionalmente se puede incluir boostrap mediante un paqute de gestión de dependencias como lo es `npm` o `Yarn` para posteriormente importarlo en el proyecto.
 Por ejemplo:
```
   npm install boostrap
```
```
   import 'bootstrap/dist/css/bootstrap.min.css';
   import 'bootstrap/dist/js/bootstrap.min.js';
```

**Paso 3: Utilizar Boostrap en un Proyecto**
   Luego de haber incluido los archivos necesarios de Boostrap en el proyecto trabajado, se puede comenzar a utilizar las clases y componentes de Boostrap en el `HTML`, `CSS` o `JavaScript`. Por ejemplo:

``` HTML
<!DOCTYPE html>
<html>
   <head>
      <!-- Incluye los archivos de Bootstrap aquí -->
   </head>
   <body>
      <button class="btn btn-primary">Botón de Ejemplo</button>
   </body>
</html>
```

Bootstrap proporciona una serie de propiedades y clases que puedes utilizar para personalizar el aspecto y el comportamiento de tus elementos. Algunas de las propiedades más relevantes incluyen:

- **Grid System:** Bootstrap utiliza un sistema de cuadrícula flexible que te permite crear diseños responsivos fácilmente. 
- **Clases de Estilos:** Bootstrap ofrece una amplia gama de clases de estilo que puedes aplicar a elementos HTML para darles formato de manera rápida. 
- **Componentes:** Bootstrap incluye una variedad de componentes predefinidos como barras de navegación, carruseles, modales, etc., que puedes personalizar y utilizar. 
- **Variables y Temas:** Puedes personalizar los colores, fuentes y otros aspectos visuales de Bootstrap utilizando variables CSS y temas. 
- **JavaScript:** Bootstrap incluye JavaScript para mejorar la funcionalidad de tus páginas web, como modales, botones desplegables y más.
- **Clases de Rejilla (Grid Classes):** Bootstrap ofrece un sistema de rejilla basado en clases como container, row, y col que te permiten crear diseños responsivos y flexibles para tus contenidos.
- **Clases de Tipografía:** Puedes utilizar clases como text-center, text-primary, text-muted, etc., para modificar la apariencia del texto y los elementos tipográficos.
- **Clases de Espaciado (Spacing Classes):** Bootstrap proporciona clases para ajustar el espaciado, como mb-3 (margin-bottom), mt-4 (margin-top), px-5 (padding-horizontal), etc.
- **Clases de Color:** Bootstrap incluye clases para cambiar el color de fondo y el texto, como bg-primary y text-white, que puedes aplicar a elementos como botones y encabezados.
- **Clases de Botones:** Puedes utilizar clases como btn, btn-primary, btn-danger, etc., para estilizar botones y crear diferentes estilos de botones.
- **Clases de Formularios:** Bootstrap ofrece clases para estilizar formularios y sus elementos, como form-control, form-group, input-group, entre otras.
- **Clases de Navegación:** Para crear barras de navegación y menús de navegación, puedes utilizar clases como navbar, navbar-expand-lg, nav, nav-item, nav-link, etc.
- **Componentes Personalizables:** Bootstrap permite personalizar componentes individuales, como modales, pestañas, alertas, y más, utilizando atributos y clases específicas para cada componente.
- **Clases de Visibilidad:** Puedes controlar la visibilidad de elementos en diferentes tamaños de pantalla utilizando clases como d-none y d-lg-block.
- **Clases de Ocultamiento y Muestra:** Bootstrap proporciona clases como hidden (ocultar) y visible para mostrar u ocultar elementos en función de las necesidades de diseño y dispositivos.
- **Clases de Desplazamiento (Scrollspy):** Para resaltar automáticamente los elementos de navegación a medida que se desplaza por la página, puedes utilizar clases de desplazamiento como data-spy="scroll" y data-target="#miNavegacion".
- **Clases de Responsividad:** Bootstrap incluye clases para mostrar u ocultar elementos en dispositivos específicos, como d-md-none (ocultar en dispositivos medianos), d-lg-block (mostrar en dispositivos grandes), etc.


Ejemplo de una página utilizando Bootstrap:
```HTML 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejemplo de Página con Bootstrap</title>
  <!-- Incluye los archivos de Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Encabezado de la página -->
  <header class="bg-primary text-white text-center py-3">
    <h1>Mi Página con Bootstrap</h1>
  </header>
  <!-- Contenido principal -->
  <section class="container my-5">
    <h2>Bienvenido a mi página</h2>
    <p>Esta es una página de ejemplo utilizando Bootstrap.</p>
    <button class="btn btn-primary">Botón de Ejemplo</button>
  </section>
  <!-- Pie de página -->
  <footer class="bg-dark text-white text-center py-3">
    &copy; 2023 Mi Página. Todos los derechos reservados.
  </footer>
  <!-- Incluye los archivos de JavaScript de Bootstrap al final del documento -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/js/bootstrap.min.js" integrity="sha384-wTf/cgx6G9l2Dj2TbDMfjqLtrtff9I/Cq8p/nzU5+WtTr0p5lPveLElXl1zshj1Pk" crossorigin="anonymous"></script>
</body>
</html>

```


# Login
---
## [Ver el Login Tradicional](https://github.com/javieer24/IPC2-Bootstrap)
<p align="center">
    <img src="IMG\Login Tradicional.png">
</p>  


