# Reto_4

Hello…. it´s me... 

Buen día, en este repositorio explico cómo hacer el "Reto no. 4" de la clase.   :) 

El reto 4 cosiste en:

### 1.Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

### 2.Revise el procedimiento matemático para hallar raices cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

## 1.1 Pseudocodigo de algoritmo para obtener una lista de numeros primos:
 
Para hacer este punto, primeramente me acorde del metodo _PRO_ del pseudocodigo para hallar los divisores de un numero "n" que es el siguiente, para el que no se acuerde.

```pseudocode
  Inicio
PASO 1. Crear una lista de números naturales desde 2 hasta (n^0.5)+1
PASO 2. repetir para cada número i de la lista
PASO 2.1. Dividir n sobre i
PASO 2.2. Si el residuo de la división es cero, i es divisor
PASO 2.3. Sino, i no es divisor
Fin
```
Entonces teniendo encuenta ese pseudocodigo y apoyandome en las mismas bases hice el siguiente pseudocodigo para hallar una lista de numeros primos:
```pseudocode
Inicio

n=int
i=int
m=int
primos[..]  --PD: este "primos[..]" es una lista donde guardaremos los numeros primos

1. ingresar un numero "n"
2. i=2
3. si i ≤ "n" hacer:
  3.1  m=2
  3.2  si m ≤ floor(i^0.5) hacer:
      3.2.1  si modulo de (i/m)=0 hacer:
          3.2.1.1  i=i+1 y regresar al paso 3       
      3.1.2 si no hacer
          3.1.2.1  m=m+1 y regresar al paso 3.2
  3.3 si no, hacer 
      3.3.1 añadir a "i" a la lista "primos[..]"
      3.3.2 i=i+1 y regresar al paso 3
4. si no, hacer
  4.1 mostrar"primos[..]"
 
Fin
```
## 1.2 Diagrama de flujo de algoritmo para obtener una lista de numeros primos:

Con el fin de entender mejor en pseudocodigo anterior, hice el siguiente diagrama de flujo (...Tambien por que tocaba hacerlo -_- ) en el que la funcion es la misma:"Obtener una lista de numeros primos anteriores a un numero determinado"

![Diagrama numeros primos](https://user-images.githubusercontent.com/124616179/221440393-f874e631-a643-4b5f-a770-e544d1119459.png)

## 2.1 Pseudocodigo de algoritmo para hallar raices cuadradas:

Para este punto utilizaremos el metodo de Newton que su "teoria simplificada" seria la siguiente:

'''
Un método para encontrar las raíces cuadradas sin una calculadora es el método de Newton Dividir y Promediar :

1) Suponga (Guess) la raíz cuadrada del número.

2) Divida (Divide) la suposición entre el número original.

3) Saque el promedio (Average) de la suposición y el cociente.

4) Repita (Repeat) con este promedio como una nueva suposición.

"Guess, Divide, Average, Repeat." (Creo que GDAR no es una buena manera para recordar esto...)

Nota: Esta "Teoria simplificada" la saque de la siguiente pagina [por favor no me saquen de la universidad por plagio (╥﹏╥)]:
https://www.varsitytutors.com/hotmath/hotmath_help/spanish/topics/square-roots#:~:text=Un%20m%C3%A9todo%20para%20encontrar%20las,la%20suposici%C3%B3n%20y%20el%20cociente.

'''
Entonces continuando con el tema, el pseudocodigo seria el siguiente:
```pseudocode
Inicio

n=int
m=int
b=float
i=int 
i=1

1  ingresar un numero"n"
2  encontrar un numero "m" que cumpla (m^2)≤n
3  mientras i ≤ 2 sea verdadero, hacer
   3.1  b=(n/m) con 3 numeros despues de la ","
   3.2  m=(m+b)/2
   3.3  i=i+1
4 es falso, hacer
   4.1 mostrar:" La raiz cuadrada de ", n " es ", m
   
   
Fin



```
## 2.2 Diagrama de flujo de algoritmo para hallar raices cuadradas:

"Esta ya se la saben..."
 Como ya hicimos anteriormente a continuacion se mostrará el diagrama de flujo respectivo al pseudocodigo para hallar raices cuadradas:
 
 ![Diagrama hallar Raices](https://user-images.githubusercontent.com/124616179/221441667-053cb101-8e78-4e91-94ea-960f4b92b46f.png)
 
<details><summary>Bueeeeno creo que no seria nada mas, entonces nos vemos en la proxima, y recuerden...</summary><p>

...El que se mueva es gay ._.

</p></details><br>

### #Viva Pyth-Ohm 

Gracias por su atencion.    😊
