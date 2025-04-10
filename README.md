Clase Nodo
Esta clase representa un nodo individual de la lista enlazada. Cada nodo contiene dos propiedades:

$dato: almacena el valor o información del nodo.

$siguiente: almacena la referencia (puntero) al siguiente nodo en la lista. Se inicializa como null porque cuando se crea el nodo todavía no se conoce su sucesor.

El método constructor __construct($dato) se encarga de asignar el valor del dato y establecer que, inicialmente, el nodo no apunta a ningún otro ($siguiente = null).
Clase ListaEnlazada
Esta clase representa la lista enlazada completa. Tiene una sola propiedad:

$cabeza: es una referencia al primer nodo de la lista. Se inicializa como null, indicando que la lista está vacía al inicio.

El método constructor __construct() simplemente establece que al crearse una nueva lista enlazada, no contiene ningún nodo.
