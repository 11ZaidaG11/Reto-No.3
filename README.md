# Reto-No.3
## Pseudocodigo
Inicio
1. Ingresar un numero x cualquiera
2. Repetir para cada numero desde 2 hasta x
   2.1. Comenzar la cuenta de los divisores del numero en 0
   2.2. Repetir para cada num_div desde 1 hasta el numero
        2.2.1. Si el residuo del numero dividido num_div es igual a 0, i es divisor
               2.2.1.1. Sumar 1 a la cuenta de divisores del numero
        2.2.2. Sino, i no es divisor
   2.3. Si los divisores del numero son 2, el numero es primo
   2.4. Sino, el numero no es primo
Fin
```
x = int(input("Ingrese x: "))
for numero in range(2, x+1):
  divisores = 0
  for i in range(1, numero+1):
    if numero%i == 0:
      divisores += 1
  if divisores == 2:
    print(numero, "primo")
  else:
    print(numero, "no primo")
```
