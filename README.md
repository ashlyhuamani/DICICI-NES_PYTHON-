# CONTROLES DE FLUJO EN PYTHON 

Se trata de una estructura de control condicional. Nos permite evaluar si una o más condiciones se cumplen, para decir qué acción vamos a ejecutar. Esta evaluación de condiciones sólo puede dar un resultado Verdadero o un resultado Falso.

### LOS PRINCIPALES CONTROLES DE FLUJO EN PYTHON

1.- CONDICIONALES:
* `if`:Permite ejecutar un bloque de codigo se se cumple una condición.

* `else`:Se ejecuta si la condición del `if` no se cumple.

* `elif`:Se utiliza para evaluar múltiples condiciones en un solo bloque de código.

2.-BUCLES:

* `for`:Se utiliza para iterar sobre una secuencia (como una lista o una cadena de texto ) o cualquier objepto iterable.

* `while`:Ejecuta un bloque de código mientras se cumpla una condición 

3.-CONTROLES DE FLUJO ADICIONAL:

* `break`:Se utiliza para salir de bucle de manera anticipada.

* `continue`:Se utilizan para saltar a la siguiente iteración de bucle sin ejecutar el resto del código dentro del bucle.

* `pass`:Se utiliza como marcador de posición cuando no se nesecita ejecutar ningún código en un bloque determinado.

Estas estructuras de controles de flujo son fundamentales para realizar tareas como tomar decisiones, repetir acciones y controlar el flujo de ejecución de un programa python.


### EJEMPLOS:

```PYTHON

1. Ejemplo de condicional  if :
 
python
 Copiar
edad = 18

if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
 
 
2. Ejemplo de condicional  if ,  elif  y  else :
 
python
 Copiar
nota = 85

if nota >= 90:
    print("Tienes una nota excelente")
elif nota >= 80:
    print("Tienes una nota buena")
elif nota >= 70:
    print("Tienes una nota regular")
else:
    print("Tienes una nota baja")
 
 
3. Ejemplo de bucle  for :
 
python
 Copiar
frutas = ["manzana", "banana", "naranja"]

for fruta in frutas:
    print(fruta)
 
 
4. Ejemplo de bucle  while :
 
python
 Copiar
contador = 0

while contador < 5:
    print("El contador es:", contador)
    contador += 1
 
 
5. Ejemplo de  break  en un bucle:
 
python
 Copiar
frutas = ["manzana", "banana", "naranja"]

for fruta in frutas:
    if fruta == "banana":
        break
    print(fruta)
 
 
6. Ejemplo de  continue  en un bucle:
 
python
 Copiar
frutas = ["manzana", "banana", "naranja"]

for fruta in frutas:
    if fruta == "banana":
        continue
    print(fruta)
 


