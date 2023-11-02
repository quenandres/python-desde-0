# `Curso de PYTHON desde CERO (Completo)`

[https://www.youtube.com/watch?v=nKPbfIU442g](https://www.youtube.com/watch?v=nKPbfIU442g)

- Min 30 instalación
- Min 56 Datos compuestos



### `Conceptos basicos`
##### _Tipos de datos_
*Datos simples*
_String_
```py
"string" # String normales
'string' # String normales
"""string""" # String multilineas
'''string''' # String multilineas
```

*`Datos simples`*

*Strings*
```py
nombre = "Jhonatan"
bienvenida = "Hola "+nombre+ " ¿Como estas?"
```

*f Strings*
```py
nombre = "Jhonatan"
bienvenida = f"Hola {nombre} ¿Como estas?"
```

*del*
```py
nombre = "Jhonatan"
bienvenida = f"Hola {nombre} ¿Como estas?"
del bienvenida
#la variable bienvenida no existe por que se elimino
```

_Operadores de pertenencia (in / not in)_
```py
bienvenida = f"Hola {nombre} ¿Como estas?"

print("Haola" not in bienvenida);#false
print("Hola" not in bienvenida);#true
```

*camelCase*
```py
nombreCompletoDeAlgo = 'Hola test'
```

*snake_case*
```py
nombre_completo_de_algo = 'Hola test'
```

*`Datos compuestos`*

*lista*
```py
lista = ["Jhonatan", "Mejia", True, 1.78]
print(lista[1])
# Mejia
```

*tupla*

La diferencia de la tupla es que no se puede modificar
```py
lista = ("Jhonatan", "Mejia", True, 1.78)
print(lista[1])
# Mejia
```

*set*

- Funciona como las listas, pero no se pueden modificar elementos, 
- no tienen un orden especifico por lo que no se puede acceder por el indice, 
- no alamcena datos duplicados, 
- no almacena datos por indice
```py
lista = ("Jhonatan", "Mejia", True, 1.78)
print(lista[1])
# Mejia
```

*diccionario*
- Le asignamos el valor de la clave
- La estructura es _key_ : _value_
```py
diccionario = {
    'nombre': 'Jhonatan',
    'apellido': 'Mejia',
    'altura': '1.78'
}

print(diccionario['altura'])
```

*`Operadores aritmeticos`*

|Operador|Descripcion|Ejemplo|
|-|-|-|
|+|Suma|a + b = 15|
|-|Resta|b - a = 5|
|*|Multiplicación|a * b = 50|
|/|Division|b / a = 2|
|%|Modulo|b % a = 0|
|**|Exponente|b ** a = 10000|
|//|Disivion baja(Devuelve el entero de la division)|b // a = 2|


*`Operadores aritmeticos`*
|Operador|Comparación
|-|-|
|==|es igual que|
|!=|es distinto que|
|<|es menor que|
|<=|es menor o igual que|
|>|es mayor|
|>=|es mayor o igual que|
