1. ¿ Qué es CSS y para qué se usa?
CSS, o Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje de estilo utilizado para controlar la presentación visual de documentos HTML u XML. Se usa para definir el diseño, los colores, las fuentes y otros aspectos visuales de una página web.

2. CSS utiliza reglas para las declaraciones de estilo, ¿cómo funcionan?
Las reglas en CSS se componen de un selector y un bloque de declaraciones de estilo. El selector apunta a uno o varios elementos HTML a los que se aplicarán los estilos, y el bloque de declaraciones contiene las propiedades de estilo y sus valores que se aplicarán a esos elementos seleccionados.

3. ¿ Cuáles son las tres formas de dar estilo a un documento?
Las tres formas de dar estilo a un documento son:
- CSS Interno: Esto implica incluir estilos CSS dentro del mismo documento HTML utilizando la etiqueta <style>.
- CSS Externo: Consiste en definir estilos en un archivo separado con extensión .css y vincularlo al documento HTML utilizando la etiqueta <link>.
- CSS en línea: Se aplica directamente a un elemento HTML utilizando el atributo style.

4. ¿ Cuáles son los distintos tipos de selectores más utilizados? Ejemplifique cada uno.
Los distintos tipos de selectores más utilizados en CSS son:
- Selector de tipo: Selecciona elementos HTML por su tipo. Ejemplo: p selecciona todos los párrafos.
- Selector de clase: Selecciona elementos HTML por su atributo de clase. Ejemplo: .clase selecciona todos los elementos con la clase "clase".
- Selector de ID: Selecciona un elemento HTML por su atributo de ID único. Ejemplo: #id selecciona el elemento con el ID "id".

5. ¿ Qué es una pseudo-clase? Cuáles son las más utilizadas aplicadas a vínculos?
Una pseudo-clase es una palabra clave que se añade a los selectores para especificar un estado especial del elemento seleccionado. Las pseudo-clases más utilizadas aplicadas a vínculos son:
- :hover: Se aplica cuando el cursor se sitúa sobre el elemento.
- :active: Se aplica cuando el elemento está siendo activado, por ejemplo, cuando se hace clic en él.
- :visited: Se aplica a los enlaces que han sido visitados por el usuario.

6. ¿ Qué es la herencia?
La herencia en CSS se refiere a la capacidad de los elementos secundarios de recibir los estilos de sus elementos padres. Esto significa que si un elemento no tiene un estilo específico definido, heredará los estilos de su elemento padre.

7. ¿ En qué consiste el proceso denominado cascada?
El proceso denominado "cascada" en CSS se refiere a cómo se resuelven los conflictos entre diferentes reglas de estilo que se aplican a un mismo elemento. La cascada sigue un conjunto de reglas específicas para determinar qué estilo prevalecerá, basándose en la especificidad de los selectores y en el orden en que se aplican las reglas. Este proceso garantiza que los estilos se apliquen de manera coherente y predecible en una página web.