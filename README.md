# Ejercicio 1

Escribir por pantalla cada carácter de una cadena introducida por teclado.

## Análisis del ejercicio

Leemos una cadena y tenemos que recorrerla (necesito un bucle que vaya desde la
posición 0 hasta la longitud de la cadena menos 1. En cada iteración mostramos
un carácter (utilizamos la función subcadena).
Datos de entrada:La cadena
Información de salida: Cada uno de los caracteres de la cadena
Variables: cad (caracter), posicion (entero)

# Ejercicio 2

Pide una cadena y un carácter por teclado (valida que sea un carácter)
y muestra cuantas veces aparece el carácter en la cadena.

## Análisis

Leo una cadena y un carácter (tengo que asegurarme que es un sólo carácter,
es decir hasta que la longitud sea 1). Recorro la cadena y compara cada uno de
sus caracteres con el carácter introducido, si es igual lo cuento.
Datos de entrada: Cadena y carácter
Información de salida: Número de veces que aparece el carácter en la cadena.
Variables: cad, car (caracter), posicion, cont (entero)

# Ejercicio 3

Realizar un programa que defina un vector llamado "vector_numeros" de 10 enteros,
a continuación lo inicialice con valores aleatorios (del 1 al 10)
y posteriormente muestre en pantalla cada elemento del vector junto con
su cuadrado y su cubo.

## Análisis

Recorro un vector de 10 enteros y lo inicializo con valoreas aleatorios.
A continuación lo recorro para mostrar los valores, el cuadrado y el cubo.
Datos de entrada: Nada
Información de salida: 10 números, su cuadrado y su cubo.
Variables: vector_numeros (vector de 10 enteros)

# Ejercicio 4

Algoritmo que pida números hasta que se introduzca un cero. Debe imprimir la suma
y la media de todos los números introducidos.

## Análisis

Vamos pidiendo números hasta introducir un 0.
Necesitamos un acumulador para ir realizando las sumas intermedias.
Además necesitamos un contador, para calcular la media (suma cantidad)
Datos de entrada: números, un acumulador para sumar y un contador
Información de salida:La suma y la media
Variables:num, suma, cont (enteros)

# Ejercicio 5

Algoritmo que muestre la tabla de multiplicar de los números 1,2,3,4 y 5.

## Análisis

Debo repetir 5 veces (desde el número 1 hasta el 5) mostrar
la tabla de multiplicar de ese número.
Como vimos en otro ejercicio para una tabla de multiplicar debemos repetir
10 veces para mostrar cada línea de la tabla.
Por lo tanto necesito dos bucles anidados.
Datos de entrada: Nada
Información de salida: Las cinco tablas de multiplicar
Variables:tabla,num(entero)
