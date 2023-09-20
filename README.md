# sobreviviendo-a-la-programacion-3

En esta bella tarde de semana universitaria me propuse a ahcae reto 4 de programacion (no entiendo nada)


1.Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```pseudocode
x = int 
x = int(input("ingrese un numero entero: "))

if x == 97:
  print("el numero corresponde a una minuscula en el codigo ASCII ")
elif x == 101:
  print("el numero corresponde a una minuscula en el codigo ASCII ")
elif x == 105:
  print("el numero corresponde a una minuscula en el codigo ASCII ")
elif x == 111:
  print("el numero corresponde a una minuscula en el codigo ASCII ")
elif x == 117:
  print("el numero corresponde a una minuscula en el codigo ASCII ")
else: 
  print("el numero no corresponde a una vocal minuscula en el codigo ASCII ")
```

2.Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```pseudocode
x = (input("ingrese una letra:"))
n = ord (x)

if n%2 == 0:
  print("el codigo ASCII es par")
else:
  print("el codigo ASCII es impar")
```


3.Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

Tengo que decir que aunque intente de varias maneras para lograr un codigo menos extenso y mas "bonito" no encontre las herramientas 
para hacerlo

```pseudocode
x = int 
x = int(input("ingrese un numero caracter: "))

if x == 48:
  print("el numero corresponde a '0' en el codigo ASCII")
elif x == 49:
  print("el numero corresponde a '1' en el codigo ASCII")
elif x == 50:
  print("el numero corresponde a '2' en el codigo ASCII")
elif x == 51:
  print("el numero corresponde a '3' en el codigo ASCII")
elif x == 52:
  print("el numero corresponde a '4' en el codigo ASCII")
elif x == 53:
  print("el numero corresponde a '5' en el codigo ASCII")
elif x == 54:
  print("el numero corresponde a '6' en el codigo ASCII")
elif x == 55:
  print("el numero corresponde a '7' en el codigo ASCII")
elif x == 56:
  print("el numero corresponde a '8' en el codigo ASCII")
elif x == 57:
  print("el numero corresponde a '9' en el codigo ASCII")

else: 
  print("el numero no corresponde a un digito en el codigo ASCII")
```



4.Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. 
Para cada caso de debe imprimir el texto que se especifica a continuación:

 -  Positivo: "El número x es positivo"
 -  Negativo: "El número x es negativo"
 -  Cero (0): "El número x es el neutro para la suma"


ciertamente este fue le ejercicio mas facil de hacer, por ende me senti todo un pro pa esta materia (no le se a la programación)


```pseudocode
x : float
x = float(input("ingrese un numero:"))

if x<0:
  print("el numero x es negativo")
elif x==0:
  print("El número x es el neutro para la suma")
elif x>0:
  print("el numero x es positivo")
```




5.Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.


- En resumen casi me da algo haciendo este ejercicio, al final descubri que era mas facil de lo que pensaba utilizando la formula
  
  para hallar la distancia entre dos puntos

```pseudocode
x= float(input("ingrese la coordenada en el eje x:"))
y= float(input("ingrese la coordenada en el eje y:"))
a= float(input("ingrese el extensión del radio:"))
b= float(input("ingrese la nueva coordenada en el eje x:"))
c= float(input("ingrese la nueva coordenada en el eje y:"))

m= ((b-x))
g= ((m)**2)
n= ((c-y))
h=((n)**2)
z= ((g+h)**0.5)

if z<a:
  print("la coordenada esta dentro de la extension del radio")
elif z==a:
  print("la coordenada esta dentro de la extension del radio")
else:
  print("la punto no  esta dentro de la extension del radio")
```
