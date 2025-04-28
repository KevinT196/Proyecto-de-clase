Proyecto Entrega #2
Kevin Andrés Toloza Silva 2241805
Fabián Andrés Remolina Mantilla 2241976
Documentación
En esta segunda versión del proyecto, hemos reemplazado la lista enlazada por un Árbol
Binario de Búsqueda (ABB) para mejorar la manera en que almacenamos y organizamos las
ciudades. Un árbol binario es una estructura en la que cada ciudad (nodo) se coloca en una
posición dependiendo de su nombre. Las ciudades se organizan de forma que, al ir hacia la
derecha de un nodo, los nombres de las ciudades son siempre más grandes alfabéticamente,
y al ir hacia la izquierda, los nombres son más pequeños. Esto hace que las búsquedas, la
adición de nuevas ciudades y la organización de la información sean mucho más rápidas y
eficientes. Por ejemplo, si queremos encontrar una ciudad específica, el tiempo que tardamos
en buscarla es mucho menor en el árbol que en una lista tradicional.
Además de las funciones que ya tenía el proyecto original, como agregar y buscar ciudades,
se ha añadido una nueva funcionalidad: la búsqueda por prefijo. Esta función permite buscar
todas las ciudades cuyo nombre empiece con un conjunto de caracteres específico. Por
ejemplo, si buscamos "Ciudad B", el sistema nos devolverá todas las ciudades que comienzan
con esa palabra, como "Ciudad B: Bucaramanga" y "Ciudad B: Floridablanca". Esta mejora
facilita la localización de grupos de ciudades que comparten un nombre similar, haciendo
que el sistema sea más flexible y útil.
En resumen, al cambiar de una lista enlazada a un árbol binario, hemos logrado una manera
más eficiente de gestionar y buscar la información, lo que mejora notablemente el
rendimiento del sistema.

