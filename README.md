# <center>Práctica 3<center>

Objetivo:
El objetivo de esta práctica es familiarizarte con los diferentes tipos de datos en Python y cómo trabajar con ellos.

## 1- Escribe una breve descripción de los Tipos de Objetos y Estructuras de Datos que se muestran a continuación: 

* #### Number:  Para valores numéricos (enteros y decimales). Se utilizan para realizar operaciones matemáticas, como suma, resta, multiplicación y división.
* #### String: Sirve para almacenar y manipular texto. Permiten manipular texto, concatenar cadenas, buscar patrones y realizar operaciones con caracteres. 
* #### List: Se representan entre corchetes [] y sus elementos se separan por comas. Permiten agregar, eliminar, modificar y acceder a elementos por índice.
* #### Set: Se representan entre llaves y sus elementos se separan por comas. Permiten verificar si un elemento existe, agregar o eliminar elementos, y realizar operaciones de conjuntos (unión, intersección, diferencia).
* #### Tuple: Es una colección ordenada de elementos inmutables, que pueden ser de diferentes tipos. Se representan entre paréntesis () y sus elementos se separan por comas. Permiten acceder a elementos por índice, pero no se pueden modificar una vez creados.
* #### Dictionarie: Es una colección no ordenada de pares clave-valor, donde cada clave es única y apunta a un valor asociado. Se representan entre llaves y los pares se separan por dos puntos y comas (clave:valor). Permiten acceder a valores a través de sus claves, agregar o eliminar pares, y recorrer la colección por claves o valores.

## 2- Cúal es la diferencia entre List, Typle y Set?

LIST

Ordenadas: Los elementos mantienen el orden de inserción.
Mutables: Se pueden modificar (agregar, eliminar, cambiar) después de la creación.
Duplicados: Permiten valores duplicados.
Representación: [], elementos separados por comas.
Ejemplo: my_list = [1, "Hola", 3.14]

TYPLE

Ordenadas: Los elementos mantienen el orden de inserción.
Inmutables: No se pueden modificar después de la creación.
Duplicados: Permiten valores duplicados.
Representación: (), elementos separados por comas.
Ejemplo: my_tuple = (1, "Hola", 3.14)

SET

No ordenados: El orden de los elementos no está definido.
Mutables: Se pueden modificar (agregar, eliminar) después de la creación.
Sin duplicados: No permiten valores duplicados, cada elemento es único.
Representación: {}, elementos separados por comas.
Ejemplo: my_set = {1, "Hola", 3.14}

## 3- Crea una lista que contenga números enteros y flotantes e imprimela

list = [1, 1, 3.14, -5, 2.71, 0]
print(list)

## 4- Crea una tupla que contenga algunos Strings e imprimela

tupla = ("Yo soy yina", "Que cosa", "Amen")

print(tupla)


## 5- Crea un diccionario que tenga como claves algunas de las cadenas de la tupla creada antes y como valores algunos de los números de la lista creada antes e imprime

upla = ("Yo soy yina", "Que cosa", "Amen")
lista = [1, 1, 3.14, -5, 2.71, 0]

diccionario = dict(zip(tupla, lista))

print(diccionario)

## 6- Escribe una ecuación de como resultado 150,75 utilizando la multiplicación, la división, la potencia, la raíz cuadrada, la suma y la resta 

potencia = 5 ** 2 
suma1 = potencia + 7.15 
raiz_cuadrada = 9 ** 0.5  
suma2 = raiz_cuadrada + 2  
multiplicacion = suma1 * suma2  
multiplicacion3 = 4 * 2.5  
resultado_final = multiplicacion - multiplicacion3  
print(resultado_final)

## 7- Añade un número al listado creado en el punto 3

list = [1, 1, 3.14, -5, 2.71, 0]

list.append(8)

print(list)

## 8- Convierte el listado anterior en un set e imprimelo

list = [1, 1, 3.14, -5, 2.71, 0]

set = set(list)

print(set)

## 9- Utiliza los index y las llaves para acceder e imprimir "hola" del siguiente diccionario:
#### d = {'c1':[4,1,{'c2':[ "es otro listado", { '0' :[3,1,['hola']]}]}]}

d = {'c1': [4, 1, {'c2': ["es otro listado", {'0': [3, 1, ['hola']]}]}]}

hola = d['c1'][2]['c2'][1]['0'][2]

print(hola) 

## 10- Basado en el diccionario anterior, que resultado arroja la siguiente expresión?
#### d['c1'][0] > d['c1'][2]['c2'][1]['0'][0]

# Diccionario anterior
d = {'c1': [4, 1, {'c2': ["es otro listado", {'0': [3, 1, ['hola']]}]}]}

resultado = d['c1'][0] > d['c1'][2]['c2'][1]['0'][0]

print(resultado)  

