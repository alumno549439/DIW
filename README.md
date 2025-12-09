# REPOSITORIO DE PRÁTICAS DEL MÓDULO DE DISEÑO DE INTERFACES WEB

## 🔗 [TAREA 1 - HTML](https://github.com/alumno549439/DIW/tree/c45ced6547a7c627210998289aa85a37020ad810/Tarea1HTML)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en crear una web sencilla
utilizando las etiquetas básicas de HTML como imágenes, enlaces, listas y tablas.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<h2>IMAGENES Y ENLACES</h2>
<p style="text-align: center;">
    <a href="https://lenguajehtml.com/html/" target="_blank">
        <img src="img/html5.png" width="100px">
    </a>
    <a href="https://lenguajecss.com/" target="_blank">
        <img src="img/css3.png" width="100px">
    </a>
</p>
<p style="text-align: center;">
    <a href="https://www.google.com/intl/es/chrome/" target="_blank">
        <img src="img/chrome.jpeg" width="90px">
    </a>
</p>
```

#### 💾 CAPTURAS
![Imagenes](https://github.com/alumno549439/DIW/blob/main/Tarea1HTML/img/Tarea1Imagenes.png?raw=true)
![Listas](https://github.com/alumno549439/DIW/blob/main/Tarea1HTML/img/Tarea1Listas.png?raw=true)
![Tablas](https://github.com/alumno549439/DIW/blob/main/Tarea1HTML/img/Tarea1Tablas.png?raw=true)

## 🔗[TAREA 2 - HTML](https://github.com/alumno549439/PCP/tree/93beba7e6a8bf4facfcfb85cc25d34f303006cab/Tarea2)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en diseñar un formulario de registro estructurado por bloques temáticos utilizando fieldsets y una amplia variedad de controles de entrada HTML y CSS básico.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<fieldset class="datospersonales">
    <legend>Datos Personales</legend>
    <p>
        <label for="nombre">Nombre:</label>
        <input type="text" name="nombre" placeholder="Insertar nombre"/> <!-- required placeholder: para hacer un campo obligatorio -->
        <label for="apellidos">Apellidos:</label>
        <input type="text" name="apellidos" placeholder="Insertar apellidos">
        <label for="email">Email:</label>
        <input type="text" name="email" placeholder="Correo electrónico">
    </p>
    ...

</fieldset>
```
> ... CSS ...
``` css
<style>
    ...

    .datospersonales {
        background-color: #9ffc89;
    }

    .otrosdatos {
        background-color: #add9e6;
    }

    .competencias {
        background-color: #ba73f3;
    }
</style>
```

#### 💾 CAPTURAS
![Captura](https://github.com/alumno549439/DIW/blob/main/Tarea2HTML/Tarea2HTML.png?raw=true)

## 🔗[TAREA 3 - HTML](https://github.com/alumno549439/DIW/tree/29653615555c868cbedd1b8a35a0e2f92ec1907e/Tarea3HTML)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en maquetar tablas complejas para horarios y comparativas utilizando atributos de fusión de celdas (colspan, rowspan) junto con selectores de ID y clase.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<table>
    <caption>HORARIO DE CLASE CURSO 2018-2019</caption>
    <thead>
        <tr>
            <th>HORAS</th>
            <th>Lunes</th>
            <th>Martes</th>
            <th>Miércoles</th>
            <th>Jueves</th>
            <th>Viernes</th>
        </tr>
    </thead>
    ...

</table>
```
>... CSS ...
```css
/* TABLA 1 */
caption {
    color: #649659;
}

thead th::first-letter {
    font-size: 2em;
}

#horario {
    background-color: green;
}
```

#### 💾 CAPTURAS
![Captura](https://github.com/alumno549439/DIW/blob/main/Tarea3HTML/img/Tarea3HTML.png?raw=true)

## 🔗[TAREA 4 - HTML](https://github.com/alumno549439/DIW/tree/29653615555c868cbedd1b8a35a0e2f92ec1907e/Tarea4HTML)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en demostrar los fundamentos de la maquetación y el posicionamiento web utilizando propiedades CSS como display, position, float, alineaciones (Flexbox) y columnas.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<section class="seccion">
    <h2>
    POSITION: static · relative · absolute · fixed · sticky · z-index
    </h2>
    <p class="pos-static">
    Este es un elemento con <code>position: static</code>.
    </p>
    <div class="pos-relativo">
    Contenedor relativo
    <div class="pos-absoluto">Elemento absoluto</div>
    </div>

    <div class="scroll-sticky">
    <div class="pos-sticky">Elemento sticky</div>
    <div class="scroll-contenido">
        Desplázate para ver el efecto sticky.
    </div>
    </div>
    ...
</section>
```
> ... CSS ...
```css
* {
    box-sizing: border-box;
}

:root {
  --alto-header: 60px; /* lo busqué, el doble guión define unas variables personalizadas */
  --ancho-maximo: 1000px;
  font-family: Arial, sans-serif;
}

body {
  margin: 0;
  background-color: #ffff99;
  color: #222;
  line-height: 1.5;
}

.header-fijo {
  position: fixed;
  top: 0; left: 0; right: 0;
  height: 60px;
  background: #182848;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 10;
}

.contenedor {
  width: 100%;
  padding-top: var(--alto-header);
}
```

