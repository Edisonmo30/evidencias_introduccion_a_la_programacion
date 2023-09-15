<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


**Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5.**

**Index:**

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        .texto {
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
        <h5 class="texto">Aprende sobre los cuatro lenguajes mas utilizados</h5>
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
**Lenguajes:**

```html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        .texto {
            color: rgb(8, 8, 8);
            font-size: medium;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            text-align: center;
            font-size: smaller;

        }

        body {
            font-family: Arial, sans-serif;
        }

        .Contenido {
            font-size: xx-large;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        header {
            background: linear-gradient(black, white);
            color: rgb(10, 10, 10);
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
        }

        footer {
            background-color: #08150a;
            color: white;
            padding: 20px;
            text-align: center;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
    </style>
</head>

<body>

    <header id="header">
        <h1>Lenguajes de programación</h1>
        <h5 class="texto">Aprende sobre los cuatro lenguajes mas utilizados</h5>
    </header>
    <br />

    <nav>
        <a href="index.html">Regresar</a>
    </nav>
    <br />

    <section>
        <h2 id="py"><u>Python</u></h2>
        <video controls width="500" height="490">
            <source src="Qué es python.mp4" type="video/mp4">
        </video> <br /> <br />
        <h4>Audio explicativo</h4>
        <audio src="Audio python.mp3" controls>audio explicativo</audio>
    </section>

    <section>
        <h2 id="j"><u>Java</u></h2>
        <video controls width="500" height="490">
            <source src="Qué es Java.mp4" type="video/mp4">
        </video> <br /> <br />
        <h4>Audio explicativo</h4>
        <audio src="Audio Java.mp3" controls>audio explicativo</audio>
    </section>

    <section>
        <h2 id="js"><u>Javascript</u></h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/FuCiNVP88pc?si=cDydpxy8DXN3ZfHm"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <h4>Audio explicativo</h4>
        <audio src="Audio JS.mp3" controls>audio explicativo</audio>
    </section>

    <section>
        <h2 id="c++"><u>C/C++</u></h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/0NPFJ73Pmu0?si=QeV8ZTRqPh8O4V8W"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <h4>Audio explicativo</h4>
        <audio src="Audio C++.mp3" controls>audio explicativo</audio>
    </section>

    <br />
    <nav>
        <a href="lenguajes.html#header">Ir al incio de la página</a>
    </nav>
    <br />

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






