# Reto #5 Condicionales

Espero que se encuentren excelente estimados lectores, el día de hoy en este ropositorio haremos varios ejemplos de código en Python utilizando los condicionales.



## Ejemplo No. 1

Se debe plantear un código mediante el cual, al ingresar un número entero, se imprima si dicho número corresponde al código ASCII de una vocal minúscula. El código ASCII es el siguiente:

![image](https://user-images.githubusercontent.com/124615034/224470569-1225364c-bed4-49e4-88b1-341ca33eb36b.png)

El código correspondiente a este problema escridigitadoto en pseudocódigo es el siguiente:

```sh
a : int
a = int(input("Ingrese un numero: ")) 
if a == 97 or a == 101 or a == 105 or a == 111 or a == 117 :
  print("El numero "+str(a)+" corresponde al código ASCII de una vocal minúscula")
else:
  print("El numero "+str(a)+" no corresponde al código ASCII de una vocal minúscula")
```
El programa funcionando se veía de la siguiente manera:
