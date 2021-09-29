# String

## Apuntes String

- Todo en mayusculas
```
>>>"hola".upper()
HOLA
```
- Todo en minusculas
```
>>>"HOLA".lower()
hola
```
- Eliminar espacios Ej(" yes ")

```
>>>" yes ".strip()
'yes'

>>>" yes ".lstrip()
'yes '

>>>" yes ".rstrip()
' yes'
```

- Contar caracteres
```
>>>"La e se repite 6 veces".count("e")
6
```
- Determinar si una cadena termina en una determinada subcadena
```
>>>"pineapple".endswitch("apple")
True
```
- Validar si una cadena es numerica
```
>>>"pineapple".isnumeric()
False
>>>"1234".isnumeric()
True
```
- Pasar una cadena numerica a variable numeros
```
>>>int("12345")
12345
```
- Pasar de una lista a cadena con un delimitador (Es esta caso "espacio")
```
>>>" ".join(["Esto", "esta", "unido", "con", "espacios"])
'Esto es una cadena con espacios'
```
- Pasar de una cadena a lista
```
>>>"Esto esta unido con espacios".split()
["Esto", "esta", "unido", "con", "espacios"]
```

## Formato de cadenas

```
>>>name=Hector
>>>print("Hola {name}, tu numero es el {number}".format(name=name, number=len(name)*3)
'Hola Hector, tu numero es el 35'

>>>name=Hector
>>>number=57
>>>print("Hola {name}, tu numero es el {number}".format(name, number)
'Hola Hector, tu numero es el 57'
```
