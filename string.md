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
- Formatear con 2 digitos despues del punto decimal
```
>>>precio=7.5
>>>piva=precio*1.09
>>>print("Precio Base:{:.2f} - Con IVA :{:.2f}".format(precio, piva)
'Precio Base:7.50 - Con IVA :8.18'
```
##Operaciones de cadena

`{: .2f}` significa que lo formatearías como un número flotante, con dos dígitos después del punto decimal.

`{:> 3.2f}`  alinearía el texto tres espacios a la derecha, además de especificar un número flotante con dos lugares decimales.

`len (cadena)` Devuelve la longitud de la cadena para el carácter de la cadena Itera sobre cada carácter de la cadena

`if` subcadena en cadena Comprueba si la subcadena es parte de la cadena

`cadena[i]` Accede al carácter en el índice i de la cadena, comenzando en cero.

`cadena[i:j]` Accede a la subcadena comenzando en el índice i, terminando en el índice j-1. Si se omite i, es 0 por defecto. Si se omite j, es len (cadena) por defecto.

##Métodos de cadena
`string.lower() / string.upper()` Devuelve una copia de la cadena con todos los caracteres en minúsculas / mayúsculas.

`string.lstrip() / string.rstrip() / string.strip()` Devuelve una copia de la cadena sin espacios en blanco izquierda / derecha / izquierda o derecha.

`string.count(substring)` Devuelve el número de veces que la subcadena está presente en la cadena.

`string.isnumeric()` Devuelve True si solo hay caracteres numéricos en la cadena. Si no, devuelve False.

`string.isalpha()` Devuelve True si solo hay caracteres alfabéticos en la cadena. Si no, devuelve False.

`string.split() / string.split(delimitador)` Devuelve una lista de subcadenas que fueron separadas por espacios en blanco / delimitador.

`string.replace(old, new)` Devuelve una nueva cadena donde todas las apariciones de old han sido reemplazadas por nuevas.

`delimiter.join(lista de cadenas)` Devuelve una nueva cadena con todas las cadenas unidas por el delimitador. 



