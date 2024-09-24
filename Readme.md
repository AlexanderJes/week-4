## Syntaxis 
- Como se puede establecer codigo css

```css
h1 {
    color: red;
}

...

- H1 : selector
- Color: propiedad
- Red: Valor

## Conceptos importantes css

- 4 conceptos importantes de css

## Selectores

- Indica a que elemnto o elementos, se aplicara estilos

``` Css
/* Selector etiqueta */

h1{ 
    Color: red;
}

/* selector de descendencia */

nav ul li a {
    color: red;
}

## Herencia (COLOS: INHERINT;)

- Elementos ancestros heredan algunas propiedades a sus descendientes



## Cascada

-significa que los estilos que llegan en ultimo lugar, sobreescriben a los de antes
-La especificidad, vence a la cascada.
## Especificidad

-Valor numererico que adquieren los selectores y se aplica cuando hay conflictos 

```HTML
/* Selector de etiqueta valor de especificidad(1) */
/* Selector de clase valor de especificidad(10) */
/* Selector de id valor de espeficidad 100 */
/* inline(Style) valor de specificidad(1000) */
/* important valor de especifidad infinito, no es bueno utilizar IMPORTANT, debido a que demuestra que tienes un conflicto*/
- Aprender de Memoria valores de especificidad
