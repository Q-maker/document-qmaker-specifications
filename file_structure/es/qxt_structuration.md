# Cómo estructurar un archivo txt para contener preguntas y respuestas.
Los archivos txt de preguntas y respuestas están estructurados para contener una o varias secciones de preguntas y propuestas de respuestas.
¿Cómo estructurar una sección de preguntas y respuestas?
Aprendamos con el ejemplo; vea la sección de preguntas y respuestas a continuación:

```
Entre los siguientes animales,
¿Cuál de estos animales vive en el agua?
-Gato
-Perro
*Pez
-caballo
> Los peces son animales acuáticos que pueblan
mares, océanos, ríos, estanques y puntos de agua.
```

Con este ejemplo, podemos resaltar que:
   * Una sección siempre comienza con la redacción de la pregunta, se puede escribir en más de una línea.
     Sin embargo, no se acepta salto de línea (línea blanca correspondiente a dos líneas de retorno)
   * Las respuestas propuestas siguen la redacción de la pregunta y están organizadas de manera que:

            -Las proposiciones verdaderas están precedidas por un asterisco (*)

            -Las proposiciones falsas están precedidas por un guión (-)

            NB: Las propuestas también se pueden escribir en varias líneas (sin saltos de línea)
   * En la última posición, tenemos el comentario: debe ir precedido del símbolo (>) y también puede escribirse en varias líneas sin salto de línea (NB: escribir un comentario no es obligatorio)



Así es como se compone una sección de preguntas y respuestas.
Sin embargo, un cuestionario se compone de una a varias secciones de preguntas y respuestas. Para hacer esto, simplemente separe cada sección de preguntas y respuestas con un salto de línea;
entonces, debe regresar dos veces a la línea (aquellas que resultan en una línea vacía).
A continuación se muestra un ejemplo con un conjunto de dos (2) secciones de preguntas y respuestas. (Tenga en cuenta la línea vacía entre las dos secciones)

```
Entre los siguientes animales,
¿Cuál de estos animales vive en el agua?
-Gato
-Perro
*Pez
-caballo
> Los peces son animales acuáticos que pueblan
mares, océanos, ríos, estanques y puntos de agua.

¿Cuál de estos animales está volando?
*Paloma
-El perro
*El Cuervo
*El águila
> La paloma, el cuervo y el águila son pájaros voladores.
```

**Nota:**  
Incluso si la función de importación admite casi toda la codificación de archivos de texto, si encuentra algún problema de codificación, prefiera utilizar la codificación **UTF-8** para garantizar el mejor rendimiento.  

Preguntas? Ideas? ¿Necesitas aclarar? Contáctenos en nuestro correo electrónico: [qcmmakerapp@gmail.com](mailto:qcmmakerapp@gmail.com)
