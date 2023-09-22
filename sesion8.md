<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


**Actividad 8: Aplicando estilos con selectores CSS**

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

* Encabezado ```<header>```
* Tres párrafos ```<p>```
* Una imagen ```<img>```
* Un pie de página ```<footer>```

Aplica los siguientes estilos usando selectores de etiqueta:

* Color rojo a los encabezados ```<h1>```
* Color azul a los párrafos ```<p>```
* Borde grueso negro a la imagen ```<img>```

Aplica los siguientes estilos usando seleccionadores de clase:

* Color verde a los elementos con la clase ".destacado"
* Tamaño de fuente grande a los elementos con la clase ".grande"
  
Aplica los siguientes estilos usando seleccionadores de ID:

* Color amarillo al elemento con ID "#principal"
* Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un ```<div>```
Centrar el contenido de la sección ```<section>```

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        #texto {
            color: rgb(8, 8, 8);
            font-size: medium;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            text-align: center;
            font-size: smaller;

        }

        body {
            font-family: Arial, sans-serif;
            background-color: rgb(251, 251, 251);
        }

        .Contenido {
            font-size:xx-large;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        header {
            background: linear-gradient(black, white);
            color: rgb(6, 6, 6);
            padding: 20px;
            text-align: center;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: large;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(1, 9, 6);
            font-size:x-large;
        }

        footer {
            background-color:#01040afb;
            color: white;
            padding: 20px;
            text-align: center;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
    </style>
</head>

<body>

    <header>
        <h1>Lenguajes de programación</h1>
        <h5 id="texto">Aprende sobre los cuatro lenguajes mas utilizados</h5>
    </header>

    <section>
        <h1 class="Contenido"><u>Contenido</u></h1>
    </section>

    <section>
        <h2><u>Python</u></h2>
        <h5>Click en la imagen para reproducir video explicativo</h5>
        <a href="lenguajes.html#py"><img src="Python.png" alt="Python" width="300" height="290"></a>
        <p> Es un lenguaje de programación general de alto nivel, que es fácil de aprender y usar. <br />
            Es popular para el desarrollo web, ciencia de datos e inteligencia artificial. <br />
            Tiene una sintaxis simple y concisa, que lo hace fácil de leer y escribir. <br />
            Cuenta con una gran biblioteca de módulos y paquetes, que lo hace muy versátil.</p>
    </section>

    <section>
        <h2><u>Java</u></h2>
        <h5>Click en la imagen para reproducir video explicativo</h5>
        <a href="lenguajes.html#j"><img src="Java.jpg" alt="Java" width="300" height="290"></a>
        <p> Es un lenguaje de programación orientado a objetos, que es robusto y portable. <br />
            Es popular para el desarrollo de aplicaciones web, móviles y de escritorio. <br />
            Es un lenguaje compilado, lo que lo hace rápido y eficiente. <br />
            Tiene una gran comunidad de desarrolladores, que lo hace muy bien documentado y respaldado.</p>
    </section>

    <section>
        <h2><u>Javascript</u></h2>
        <h5>Click en la imagen para reproducir video explicativo</h5>
        <a href="lenguajes.html#js"><img src="Java script.png" alt="Java" width="300" height="290"></a>
        <p> Es un lenguaje de programación interpretado, que es utilizado para el desarrollo de páginas web y
            aplicaciones web. <br />
            Es un lenguaje dinámico, lo que significa que no necesita ser compilado antes de ejecutarse. <br />
            Es un lenguaje de propósito general, que puede utilizarse para una amplia variedad de tareas. <br />
            Es muy popular para el desarrollo de aplicaciones web interactivas y juegos.</p>
    </section>

    <section>
        <h2><u>C/C++</u></h2>
        <h5>Click en la imagen para reproducir video explicativo</h5>
        <a href="lenguajes.html#c++"><img src="C++.png" alt="Java" width="300" height="290"></a>
        <p> Son lenguajes de programación de bajo nivel, que son rápidos y eficientes. <br />
            Son populares para el desarrollo de sistemas operativos, aplicaciones de escritorio y juegos. <br />
            Tienen un control directo sobre el hardware, lo que los hace ideales para tareas que requieren un
            rendimiento óptimo. <br />
            Son lenguajes complejos, que requieren un mayor nivel de experiencia para dominarlos.</p>
    </section>

    <footer>
        Edison Martinez Osorio
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>
</html>
```
