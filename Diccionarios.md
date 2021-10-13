# Diccionarios


Ejemplo de un diccionario:  `datos_usuario = {'Nombre': 'Laura', 'Edad': 27, 'Documento': 1003882, 'Direccion': 'Calle 123'}`


```
>>>datos_usuario = {'Nombre': 'Laura', 'Edad': 27, 'Documento': 1003882, 'Direccion': 'Calle 123'}
>>>print(datos_usuario)
{'Nombre': 'Laura', 'Edad': 27, 'Documento': 1003882, 'Direccion': 'Calle 123'}
>>>datos_usuario["Nombre"]
Laura
>>>"Edad" in datos_usuario
True
>>>datos_usuario["Edad"] = 28
>>>print(datos_usuario)
{'Nombre': 'Laura', 'Edad': 28, 'Documento': 1003882, 'Direccion': 'Calle 123'}
>>>datos_usuario["Genero"] = "femenino"
>>>print(datos_usuario)
{'Nombre': 'Laura', 'Edad': 28, 'Documento': 1003882, 'Direccion': 'Calle 123', 'Genero': 'femenino'}
>>>del datos_usuario["Direccion"]
>>>print(datos_usuario)
{'Nombre': 'Laura', 'Edad': 28, 'Documento': 1003882, 'Genero': 'femenino'}
```

## Iterando sobre diccionarios

```
>>>datos_usuario = {'Nombre': 'Laura', 'Edad': 27, 'Documento': 1003882, 'Direccion': 'Calle 123'}
>>> for llave in datos_usuario:
>>>    print(llave)
Nombre
Edad
Documento
Direccion

>>>for llave, dato in datos_usuario.items():
>>>   print(llave+", "+dato)
Nombre, Laura
Edad, 27
Documento, 1003882
Direccion, Calle 123

>>>for dato in datos_usuario.values():
>>>   print(dato)
Laura
27
1003882
Calle 123

>>>for dato in datos_usuario.keys():
>>>    print(dato)
Nombre
Edad
Documento
Direccion

```

## Cuantas veces una letra esta en una palabra

```
def cuenta_letras(texto):
   result = {}
   for letra in texto:
      if letra not in result:
         result[letra] = 0
      result += 1
   return result

>>> cuenta_letras("aaaa")
{"a":4}


```




#Dictionary Methods Cheat Sheet
##Definition

x = {key1:value1, key2:value2} 

##Operations

len(dictionary) - Returns the number of items in the dictionary

for key in dictionary - Iterates over each key in the dictionary

for key, value in dictionary.items() - Iterates over each key,value pair in the dictionary

if key in dictionary - Checks whether the key is in the dictionary

dictionary[key] - Accesses the item with key key of the dictionary

dictionary[key] = value - Sets the value associated with key

del dictionary[key] - Removes the item with key key from the dictionary

##Methods

dict.get(key, default) - Returns the element corresponding to key, or default if it's not present

dict.keys() - Returns a sequence containing the keys in the dictionary

dict.values() - Returns a sequence containing the values in the dictionary

dict.update(other_dictionary) - Updates the dictionary with the items coming from the other dictionary. Existing entries will be replaced; new entries will be added.

dict.clear() - Removes all the items of the dictionary
