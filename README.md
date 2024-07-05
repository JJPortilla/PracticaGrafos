VERSION FINAL 1.0.0
-   Practica de Implementación de estructura no lineal (Grafos) 
En la practica, se creo un pequeño programa similar a una aplicacion de red social basica.Usando grafos se
recreo una red de amigos de cada usuario creado, se creo un algoritmo que realiza recomendaciones de posibles amigos.

-User Estan los usuarios registrados.

-Clase NodeGraph Aquie se encuentra el Nodo del usuario con sus conexiones de amigos, en la que no debe haber amigos duplicados.

-Clase Graph Es la clase principal de la red, en esta clase se agregan los usuarios y sus conexiones con amigos creando asi la red. Esta clase no debe
tener usuarios duplicados por medio del uso de la coleccion SETs representamos todos los nodos, como ya sabemos los SETs no permite valores duplicados. 

-Clase RecommendationEngine Esta clase se encarga de analizar y recomendar a cualquier usuario posibles amigos, para lo cual esta clase evalua los 
gustos de la persona con los gustos de todos los nodos que tiene la Red. Para saber la Simulitud se calcula un promedio entre los gustos similares 
con los gustos totales entre la persona. Devolviendo asi un numero que depende de la similutud colocado para recomendar.  
