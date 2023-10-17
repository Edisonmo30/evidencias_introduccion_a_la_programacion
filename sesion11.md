<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


**Actividad 11: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css**

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

* [Link Página](https://edisonmo30.github.io/Herbacea_Taller/)

**Index**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sitio web Herbacea</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="center-logo">
        <img class="logo"
            src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/logo.png?alt=media&token=b0dfcdd8-0b15-4608-8b76-0d1902572cef&_gl=1*1u76mxm*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkxOTg0Ni4zLjEuMTY5NTkyMTczNC4yNC4wLjA."
            alt="logoherbacea">
    </div>
    <h1>

        <div class="center-navegation">
            <a href="tienda.html">
                <h4>Tienda</h4>
            </a> <br />
            <a href="sobrenosotros.html">
                <h4>Sobre nosotros</h4>
            </a> <br />
            <a href="contacto.html">
                <h4>Contacto</h4>
            </a>
        </div>

    </h1>

    <br><br><br>
    <br><br><br>
    <br><br>

    <footer>
        Herbacea Colombia
        <br />
        <br />
        Medellín-Antioquia
        <br />
        <br />
        &copy;2023
    </footer>

</body>

</html>
```

**Contacto**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="center-logo">
        <img class="logo"
            src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/logo.png?alt=media&token=b0dfcdd8-0b15-4608-8b76-0d1902572cef&_gl=1*1u76mxm*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkxOTg0Ni4zLjEuMTY5NTkyMTczNC4yNC4wLjA."
            alt="logoherbacea">
    </div>

    <nav>
            <a href="index.html">Regresar</a>
    </nav>

    <h1>

        <div class="center-navegation">
            <a href="tienda.html">
                <h4>Tienda</h4>
            </a> <br />
            <a href="sobrenosotros.html">
                <h4>Sobre nosotros</h4>
            </a> <br />
            <a href="contacto.html">
                <h4>Contacto</h4>
            </a>
        </div>
    </h1>


        <main>
            <form class="aline">
                <label for="nombre">Nombre: </label>
                <input type="text" id="nombre"><br>
                <label for="email">Email: </label>
                <input type="email" id="email"><br>
                <label for="mensaje">Mensaje:</label>
                <textarea class="fijar" id="mensaje" rows="4" cols="50"></textarea>
            </form>
        </main>
        
        <br><br><br>

        <footer>
            Herbacea Colombia
            <br />
            <br />
            Medellín-Antioquia
            <br />
            <br />
            &copy;2023
        </footer>
</body>


</html>
```

**Sobre nosotros**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="center-logo">
        <img class="logo"
            src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/logo.png?alt=media&token=b0dfcdd8-0b15-4608-8b76-0d1902572cef&_gl=1*1u76mxm*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkxOTg0Ni4zLjEuMTY5NTkyMTczNC4yNC4wLjA."
            alt="Herbacea">
    </div>

    <nav>
        <a href="index.html">Regresar</a>
    </nav>

    <h1>
        <div class="center-navegation">
            <a href="tienda.html">
                <h4>Tienda</h4>
            </a> <br />
            <a href="sobrenosotros.html">
                <h4>Sobre nosotros</h4>
            </a> <br />
            <a href="contacto.html">
                <h4>Contacto</h4>
            </a>
        </div>
    </h1>

    <p class="text-aboutus"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto reiciendis laborum, sequi fuga consequuntur
        iure veritatis nemo illum facilis odio ab sit officiis accusantium, consequatur dolores. Labore impedit hic
        perspiciatis.
    </p>

    <br><br><br>

    <footer>
        Herbacea Colombia
        <br />
        <br />
        Medellín-Antioquia
        <br />
        <br />
        &copy;2023
    </footer>

</body>


</html>
```

**Tienda**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tienda</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="center-logo">
        <img class="logo"
            src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/logo.png?alt=media&token=b0dfcdd8-0b15-4608-8b76-0d1902572cef&_gl=1*1u76mxm*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkxOTg0Ni4zLjEuMTY5NTkyMTczNC4yNC4wLjA."
            alt="Herbacea">
    </div>

    <nav>
        <a href="index.html">Regresar</a>
    </nav>

    <h1>

        <div class="center-navegation">
            <a href="tienda.html">
                <h4>Tienda</h4>
            </a> <br />
            <a href="sobrenosotros.html">
                <h4>Sobre nosotros</h4>
            </a> <br />
            <a href="contacto.html">
                <h4>Contacto</h4>
            </a>
        </div>
    </h1>

    <br>
    <br>
    <br>
    <br>
    <br>

    <div class="gallery">
        <div class="row">
            <div class="column">
                <img class="vela-calma imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Vela%20calma.jpg?alt=media&token=570f5088-89fa-46fc-bd24-06af686c152d&_gl=1*vrauvh*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkyODIxNC40LjEuMTY5NTkyODIyOS40NS4wLjA."
                    alt="Vela calma">
                <P class="text-vela-calma">Vela calma</P>
            </div>

            <div class="column">
                <img class="vela-prosperidad imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Vela%20prosperidad.jpg?alt=media&token=f5c1407f-d104-45ca-abd9-7ed20d05d51b&_gl=1*1gw27hr*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkyODIxNC40LjEuMTY5NTkzMTcyNS4yOC4wLjA."
                    alt="Vela prosperidad">
                <P class="text-vela-prosperidad">Vela prosperidad</P>
            </div>

            <div class="column">
                <img class="vela-amor-propio imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Vela%20amor%20propio.jpg?alt=media&token=2a5d22da-7dbf-45e8-ba48-2d9dd56498f9&_gl=1*1173dvv*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkyODIxNC40LjEuMTY5NTkzMzA3Ni41MC4wLjA."
                    alt="Vela amor propio">
                <P class="text-vela-amor-propio">Vela amor propio</P>
            </div>
        </div>
    </div>

    <br>
    <br>
    <br>
    <br>
    <br>

    <div class="gallery">
        <div class="row">
            <div class="column">
                <img class="jabon-calendula imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Jab%C3%B3n%20cal%C3%A9ndula.jpg?alt=media&token=70012050-055f-4acc-a732-53658257b822&_gl=1*8vaa08*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkzNTIwNC41LjEuMTY5NTkzNTI4OC42MC4wLjA."
                    alt="jabon calendula">
                <P class="text-jabon-calendula">Jabón caléndula</P>
            </div>

            <div class="column">
                <img class="jabon-lavanda imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Jab%C3%B3n%20lavanda.jpg?alt=media&token=5410c1eb-61a9-4388-9d30-160a4f3d36d3&_gl=1*15reubp*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkzNTIwNC41LjEuMTY5NTkzNTMyNy4yMS4wLjA."
                    alt="jabon lavanda">
                <P class="text-jabon-calendula">Jaboón lavanda</P>
            </div>

            <div class="column">
                <img class="jabon-carbon-activado imgzoom"
                    src="https://firebasestorage.googleapis.com/v0/b/proyecto-edison.appspot.com/o/Jab%C3%B3n%20carb%C3%B3n%20activado.jpg?alt=media&token=428dbb68-5dae-46b3-b723-fe56b84dc073&_gl=1*1rildp1*_ga*MzU4NDkxNDc0LjE2OTQ3MjE5MDU.*_ga_CW55HF8NVT*MTY5NTkzNTIwNC41LjEuMTY5NTkzNTM1NC42MC4wLjA."
                    alt="jabon carbon activado">
                <P class="text-jabon-carbon-activado">Jabón carbón activado</P>
            </div>
        </div>
    </div>

    <br><br><br>
    
    <footer>
        Herbacea Colombia
        <br />
        <br />
        Medellín-Antioquia
        <br />
        <br />
        &copy;2023
    </footer>

</body>

</html>
```

**Estilos**

```css
.logo{
    width: 500px;
    height: 500px;
    padding: 0px;
    position: relative;
    display: inline-block;
    z-index: -1;
}

.center-logo{
    text-align: center;
    margin: -100px;
}

.center-navegation{
    text-align: center;
    display: flex;
    justify-content: center;
}

.center-navegation h4{
    padding: 15px;
    font-size: 25px;
    color: #D85B2D;
    margin: 20px;
    transition:background-colo 0.3s ease;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.center-navegation h4:hover{
    background-color: #d85b2d41;
    cursor: pointer;
}

.center-navegation a{
    text-decoration: none;
}

.vela-calma{
    width: 200px;
    height: 200px;
}

.text-vela-calma{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.vela-prosperidad{
    width: 200px;
    height: 200px;
}

.text-vela-prosperidad{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.vela-amor-propio{
    width: 200px;
    height: 200px;
}

.text-vela-amor-propio{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.gallery{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.row{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.column{
    text-align: center;
    margin-right: 150px;
}

.imgzoom{
    transition: transform 0.3s ease;
}

.imgzoom:hover{
    transform: scale(1.2);

}

.jabon-calendula{
    width: 200px;
    height: 200px;
}

.text-jabon-calendula{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.jabon-lavanda{
    width: 200px;
    height: 200px;
}

.text-jabon-lavanda{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

.jabon-carbon-activado{
    width: 200px;
    height: 200px;
}

.text-jabon-carbon-activado{
    color: #0B0C0C;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
}

body{
    max-width: 1200px;
    margin:0 auto;
    padding: 0 20px;

}


footer {
    color: black;
    padding: 20px;
    text-align: center;
    font-weight: lighter;
}

.aline{
    text-align: center;
}


.aline {
    margin: 0 auto;
    text-align: center;
    max-width: 400px;
    font-size: 25px;
    color: black;
    font-weight: lighter;
}


.aline label,
.aline input,
.aline textarea {
    display: block;
    margin: 10px 0;
    width: 100%;
}


.fijar{
    width: 500px;
    height: 200px;
    resize: none;
}

.text-aboutus{
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: 30vh;
    font-size: 20px;
    margin-inline: 400px;
    font-weight: lighter;
    text-align: justify;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}
```