#### 💾 CAPTURAS
![Captura 1](https://github.com/alumno549439/DIW/blob/main/Tarea4HTML/Tarea4primera.png?raw=true)
![Captura 2](https://github.com/alumno549439/DIW/blob/main/Tarea4HTML/Tarea4segunda.png?raw=true)
![Captura 3](https://github.com/alumno549439/DIW/blob/main/Tarea4HTML/Tarea4tercera.png?raw=true)

## 🔗[TAREA 5 - HTML](https://github.com/alumno549439/DIW/tree/29653615555c868cbedd1b8a35a0e2f92ec1907e/Tarea5HTML)
#### 📰 DESCRIPCIÓN:
Ejercicios prácticos orientados al dominio de la maquetación web, que comienza con la estructuración semántica de información mediante formularios y tablas complejas, y avanza hacia el control visual avanzado con CSS. El trabajo profundiza en las propiedades de posicionamiento, visualización y modelo de caja, culminando con una serie de implementaciones específicas con Flexbox para diseñar componentes de interfaz modernos como menús de navegación, galerías y catálogos de productos adaptables.

#### ⚡CODIGO
>A continuación, podemos ver ejemplos de los códigos implementados en esta tarea   


Ejercicio 1:

```html
<body>
    <header class="header">Flexbox</header>
    <nav class="flex">
        <li><a href="#">Enlace1</a></li>
        <li><a href="#">Enlace2</a></li>
        <li><a href="#">Enlace3</a></li>
        <li><a href="#">Enlace4</a></li>
    </nav>
</body>
```
> CSS

```css
.header {
    background-color: #333333;
    color: #d0d5d4;
    font-size: x-large;
    text-indent: 5px;
    padding: 10px;
}
...
```

#### 💾 CAPTURA
![Captura 1](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML1.png?raw=true)

Ejercicio 2:

```html
<body>
    <nav class="nav">
        Logo Home Products Services
        <p>
            <input type="text" placeholder="Search"></input>
            <input class="boton" type="submit" value="Go"></input>
        </p>
    </nav>
</body>
```
> CSS

```css
.nav {
    background-color: #008080;
    height: 40px;
    display: flex;
    justify-content: space-between;
    color: white;
    align-items: center;
    padding: 0 10px;
}

.boton {
    border-radius: 10px;
    border: none;
    width: 50px;
}
```
#### 💾 CAPTURA
![Captura 2](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML2.png?raw=true)

Ejercicio 3:

```html
<body>
    <header class="header">Flexbox: Catálogo de imágenes</header>
    <nav class="flex">
        <img src="/Tarea5HTML/img/edificios/1076-600x400.jpg">
        <img src="/Tarea5HTML/img/edificios/1081-600x400.jpg">
        <img src="/Tarea5HTML/img/edificios/743-600x400.jpg">
        <img src="/Tarea5HTML/img/edificios/870-600x400.jpg">
        <img src="/Tarea5HTML/img/edificios/945-600x400.jpg">
    </nav>
</body>
```
> CSS

```css
.header {
    background-color: #333333;
    color: #d0d5d4;
    font-size: x-large;
    text-indent: 5px;
    padding: 10px;
}

.flex {
    display: flex;
    justify-content: space-around;
    background-color: #cccccc;
    
}

.flex img {
    border: 1px solid #979797;
    width: 200px;
    padding: 15px 10px;
}
```
#### 💾 CAPTURA
![Captura 3](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML3.png?raw=true)

Ejercicio 4:

```html
<body>
    ...
        <div class="imagen-item">
            <img src="/Tarea5HTML/img/edificios/1076-600x400.jpg">
            <div class="info-content">
                <h2>Building 1</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore, quam quibusdam Delorum, modi tempore Necessitatibus eligendi perspiciatis excepturi in sequi, neque corrupti quos unde voluptates mollitia sint? Cumque, voluptatem. Delectus.</p>
            </div>
        </div>
    ...
</body>
```
> CSS

```css
...
.imagen-item {
    max-width: 200px;
    min-width: 180px;
    border: 3px solid #525252;
    display: flex;
    flex-direction: column;
}

.info-content {
    text-align: left;
    flex-grow: 1;
}

.info-content p {
    padding: 5px;
}
...
```
#### 💾 CAPTURA
![Captura 4](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML4.png?raw=true)

Ejercicio 5:

```html
<body>
    ...
        <div class="imagen-item">
            <img src="/Tarea5HTML/img/edificios/743-600x400.jpg">
            <div class="info-content">
                <h2>Building 3</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore, quam quibusdam Delorum, modi tempore Necessitatibus eligendi perspiciatis excepturi in sequi, neque corrupti quos unde voluptates mollitia sint? Cumque, voluptatem. Delectus.</p>
            </div>
        </div>
    ...
</body>
```
> CSS

```css
.imagen-item {
    max-width: 300px;
    min-width: 250px;
    border: 3px solid #525252;
    display: flex;
}

.imagen-item img {
    width: 40%;
}
.info-content {
    display: flex;
    flex-direction: column;

}

.info-content p {
    padding: 5px;
}

.info-content h2 {
    background-color: #979797;
    text-align: center;
    padding: 30px;
}
```
#### 💾 CAPTURA
![Captura 5](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML5.png?raw=true)

Ejercicio 6:

```html
<body>
    <h1 class="h1">Portfolio</h1>
    <div class="container">

        <div class="gallery-column">
            <img src="/Tarea5HTML/img/portfolio/1003-400x500.jpg">
            <img src="/Tarea5HTML/img/portfolio/1005-400x400.jpg">
        </div>
        ...
    </div>
</body>
```
> CSS

```css
.h1 {
    padding: 40px;
    text-align: center;
}

.container {
    display: flex; 
    gap: 15px; 
    max-width: 1200px;
    width: 100%;
    padding: 15px;
}

.gallery-column {
    flex: 1 1 200px;
    display: flex; 
    flex-direction: column;
    gap: 15px;
    justify-content: flex-start;
    min-width: 180px;
}

.gallery-column img {
    margin-left: 180px;
    width: 100%; 
    height: auto; 
    display: block;
}
```
#### 💾 CAPTURA
![Captura 6](https://github.com/alumno549439/DIW/blob/main/Tarea5HTML/img/Tarea5HTML6.png?raw=true)

## 🔗[TAREA 6 - HTML](https://github.com/alumno549439/DIW/tree/941080f53942e19143fa76e715d4e9fd973e7d45/Tarea6HTML)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en desarrollar mi catálogo musical responsivo (responsive) utilizando Flexbox para la estructura de rejilla y Media Queries para adaptar la visualización a dispositivos móviles, tablets y escritorio.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<body>
    ...
    <article class="song-card">
        <img src="https://cdn-images.dzcdn.net/images/cover/8382389d964d882e3652a44d0279b8d0/500x500-000000-80-0-0.jpg" class="song-cover"/>
        <h2 class="song-title">Orbit</h2>
        <p class="song-artist">Christopher</p>
        <a href="#" class="btn-lyrics">Ver letra</a>
    </article>
    ...
</body>
```
> CSS

```css
.song-card {
                background-color: rgba(255, 255, 255, 0.1); 
                border-radius: 10px;
                padding: 15px;
                text-align: center;
                width: 90%;
                min-height: 350px;
                flex-shrink: 0; 
                display: flex;
                flex-direction: column;
                justify-content: space-between; 
                align-items: center;
            }
```

#### 💾 CAPTURAS
![Captura](https://github.com/alumno549439/DIW/blob/main/Tarea6HTML/Tarea6HTML.png?raw=true)

## 🔗[TAREA 1 - SASS](https://github.com/alumno549439/DIW/tree/941080f53942e19143fa76e715d4e9fd973e7d45/Tarea1SASS)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en generar hojas de estilo dinámicas y modulares utilizando el preprocesador SASS, empleando variables, anidamiento y bucles (@for) para la asignación automatizada de colores.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<body>
    ...
    <nav>
        <ul>
            <li class="active">
            <a>Inicio</a>
            </li>
            <li>
            <a>Productos</a>
            </li>
            <li>
            <a>Clientes</a>
            </li>
            <li>
            <a>Sobre nosotros</a>
            </li>
        </ul>
    </nav>
    ...
</body>
```
> SCSS
```scss
// Colores menú
$navbar-background-color: #84b736;
$navbar-color-hover: $color-background;
...
nav {
    background-color: $navbar-background-color;
    padding: 0.2rem;

    ul {
        li {
            display: inline-block;
            padding-left: 1rem;
            padding-right: 1rem;

            &.active {
                color: $navbar-color-hover;
                font-weight: bolder;
            }
            ...
        }
    }
}
...
```
#### 💾 CAPTURA
![Captura](https://github.com/alumno549439/DIW/blob/main/Tarea1SASS/img/Tarea1SASS.png?raw=true)

## 🔗[TAREA 2 - SASS](https://github.com/alumno549439/DIW/tree/941080f53942e19143fa76e715d4e9fd973e7d45/Tarea2SASS)
#### 📰 DESCRIPCIÓN:
Ejercicio práctico que consiste en maquetar una landing page corporativa completa integrando CSS Grid y Flexbox para el diseño de estructuras complejas (formularios, rejillas de equipo y footers) y organizando los estilos mediante SASS.

#### ⚡CODIGO
>A continuación, podemos ver un ejemplo del código implementado en esta tarea:

```html
<body>
    ...
    <section class="services">
      <h3>
        Bufete de abogados trilingüe:<br />
        alemán, español e inglés
      </h3>
      <p>
        Confíe en nuestra experiencia para un asesoramiento jurídico que<br />
        obtenga resultados y cubra de forma integral sus preocupaciones<br />
        legales en los tres idiomas.
      </p>
      <a href="#" class="boton secundario">CONOCE A NUESTRO EQUIPO</a>
    </section>
    ...
</body>
```
> SCSS
```scss
// Colores menú
$navbar-background-color: #84b736;
$navbar-color-hover: $color-background;
...
.services {
  text-align: center;
  background: url("../assets/img/techo-cristal.jpg") center/cover no-repeat;
  position: relative;
  color: $blanco;
  padding: 100px;

  h3 {
    font-size: 40px;

  }

  p {
    margin: 20px auto;
  }

}
...
```
#### 💾 CAPTURA
![Captura](https://github.com/alumno549439/DIW/blob/main/Tarea2SASS/assets/img/Tarea2SASS.png?raw=true)