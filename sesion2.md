<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


**Actividad 2: Creando mi primer sitio web.**

**Index:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer sitio web</title>
</head>

<body>
    <center>
        <header>
            <hr>
            <u>
                <img src="https://practiline.pt/wp-content/uploads/2015/07/barra-negra-1024x356.jpg" alt="barra del header" width="1920" height="70">
                <p>Bienvenido a la página web de</p>
                <h1><span style="color:rgb(30, 94, 139);">Edison Martinez Osorio </span></h1>
                <video src="video1.mp4" controls width="500" height="400" autoplay loop muted></video>
                <hr>
            </u>
        </header>

        <nav>
            <strong>
                <p><a href="about.html">Acerca | </a>
                    <a href="contac.html">Contacto</a>

                </p>

            </strong>


        </nav>
        <main>
            <p>
                Bienvenido a mi primer sitio web <br> Aquí encontrarás información sobre mi.
            </p>
        </main>
        <footer>
            <p>
                <i>Copyright 2023 - Edison Martinez
            </p>
            <p>
                Edisonmartinez1035@gmail.com
            </p>
            </i>
        </footer>
    </center>

</body>

</html>
```

**About:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head>

<body>
    <center>

        <header>
            <h1>
               <span style="color: rgb(30, 94, 139);">Sobre nosotros</span> 
            </h1>
        </header>
        <hr>
        <section>
            <h2>
                Historia
            </h2>
            <p>

                ¡Hola! Mi nombre es Edison Martínez Osorio y tengo 27 años. Me encanta todo lo relacionado con la
                tecnología, desde los teléfonos inteligentes hasta las computadoras. <br>
                También soy un gran aficionado al deporte, me encanta ver y jugar fútbol y al fútbol sala. Uno de mis
                sueños más grandes es convertirme en un excelente programador.<br>
                Imagino crear programas y aplicaciones que ayuden a las personas y hagan la vida más fácil.<br>
                Aunque pueda parecer complicado, estoy emocionado por aprender y trabajar duro para lograrlo. Me
                encantaría desarrollar sitios web geniales, aplicaciones útiles y<br>
                tal vez incluso crear un videojuego divertido algún día.
                Sé que el camino para ser un gran programador puede ser desafiante, pero estoy dispuesto a estudiar,
                practicar <br>
                y mejorar mis habilidades. Con dedicación y esfuerzo, espero convertir mi pasión por la tecnología en
                una carrera emocionante y exitosa.

            </p>

            <article>
                <h3>
                    Misión y Visión
                </h3>
                <hr>
                <p>
                    <strong>Misión:</strong>Mi misión es convertirme en un programador excepcional, utilizando mi
                    profundo
                    amor por la tecnología y el deporte como motores de mi crecimiento. <br>
                    A través del aprendizaje constante, la dedicación y la práctica, buscaré adquirir las habilidades
                    necesarias para desarrollar aplicaciones y programas que resuelvan <br>
                    problemas reales. Trabajaré incansablemente para crear soluciones intuitivas y accesibles,
                    permitiendo que las personas aprovechen al máximo la tecnología en su día a día. <br><br>

                    <strong>Visión:</strong>En mi camino como Edison Martínez Osorio, tengo una visión clara y
                    emocionante.
                    Sueño con fusionar mi pasión por la tecnología y el deporte para crear un impacto <br>
                    positivo en el mundo. Visualizo un futuro donde mis habilidades como programador no solo me permitan
                    crear soluciones innovadoras, sino también inspirar a otros a aprovechar <br>
                    al máximo la tecnología para mejorar sus vidas. Quiero ser reconocido como un líder en el campo de
                    la
                    programación, uniendo la creatividad tecnológica con la vitalidad del deporte <br>
                    para construir un mundo más conectado y eficiente.
                </p>
                <hr>
            </article>
        </section>

        <nav>
            <a href="index.html">Inicio | </a>
            <a href="contac.html">Contacto</a>
        </nav>
    </center>

</body>

</html>
```

**Contact:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>

<body>
    <center>
        <header>
            <hr>
            <h1>
              <span  style="color:rgb(30, 94, 139);">Contacto </span>  
            </h1>
            <hr>
        </header>
        <nav><br><br>
            <a href="index.html">Inicio | </a>
            <a href="about.html">Acerca</a> <br><br><br>
        </nav>

        <main>
            <form>
                <label for="Nombre">Nombre: </label>
                <input type="text" id="nombre"><br>
                <label for="Email">Email: </label>
                <input type="Email" id="Email"><br>
                <label for="Mensaje">mensaje: </label>
                <textarea id="Mensaje"></textarea><br>
            </form>
        </main>
        <footer>
            <p>
                <i>
                Copyright 2023 - Edison Martinez Osorio
            </i>
            </p>
        </footer>
    </center>

</body>

</html>
```







