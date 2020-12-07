# proyecto-graficacion

El siguiente proyecto se trata de demostrar como funcionan los algoritmos de rotacion, traslacion y escalamiento haciendo demostraciones de su funcionalidad

# instalacion

clonar el repositorio y abrir el index.html

# algoritmos usado

se usaron los algoritmos para hacer traslacion, rotacion, y escalamiento, si no antes se tiene conciencia al 100% se de que se usaron los metetodos respectivos para crear las figuras y asi poder manipularlas con estros 3 algoritmos anteriores.

# algoritmo usados

# Algoritmo de llenado por difusion: 

El algoritmo de relleno en programas de dibujo, creado por S. Fazzini, requiere tres parámetros: un nodo inicial, un color para sustituir, y otro de relleno. El algoritmo rastrea todos los nodos que sean del color seleccionado, y a la vez contiguos entre sí y con el inicial, y los sustituye por el color de relleno.

Hay muchas maneras en las que el algoritmo de relleno por difusión puede ser estructurado, pero todas ellas hacen uso de tipos de datos tales como la cola o la pila, explícita o implícitamente. Una implementación del algoritmo de relleno por difusión basada en pilas se define de la siguiente manera (para un arreglo bidimensional):

Flood-fill (node, target-color, replacement-color):
1. Si el color de un node es distinto del que se pretende sustituir, se termina el algoritmo.
2. Asigna el color de node a replacement-color.
3. Se ejecuta de nuevo el algoritmo, usando el nodo situado a la izquierda del presente, y los mismos parámetros de color.
Se ejecuta de nuevo el algoritmo, usando el nodo situado a la derecha del presente, y los mismos parámetros de color.
Se ejecuta de nuevo el algoritmo, usando el nodo situado inmediatamente superior al presente, y los mismos parámetros de color.
Se ejecuta de nuevo el algoritmo, usando el nodo situado inmediatamente inferior al presente, y los mismos parámetros de color.
4. Fin del algoritmo.

Una implementación explícitamente basada en colas sería como sigue:

Flood-fill (node, target-color, replacement-color):
1. Asignar Q a una cola vacía.
2. Si el color de node no es target-color, retornar.
3. Agregar node al final de Q.
4. Para cada elemento n de Q:
5. Si el color de n es igual a target-color:
6. Asigna el color de n a replacement-color.
7. Si el color del nodo a la derecha de n es target-color, agregar ese nodo al final de Q.
Si el color del nodo a la izquierda de n es target-color, agregar ese nodo al final de Q.
Si el color del nodo arriba de n es target-color, agregar ese nodo al final de Q.
Si el color del nodo debajo de n es target-color, agregar ese nodo al final de Q.
8. Continuar el bucle hasta que Q quede vacía.
9. Retornar.


#Scanline Fill
El algoritmo puede acelerarse rellenando líneas. En lugar de introducir en la pila la coordenada de cada píxel potencial, se inspeccionan las líneas vecinas (anterior y siguiente) para encontrar segmentos adyacentes que puedan ser rellenados en un pase futuro. Se introducen en la pila las coordenadas de los segmentos de línea (ya sea su inicio o su final). En la mayoría de los casos este algoritmo es por lo menos más rápido en un orden de magnitud que el basado en cada pixel.


# Algoritmo de Bresenham
El Algoritmo de Bresenham es un método rápido para el trazado de líneas en dispositivos gráficos, cuya cualidad más apreciada es que solo realiza cálculos con enteros.

Se puede adaptar para rasterizar también circunferencias y curvas. Los ejes verticales muestran las posiciones de rastreo y los ejes horizontales identifican columnas de pixel.

Actualmente se usa el nombre de algoritmos de Bresenham a toda una familia de algoritmos basado en modificaciones o ampliaciones del original aquí descrito.


# pagina web de demostracion
https://app.netlify.com/sites/musing-wescoff-4123b5/overview


