**************** PR�CTICA 10 - LENGUAJES Y PARADIGMAS DE PROGRAMACI�N ******************

Autores: 
- Noelia Rodr�guez Mart�n
- Juan Manuel Ramos P�rez
           
OBJETIVO

Acabar el c�digo de las matrices densas y diespersas de la pr�ctica pasada.
Desarrollar m�todos para calcular el m�ximo y el m�nimo de los elementos de una matriz.
Construit la gema (gem build).
Considerar su publicaci�n (gem push).

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


