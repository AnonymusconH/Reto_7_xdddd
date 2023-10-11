# Reto_7_xdddd

## Punto 1

```
def cuadrados(n):
if n <=100
cuadrados = [i**2 for i in range (1, 101)]

return cuadrados [:n]
print ("El cuadrado de" + str(n) + "es: " + str(cuadrados)")

```

## Punto 2

```
n= int
while n <= 1000:
    n = n + 1
    if n % 2 !=0:
    print("La lista de números pares son: ")
    print (n)

continue

n = 0
while n <= 1000:
  if n % 2 != 0:
    print(i)
  n = n + 1

   print("Y la lista de números pares son: ")
    print (n)


```

## Puto 3

```
n : int
n = int(input("Ingrese un número natural mayor o igual a 2: "))
Descendentes = i - 2n
while n > 2:
    if n % 2 == 0:
        n -= 2
    else:
        n = n +1
        n -= 2
    print(n)

print("La lista de números pares anteriores a " + str(n) + " es:" + str(Descendetes))

```


## Punto 4

En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18.9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a la de A.

```
pais_A : int = 25000000
pais_B : int = 18900000
año=int(input("Ingrese un año: "))
while pais_A > pais_B:
  año += 1
  pais_A = pais_A + pais_A*0.02
  pais_B = pais_B + pais_B*0.03

  print("Para el año" + str(año) + "el Pais B superará en población al pais A")

```

## Punto 5

Imprimir el factorial de un número natural n dado.

```

import math 

x=int(input("Ingrese un número: "))

for x in range (1, x+1):
 fact= math.factorial(x)
print("El factorial de" + str(x) + "es = " + str(fact))

```

## Punto 6

```
import random
numero_ = int(input("Ingresa un entero entre 0 y 100: "))
bandera : bool = True
Mínimo : int = 1
Máximo : int = 100
while bandera == True:
  numero_para_advinar= random.randint(Mínimo, Máximo)
  pregunta_ = input("Tu número es mayor, menor o igual a " +str(numero_para_advinar)+ ": ")
  if pregunta_ == "mayor":
    minimo = numero_para_advinar + 1
  elif pregunta_== "menor" :
    maximo = numero_para_advinar -1
  elif pregunta_ == "igual":
    break
print("El número que tenias en mente era el: " +str(numero_para_advinar))

```

## Punto 7

```

n = int(input("Ingrese un número entre 2  50:"))
divisor = 1
Lista_divisores=[]

while divisor <= n:
  if n % divisor == 0:
    Lista_divisores.append(divisor)
    divisor += 1
  else:
    divisor += 1

print(Lista_divisores)

```

## Punto 8

```
for numero in range (1,101):
    if numero> 1:
        cont=0
        i=2
        while i<numero and cont==0:
            resto=numero % i
            if resto==0:
                cont+=1
            i+=1
        if cont== 0:
            print(numero)

```
