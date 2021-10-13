# Listas
## Operaciones con Listas

`lista.append("Chile")` 	Agrega "Chile" al final de la lista.

`lista.insert(0,"Chile")` 	Agrega "Chile" en el indice indicado (Es este caso al inicio)
				Si agregas un indice mayor al numero de elementos se agrega al final.

`lista.remove("Chile")` 	Elimina "Chile" de la lista, si "melon no esta en la lista da error.

`lista.pop(3)` 			Entrega el valor del indice y lo elimina de la lista.
				Si el indice no existe, muestra el ultimo elemento de la lista y lo elimina.

`lista[2] = "Chile"` 		Remplaza por "Chile" lo que se encuentre en el indice 2 (el tercer elemento)

`lista.sort()` 			Ordena los elementos de la lista.

`lista.reverse()` 		Entrega los elementos de atras hacia adelante.

`lista.clear()` 		Elimina todos los elementos de una lista.

`lista.copy()` 			Crea una copia de la lista.

`lista.extend(lista2)` 		Agrega todos los elementos de "lista2" a "lista".

## Compresion de Listas
Es el arte de realizar una tarea que normalmente requeriria avrias lineas en una sola. Ej:

Un programa que calcule los multiplos de 7 desde el 1 al 70.

```
multiplos=[]
for x in range(1,11):
  multiplos.append(x*7)
```

La misma tarea realizada en una sola linea seria:

```
multiplos = [ x*7 for x in range(1,11)]
```

Otro ejemplo, una lista que contenga todos los numeros divisibles por 3 entre 0 y 100:

```
multiplos = [x for x in range(101) if x % 3 == 0]
```
Una funcion que entregue una lista de todos los numeros impares entre 1 y "n":

```
def odd_numbers(n):
	return [x for x in range(n+1) if x % 2 != 0]
```
  
