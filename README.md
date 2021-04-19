# 12-04-2021-Deber-3-Listas-con-Arreglo
Creo una lista personalizada con memoria dinamica, uso de punteros dobles** y reserva de memoria con "malloc()"

La lista tiene las siguientes funciones.
AList* crearLista(int longitud);
int agregar(AList* lista, int* valor);
int agregarPos(AList* lista, int* valor, int pos);
int remover(AList* lista, int index);
int redimensionar(AList* list);
BOOLEAN contieneDato(AList* lista, int* dato);
void printAList(AList* lista);

printALista imprime todos los elementos de la lista.
