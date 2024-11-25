# Reto-No.3
```
x = int(input("Ingrese x: "))
for numero in range(2, x+1):https://github.com/11ZaidaG11/Reto-No.3/blob/main/README.md
  divisores = 0
  for i in range(1, numero+1):
    if numero%i == 0:
      divisores += 1
  if divisores == 2:
    print(numero, "primo")
  else:
    print(numero, "no primo")
```
