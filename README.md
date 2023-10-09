# Reto_7_xdddd

## Punto 4

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
