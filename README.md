# Reto #5 Condicionales

Espero que se encuentren excelente estimados lectores, el día de hoy en este repositorio haremos varios ejemplos de código en Python utilizando los condicionales.


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
El programa funcionando se ve de la siguiente manera:
![image](https://user-images.githubusercontent.com/124615034/224505457-9533e51c-b116-4a96-81af-e72fb39b0d55.png)
![image](https://user-images.githubusercontent.com/124615034/224505478-778276a9-b737-49e2-8fe5-474fa86573c3.png)


![image](https://user-images.githubusercontent.com/124615034/224505535-d0c336a9-187b-4e47-9f52-325762c8a145.png)
![image](https://user-images.githubusercontent.com/124615034/224505546-6b55d4e4-f246-47ab-a707-73162c9fb56a.png)


## Ejemplo No. 2
Ahora se debe formular un código mediante el cual al ingresar una cadena de caracteres (letras), debe determinar si la primera letra de dicha cadena corresponde al código ASCII de un número par o impar.
El código que ejecuta el anterior problema de manera óptima escrito en pseudocódigo es el siguiente:
```sh
a = input("Ingrese una cadena de carácteres: ")
primer_letra = a[0]
x = ord(a[0])
if x%2 == 0:
 print ("La primera letra de la enteior cadena de caracteres corresponde al código ASCII de un número par")
else:
 print ("La primera letra de la anterior cadena de caracteres corresponde al código ASCII de un número impar")
```

El anterior código ejecutado en un notebook de python se ve de la siguiente manera:

![image](https://user-images.githubusercontent.com/124615034/224559335-e429a745-82a2-464b-94c7-e70df7fcb92b.png)
![image](https://user-images.githubusercontent.com/124615034/224559343-6f934c1a-20ac-40d5-ab9e-bf2b46a48bce.png)


![image](https://user-images.githubusercontent.com/124615034/224559374-c2e4af53-fb57-41b4-a657-c36e1637066f.png)
![image](https://user-images.githubusercontent.com/124615034/224559382-49c33592-0fe4-4245-9b98-121269870b5b.png)

## Ejemplo No. 3
El siguiente ejemplo consiste en construir un programa el cual al ingresar un caracter, nos indique si dicho carecter es un dígito (número) o no.
Para ello haremos uso de la variable booleana (a.isdigit), que nos dice si es cierto o falso que el caracter ingresado es un número.
La solución al anterior problema escrita en pseudocódigo:
```sh
a = input("Ingrese un caracter: ")
if a.isdigit():
 print ("El caracter ingresado es un dígito")
else:
 print ("El caracter ingresado no es un dígito")
```
Ejecutado se ve de la siguiente manera:
![image](https://user-images.githubusercontent.com/124615034/224559906-b9e212e6-4a19-4cf3-a3b5-534e2fc5693d.png)
![image](https://user-images.githubusercontent.com/124615034/224559920-52bb3886-3314-4a6d-b110-5482af0a5cb2.png)

![image](https://user-images.githubusercontent.com/124615034/224559939-2364f486-71ae-4dbe-99ad-a6f27874d43c.png)
![image](https://user-images.githubusercontent.com/124615034/224559949-ee7feb11-06c1-4c76-bb88-6bad331379b2.png)


## Ejemplo No. 4
Posteriormente se debe diseñar un programa, que al ingresar un dígito, y al ejecutar dicho programa, nos determine si el dígito ingresado es positivo, negativo o cero.
A continuación el código solución al anterior ejemplo:
```sh
a = float
a = int(input("Ingrese un numero: "))
if a > 0:
 print ("El número "+str(a)+" es positivo")
if a < 0:
 print ("El número "+str(a)+" es negativo") 
if a == 0:
 print ("El número "+str(a)+" es el neutro para la suma")
 ```
 
El código ejecutado en un notebook de python se ve así:
![image](https://user-images.githubusercontent.com/124615034/224560475-48d37b30-ccb5-4f41-8dff-66ec683cbe79.png)
![image](https://user-images.githubusercontent.com/124615034/224560486-44870bd6-092d-4464-9d36-ed51bacd1cac.png)

![image](https://user-images.githubusercontent.com/124615034/224560520-c760062f-0ac1-41c3-9884-8eaa21143d4e.png)
![image](https://user-images.githubusercontent.com/124615034/224560534-40e206c8-2c2c-4369-9658-2e0decf27aec.png)

![image](https://user-images.githubusercontent.com/124615034/224560553-d7b3a8c5-3f80-4b21-b5dc-eafeef406360.png)
![image](https://user-images.githubusercontent.com/124615034/224560575-6490dfe4-b5a2-4c25-981a-83e34bac780c.png)


## Ejemplo No. 5
Ahora bien, se planteó un código mediante el cual al determinar el centro y radio de un círculo, y posteriormente ingresar una coordenada (punto en x , punto en y), el programa nos indique si dicha coordenada pertenece al interior del circulo o a su superficie, o si por el contrario no hace parte de dicho circulo.
Para ello se hará uso de la ecuación general de la circunferencia en un plano cartesiano
> (x-h)² + (y-k)² = r²


El código correspondiente a lo planteado anteriormente se muestra a continuación:
```sh
h = float
k = float
r = float
x = float
y = float
h = float(input("ingrese la coordenada del centro respecto al eje x: "))
k = float(input("ingrese la coordenada del centro respecto al eje y: "))
r = float(input("ingrese el valor del radio: "))
x = float(input("ingrese la coordenada respecto al eje x: "))
y = float(input("ingrese la coordenada respecto al eje y: "))
if ((x-h)**2)+((y-k)**2) <= r**2:
 print ("La coordenada ("+str(x)+" , "+str(y)+") pertence al interior de la circunferencia")
else:
 print ("La coordenada ("+str(x)+" , "+str(y)+") no pertenece al interior de la circunferencia")
```

Se ve de la siguiente forma al ejecutarlo:
Determinar si el punto (3,5) hace parte de la circunferencia con centro en (2,3) y radio 3.

![image](https://user-images.githubusercontent.com/124615034/224561350-5fb94f04-c7a5-4df9-85e3-34fc2c1b3cf5.png)
![image](https://user-images.githubusercontent.com/124615034/224561419-32f04da1-239c-4aab-826b-3cc42004a3f3.png)
![image](https://user-images.githubusercontent.com/124615034/224561435-6efb9189-375e-4e8c-8f8f-00c4453c7562.png)
![image](https://user-images.githubusercontent.com/124615034/224561480-15714dca-56a0-4960-bf35-a35eb0f7e78f.png)
![image](https://user-images.githubusercontent.com/124615034/224561530-82efb033-f6c2-4daa-ba87-10ff62dbe0fd.png)
![image](https://user-images.githubusercontent.com/124615034/224561568-ccf779b2-dbe3-4442-a6e5-b5302f5c5d15.png)

Determinar si el punto (5,1) hace parte de la circunferencia con centro en (2,3) y radio 3.

![image](https://user-images.githubusercontent.com/124615034/224561350-5fb94f04-c7a5-4df9-85e3-34fc2c1b3cf5.png)
![image](https://user-images.githubusercontent.com/124615034/224561419-32f04da1-239c-4aab-826b-3cc42004a3f3.png)
![image](https://user-images.githubusercontent.com/124615034/224561435-6efb9189-375e-4e8c-8f8f-00c4453c7562.png)
![image](https://user-images.githubusercontent.com/124615034/224561705-bf4040aa-b97f-411a-a57b-c2a333e49c35.png)
![image](https://user-images.githubusercontent.com/124615034/224561717-7468a5f6-e491-400a-848d-cc83f467948e.png)
![image](https://user-images.githubusercontent.com/124615034/224561740-47a0f96a-d182-45ef-9988-b7a48acdc740.png)

- Demostración en Geogebra:

![image](https://user-images.githubusercontent.com/124615034/224561977-2741a339-dc0a-43cd-89bf-c77226af05cb.png)


## Ejemplo No. 6
Para finalizar esta serie de ejemplos acerca de los condicionales, se debe diseñar un código, el cual a partir de tres longitudes de lado dadas, indique si es posible conformar un triángulo o no.
Para el anterior problema se debe tener en cuenta la desigualdad triangular, que nos indica que la suma de dos lados del triángulo, debe ser mayor a la longitud del tercer lado.
> a + b > c
b + c > a
a + c > b

El código que resuelve dicha cuestión es el siguiente:
```sh
a = float
b = float
c = float
a = float(input("ingrese el valor de uno de los lados del triángulo: "))
b = float(input("ingrese el valor de uno de los lados del triángulo: "))
c = float(input("ingrese el valor de uno de los lados del triángulo: "))
if a < 0 or b < 0 or c < 0:
 print ("los longitudes de los lados no pueden ser negativas")
else:
 if a + b > c and  a + c > b  and  b + c > a:
  print ("con los valores de las longitudes ingresadas es posible conformar un triángulo")
 else:
  print ("con los valores de las longitudes ingresadas no es posible conformar un triángulo")
```

Al ejecutarlo se aprecia así:

![image](https://user-images.githubusercontent.com/124615034/224563319-91d6876a-f9f6-413c-8161-a42b1861dfec.png)
![image](https://user-images.githubusercontent.com/124615034/224563328-07a4a17e-bed0-4d3a-9f2a-0a327907dbac.png)
![image](https://user-images.githubusercontent.com/124615034/224563342-62fde3fa-1d9c-433c-98fa-b495d1ffa3c6.png)
![image](https://user-images.githubusercontent.com/124615034/224563359-413d3715-ae6d-419a-b5fc-16e09da58416.png)

- Demostración en Geogebra:

![image](https://user-images.githubusercontent.com/124615034/224563474-ce15166b-dc1e-4e5d-907d-cd9ebb63d9e6.png)


![image](https://user-images.githubusercontent.com/124615034/224563511-9610246d-ce96-4d11-a9ea-349ea06fb4b7.png)
![image](https://user-images.githubusercontent.com/124615034/224563527-f2f13be1-4fbc-40c0-887e-2ecaaabdb66b.png)
![image](https://user-images.githubusercontent.com/124615034/224563541-68cd73cb-d905-4672-9d4c-dec39bb603da.png)
![image](https://user-images.githubusercontent.com/124615034/224563562-7ea0e1a5-0668-42ff-a503-44254ae5eb08.png)

- Demostración en Geogebra:

![image](https://user-images.githubusercontent.com/124615034/224563628-20cbb1ce-5015-4a33-ba01-cbb9a28f03f2.png)

## FIN
Hasta acá llega nuestro camino en el presente repo, espero que haya sido de tu interés, si encuentras algún error o alguna inconsistencia, no dudes en contactarme y hacermela saber.

   "Si lo puedes soñar, lo puedes lograr"
         - Walt Disney

