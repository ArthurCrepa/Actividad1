#ACTIVIDAD1
---
---

En el presente repositorio se ha agregado el codigo fuente de "paint" 
recuperado de: http://www.grantjenks.com/docs/freegames/paint.html . En el código original, podemos dibujar líneas (presionando "l") y cuadrados (presionando "s"),
al mismo tiempo, somos capaces de seleccionar 4 colores siendo: *Negro (presionando "K") , Rojo (presionando "R"), Verde (presionando "G") y Azul (presionando "B").*

donde se nos ha pedido realizar lo siguiente:

1)Agregar un nuevo color
-
2)Dibujar un círculo
-
3)Completar el rectángulo
-
4)Completar el triángulo
-


Explicaciones
***
*Primer caso:* Para implementar el nuevo color que en este caso es el Purple, reulitizamos el codigo en la parte de onkey color y sustituimos un color 
por el Purple agregando al final la letra P para hacer llamado de esta nueva acción

*Segundo caso:* Implementamos el circle con la funcion que venia por default en la libreria de Turtle para mayor facilidad y al final
cambiamos el nombre de Circle a Circle_shape para poder llamar a realizar la función

*Tercer Caso:* Se reutilizó el código de square y se agregaron medidas "width" y "height" considerando la fórmula:
Perímetro = (2 x Base) + (2 x Altura). Se redujo la cantidad de veces que se repita el código de 4 a 2.
Este dibujará un rectángulo según dónde presione el usuario. Activamos esta figura seleccionando "r".

*Cuarto Caso:* Tomando en cuenta que podemos rotar nuestra flecha, se reutilizó el código de square, reduciendo la cantidad de veces que se repita el código de 4 a 3. 
Se ha aumentado el ángulo de rotación de 90° a 120° (considerando que la suma de los ángulos interiores de un triángulo debe ser igual a 180°). 
Se dibuja un triángulo equilátero del color seleccionado y según la distancia indicada por el usuario. Activamos esta figura seleccionando "t".

