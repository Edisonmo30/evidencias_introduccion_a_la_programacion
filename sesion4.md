<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


**Crear una tabla HTML con información sobre productos.**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .texto {
        font-size: xx-large;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        text-align: left;
        color: black;
        background: linear-gradient(to left, rgb(10, 10, 10), rgb(153, 156, 156));
        padding: 40px;

    }

    .borde {
        border-color: rgb(12, 12, 12);

    }

    .encabezado {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size: xx-large;

    }

    .columna01 {
        font-family:fantasy;
        color: rgb(11, 11, 11);

    }

    .columna001 {
        font-family: cursive;
        color: rgb(11, 11, 11);

    }

    .columna02 {
        font-family:fantasy;
        color: rgb(11, 11, 11);

    }

    .columna002 {
        font-family: cursive;
        color: rgb(11, 11, 11);

    }

    .columna03 {
        font-family:fantasy;
        color: rgb(11, 11, 11);

    }

    .columna003 {
        font-family: cursive;
        color: rgb(11, 11, 11);

    }

    .columna04 {
        font-family:fantasy;
        color: rgb(11, 11, 11);

    }

    .columna004 {
        font-family: cursive;
        color: rgb(11, 11, 11);

    }
</style>

<body>
    <h4 class="texto">
        Consolas de videojuegos mas utilizadas
    </h4>

    <table class="borde" border="10" cellpadding="5" cellspacing="15">
        <thead>
            <tr class="encabezado">
                <th>Código</th>
                <th>Nombre</th>
                <th>Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2" class="columna01">0023</td>
                <td rowspan="2" class="columna01">PlayStation 5</td>
                <td class="columna001">El playStation 5 es una consola de videojuegos desarrollada por Sony. El PS5 presenta un hardware
                    potente que incluye una CPU y GPU de última generación, lo que permite gráficos de alta calidad y
                    tiempos de carga más rápidos.</td>
                <td>$3.800.000</td>
                <td>15</td>
                <td>12-22-2020</td>

            <tr>
                <td class="columna001">Además, el PS5 es compatible con una amplia gama de títulos de PlayStation 4 y presenta una
                    creciente
                    biblioteca de juegos exclusivos y multiplataforma. También admite resolución 4K y, en
                    algunos casos, hasta 8K, lo que permite una experiencia visual impresionante.</td>
                <td>100</td>

            </tr>
            </tr>

            <tr>
                <td rowspan="2" class="columna02">0014</td>
                <td rowspan="2" class="columna02">Xbox Series X</td>
                <td class="columna002">El Xbox Series X es una consola de videojuegos de última generación desarrollada por Microsoft.
                    Se destaca por su potencia y capacidad para ofrecer una experiencia de juego inmersiva. </td>
                <td>$2.999.000</td>
                <td>22</td>
                <td>10-11-2020</td>

            <tr>
                <td class="columna002">Cuenta con un hardware avanzado que incluye una CPU AMD Ryzen multicore y una GPU personalizada
                    basada
                    en la arquitectura RDNA 2, lo que permite gráficos de alta calidad y un rendimiento fluido a
                    resoluciones de hasta 4K y 120 fps en muchos juegos. </td>
                <td>75</td>

            </tr>
            </tr>
            <tr>
                <td rowspan="2" class="columna03">0037</td>
                <td rowspan="2" class="columna03">Steam Deck</td>
                <td class="columna003">La Steam Deck es una consola portátil de videojuegos desarrollada por Valve Corporation, la misma
                    empresa detrás de la plataforma de distribución de videojuegos Steam. Fue diseñada para permitir a
                    los usuarios jugar una amplia variedad de juegos de PC en un formato portátil. </td>
                <td>$2.100.000</td>
                <td>7</td>
                <td>25-02-2022</td>

            <tr>
                <td class="columna003">La Steam Deck cuenta con una pantalla táctil de alta resolución, controles integrados similares a
                    los de un controlador de consola tradicional, un procesador personalizado AMD, opciones de
                    almacenamiento en diferentes capacidades y la capacidad de ejecutar sistemas operativos como SteamOS
                    o Windows, lo que brinda a los jugadores la flexibilidad de acceder a su biblioteca de juegos de
                    Steam y otras plataformas.</td>
                <td>75</td>
            </tr>

            <tr>
                <td rowspan="3" class="columna04">0194</td>
                <td rowspan="3" class="columna04">Nintendo 3DS</td>
                <td class="columna004">El Nintendo 3DS es una consola de videojuegos portátil desarrollada por Nintendo. Fue lanzada en
                    2011 como sucesora de la Nintendo DS. </td>
                <td>$1.476.000</td>
                <td>9</td>
                <td>26-02-2011</td>

            <tr>
                <td class="columna004">Una característica destacada del 3DS es su capacidad para mostrar efectos 3D sin necesidad de gafas
                    especiales, lo que brinda una experiencia de juego más inmersiva. Además de los juegos
                    tradicionales, el 3DS también ofrece funciones como conectividad en línea, cámara integrada,
                    controles de movimiento y compatibilidad con juegos de la Nintendo DS. </td>
                <td rowspan="2">100</td>
            </tr>

            <tr>
                <td class="columna004">A lo largo de su ciclo de vida, el 3DS recibió una variedad de títulos populares y se convirtió en
                    una plataforma icónica en el mundo de los juegos portátiles.</td>
            </tr>
            </tr>
        </tbody>
    </table>
</body>

</html>
```






