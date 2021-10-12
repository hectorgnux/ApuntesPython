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
```

# Para ver 
