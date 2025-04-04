[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KVkZjcZ_)
# Trabajo Práctico 3

## Ejercicio 1 - Uso del "in"

Ingresar un nombre usando input y verificar que contenga cada una de las vocales.
No considerar el uso de vocales con tilde, pero si considerar que la letra puede ser mayúscula o minúscula.

Dado el ingreso de las palabras dadas por ejemplo, se deben imprimir en pantalla los textos indicados con su correspondiente valor booleano.

Ejemplo: 
```
# Input
> Matias

# Imprime en pantalla
Contiene a: True
Contiene e: False
Contiene i: True
Contiene o: False
Contiene u: False

# Input
> Augusto

# Imprime en pantalla
Contiene a: True
Contiene e: False
Contiene i: False
Contiene o: True
Contiene u: True
```

************************************************** 

## Ejercicio 2 - Uso del "slice" con múltiples caracteres. 
Obtener los siguientes datos del texto de ejemplo e imprimirlos en pantalla:
* Primeras 3 letras del texto ( usando índices positivos )
* Las 3 letras en medio del texto ( usando índices positivos )
* De la primera a la cuarta letra ( incluída ) y de la antepenúltima hasta la última ( incluída )

Es necesario que todos los caracteres se impriman en minúscula

Ejemplo: 
```
texto = "Awesome"
# Imprime en pantalla
awe
eso
awesome
```

************************************************** 

## Ejercicio 3 - Uso del "slice" cada N caracteres con condiciones extra.
Ingresar un texto usando input e imprimir en pantalla el resultado de obtener los valores saltando de a 2 caracteres, pero sólo a partir del quinto carácter ( incluído )

Ejemplo: 
```
# Input
> Hello, World!
# Imprime en pantalla
o ol!

# Input
> 12345678910
# Imprime en pantalla
5790
```
