<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


**Actividad 10: Propiedades de posicionamiento de CSS**

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.
   
Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```
Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

**Código modificado**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="div1">
        <div class="div2" style="background-color: black;">
        </div>

        <div class="div3" style="background-color: rgb(62, 62, 63);">
        </div>

        <div class="div4" style="background-color: rgb(144, 142, 146);">
        </div>

        <div class="div5" style="background-color:  black;">
        </div>

        <div class="div6" style="background-color: rgb(62, 62, 63);">
        </div>

        <div class="div7" style="background-color: rgb(144, 142, 146);">
        </div>

        <div class="div8" style="background-color: black;">
        </div>

        <div class="div9" style="background-color: rgb(62, 62, 63);">
        </div>

        <div class="div10" style="background-color: rgb(144, 142, 146);">
        </div>
        
    </div>
</body>
</html>
```

```css
.div1{
    background-color: rgb(197, 195, 191);
    height: 400px;
    width: 800px;
    top: 200px;
    left: 200px;
    z-index: 0;


}

.div2{
    height: 100px;
    width: 100px;
    position: relative;
    top: 20px;
    left: 20px;
    z-index: 1;
}

.div3{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 50px;
    left: 50px;
    z-index: 2;
   
}

.div4{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 80px;
    left: 60px;
    z-index: 3;
    
}

.div5{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: block;
    top: -80px;
    left: 35%;
    
    
}

.div6{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: block;
    top: -80px;
    left: 35%;
    
}

.div7{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: block;
    top: -80px;
    left: 35%;
    
}

.div8{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: inline-block;
    top: -380px;
    left: 60%;
    
}

.div9{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: inline-block;
    top: -380px;
    left: 60%;
}

.div10{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 20px;
    left: 20px;
    position: relative;
    display: inline-block;
    top: -380px;
    left: 60%;
    
}
```

**Preguntas:**
* ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

Position: relative, mediante este valor podemos posicionar un elemento respecto al flujo normal de la página. Se podría decir que estamos posicionando un elemento tomando como referencia el flujo normal (la posición por defecto) de dicho elemento. Podremos usar top, left, right y bottom para posicionar nuestro elemento tomando como referencia la posición por defecto del elemento.
Position: absolute,este valor también aceptará los valores top, left, right y bottom. El elemento con position: absolute no estará dentro del flujo normal de la página y tomará como referencia la ventana del navegador o el elemento posicionado (que tenga cualquier valor de position excepto static) más cercano si es padre del elemento que queremos posicionar.

* ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
  
Se utiliza para definir la posición vertical de elementos superpuestos. Un valor más alto de z-index coloca un elemento encima de otros con un valor menor.

* ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

La propiedad display en CSS no solo determina dónde se va a situar un elemento, también define cómo se va a comportar a nivel de bloque o línea, e incluso si se va a ver o no. Para entender este comportamiento primero debemos saber qué es el nivel de bloque y de línea.

Cada elemento de HTML tiene un valor display CSS por defecto. Los elementos de tipo div, encabezados, formularios, secciones o párrafos son elementos que tienen por defecto el valor block. Por otro lado, los elementos como span, cursiva, negrita, enlace e imagen tienen por defecto el valor inline. Estos valores afectarán la forma en la que se comporta el elemento en relación al viewport y a la línea de texto.

Además de estos valores, la propiedad display en CSS tiene muchas opciones. A continuación te presentamos las cuatro tipos de display css u opciones más importantes de esta propiedad: block (como un bloque), inline (en línea con el texto), inline-block y none (oculto).
