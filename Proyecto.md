#PROYECTO IPC
Problema: Se realizan cotizaciones manualmente y es necesario que se realice un programa que pueda hacer mas eficiente este trabajo,
 el programa debe calcular los recargos que le corresponden a cada persona según su edad, estado civil (soltero o casado) y 
según la cantidad de hijos que tenga el asegurado.

 Algoritmo:
1.	Declarar el valor base de la cotización.
2.	Declarar el valor de los recargos a aplicar según cada situación.
3.	Ingresar el nombre del cliente
4.	Ingresar la edad del cliente
5.	Convertir la string a integer
6.	Comprobar si es casado o soltero.
7.	Si, en caso es casado ingresar edad esposo/a.
8.	>>convertir la string a integer 
9.	Comprobar si tiene hijos
10.	Si, tiene hijos, convertir string a integer.
11.	Dependiendo de la edad agregar recargo multiplicando el valor base por el recargo correspondiente al rango de edad:
12.	si su edad esta entre 18 a 24 (10%)
13.	si su edad esta entre 25 a 49 (20%)
14.	si su edad esta mayor de 50 (30%)
15.	Si tiene cónyuge agregar el mismo recargo según su edad.
16.	Si tiene hijos agregar recargo del 20% por cada hijo que tenga, multiplicando el valor base por el numero de hijos por el 20%
17.	Establecer el recargo total 
18.	Mostrar el nombre
19.	Mostrar el recargo total según las condiciones ingresadas
20.	Mostrar el precio final (recargo total mas precio base).
