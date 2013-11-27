**************** PRÁCTICA 11 - LENGUAJES Y PARADIGMAS DE PROGRAMACIÓN ******************

Autores: 
- Noelia Rodríguez Martín
- Juan Manuel Ramos Pérez
           
OBJETIVO

Considere la Gema para la representación de Matrices que ha desarrollado en prácticas anteriores. Los objetivos de esta práctica son dos:
Documentar la gema (utlizando RDOC).
Desarrollar métodos con la filosofía de la programación funcional.
Utilizar métodos como 'map/collect', 'inject/reduce', 'upto' o 'times' para implementar la suma y el producto de matrices.
Generar la documentación de la Gema.

CLASE MATRIZ (MADRE)

Es un clase abstracta, por tanto no tiene métodos. 


CLASE DENSA (HIJA)

MÉTODOS

Los métodos que se han implementado son los siguientes:

-- Método initialize --
Asignamos valores a las filas, columnas y argumentos. Es el constructor


-- Método to_s(*args) --
Debe: mostrar la matriz

 
-- Método +(other) --
Debe: calcula la suma de dos matrices 


-- Método -(other) --
Debe: calcula la resta de dos matrices 


-- Método  *(other) --
Debe: calcula la multiplicación de dos matrices 


-- Método minimo --
Debe: calcula el número menor de todos los elementos de la matriz 


-- Método maximo --
Debe: calcula el número mayor de todos los elementos de la matriz 



CLASE DISPERSA (HIJA)

MÉTODOS

Los métodos que se han implementado son los siguientes:

-- Método initialize --
Asignamos valores a las filas, columnas y argumentos. Es el constructor



-- Método calcularFilCol(numElem) --
Cálcula las filas y las columnas.

 
-- Método minimo --
Debe: calcula el número menor de todos los elementos de la matriz 


-- Método maximo -- 
Debe: calcula el número mayor de todos los elementos de la matriz 


-- Método to_s --
Debe: mostrar la matriz


-- Método +(other) --
Debe: calcula la suma de dos matrices 


-- Método -(other) --
Debe: calcula la resta de dos matrices 


-- Método *(other) --
Debe: calcula la multiplicación de dos matrices 


CLASE FRACCIÓN

-- Método coerce --
Debe: suma un entero con una fracción y una fracción con un entero y fracción con fracción.




