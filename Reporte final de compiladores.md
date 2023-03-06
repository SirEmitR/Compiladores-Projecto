![[UAG.png]]

# MAREMI
## El compilador de ensueños

Mario Alberto Avelar Gutierrez
mario.avelar@edu.uag.mx
Jesus Emiliano Reyes Gomez
jesuse.reyes@edu.uag.mx

Av. Patria 1201 Col. Jardines del Valle
CP. 45129
Zapopan, Jalisco.
a 2 de Febrero del 2023


## Contenido


## Introduccion

## Análisis

>"Recuerda: si lo puedes construir, lo puedes programar." - MAREMI

Después de analizar el mundo de los compiladores, IDE y herramientas de programación disponibles para principiantes, se ha identificado una falta de entornos gráficos atractivos y que se adapten a las tendencias actuales de los niños y jóvenes. A pesar de que muchos ofrecen una gran capacidad para escalar el código inicial, no todos lo hacen de manera intuitiva. Aquellos que no lo hacen de manera intuitiva, a menudo utilizan una forma tediosa que puede frustrar al usuario.

La forma más sencilla de acceder a una herramienta de programación es a través de la web. Se ha encontrado que existen muchas herramientas que ofrecen un IDE de escritorio pero que no ofrecen una solución web.

Por lo tanto, se ha creado un compilador de ensueño: una solución web con una interfaz gráfica atractiva que se adapta a las tendencias del siglo XXI, basada en el popular videojuego "Minecraft". Esta solución proporciona una interfaz de entrada de texto con salidas tanto gráficas como de texto, lo que permite al usuario adentrarse en un ambiente más real en el mundo de la programación.

Además, contará con herramientas de apoyo para orientar al usuario basado en un paradigma de programación orientada a objetos, con una sintaxis sencilla en español. Por ejemplo, la sintaxis utilizada en esta solución será:

``` rdc
materiales <vacio>

material MiMadera <madera>  8

material MiPiedra <piedra> 3

material MiCemento <cemento> 10

materiales.agregar <MiMadera>

materiales.agregar <MiPiedra>

materiales.agregar <MiCemento>

casa MiCasa <materiales>

mientras MiCasa.contruir <mansion> -> mensaje <'En construccion'>

si MiCasa.contruida -> mensaje <'Felicidades por tu casa'>

si MiCasa.insuficiente -> mensaje <'Materiales insuficientes'>
```

## Diseño

