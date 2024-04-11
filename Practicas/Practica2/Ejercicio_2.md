Analizar el siguiente código señalando declaraciones y aplicaciones de reglas, y su efecto.

```
p#normal {
    font-family: arial,helvetica;
    font-size: 11px;
    font-weight: bold;
}
*#destacado {
    border-style: solid;
    border-color: blue;
    border-width: 2px;
}
#distinto {
    background-color: #9EC7EB;
    color: red;
}
<p id="normal">Este es un párrafo</p>
<p id="destacado">Este es otro párrafo</p>
<table id="destacado"><tr><td>Esta es una tabla</td></tr></table>
<p id="distinto">Este es el último párrafo</p>
```

<p id="normal">Este es un párrafo</p>: Este párrafo tiene el ID "normal", por lo que se aplican las reglas de p#normal. El texto se mostrará con la fuente Arial o Helvetica, de tamaño 11 píxeles y en negrita.

<p id="destacado">Este es otro párrafo</p>: Este párrafo tiene el ID "destacado", por lo que se aplican las reglas de *#destacado. Tendrá un borde sólido azul de 2 píxeles de ancho.

<table id="destacado"><tr><td>Esta es una tabla</td></tr></table>: Esta tabla tiene el ID "destacado", por lo que también se aplican las reglas de *#destacado. Tendrá un borde sólido azul de 2 píxeles de ancho.

<p id="distinto">Este es el último párrafo</p>: Este párrafo tiene el ID "distinto", por lo que se aplican las reglas de #distinto. Tendrá un fondo azul claro y el texto será de color rojo.
