**************** PR�CTICA 11 - LENGUAJES Y PARADIGMAS DE PROGRAMACI�N ******************

Autores: 
- Noelia Rodr�guez Mart�n
- Juan Manuel Ramos P�rez
           
OBJETIVO

Considere la Gema para la representaci�n de Matrices que ha desarrollado en pr�cticas anteriores. Los objetivos de esta pr�ctica son dos:
Documentar la gema (utlizando RDOC).
Desarrollar m�todos con la filosof�a de la programaci�n funcional.
Utilizar m�todos como 'map/collect', 'inject/reduce', 'upto' o 'times' para implementar la suma y el producto de matrices.
Generar la documentaci�n de la Gema.

CLASE MATRIZ (MADRE)

Es un clase abstracta, por tanto no tiene m�todos. 


CLASE DENSA (HIJA)

M�TODOS

Los m�todos que se han implementado son los siguientes:

-- M�todo initialize --
Asignamos valores a las filas, columnas y argumentos. Es el constructor


-- M�todo to_s(*args) --
Debe: mostrar la matriz

 
-- M�todo +(other) --
Debe: calcula la suma de dos matrices 


-- M�todo -(other) --
Debe: calcula la resta de dos matrices 


-- M�todo  *(other) --
Debe: calcula la multiplicaci�n de dos matrices 


-- M�todo minimo --
Debe: calcula el n�mero menor de todos los elementos de la matriz 


-- M�todo maximo --
Debe: calcula el n�mero mayor de todos los elementos de la matriz 



CLASE DISPERSA (HIJA)

M�TODOS

Los m�todos que se han implementado son los siguientes:

-- M�todo initialize --
Asignamos valores a las filas, columnas y argumentos. Es el constructor



-- M�todo calcularFilCol(numElem) --
C�lcula las filas y las columnas.

 
-- M�todo minimo --
Debe: calcula el n�mero menor de todos los elementos de la matriz 


-- M�todo maximo -- 
Debe: calcula el n�mero mayor de todos los elementos de la matriz 


-- M�todo to_s --
Debe: mostrar la matriz


-- M�todo +(other) --
Debe: calcula la suma de dos matrices 


-- M�todo -(other) --
Debe: calcula la resta de dos matrices 


-- M�todo *(other) --
Debe: calcula la multiplicaci�n de dos matrices 


CLASE FRACCI�N

-- M�todo coerce --
Debe: suma un entero con una fracci�n y una fracci�n con un entero y fracci�n con fracci�n.




