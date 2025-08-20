# La suma, fundamentalmente
La suma, en una base cualquiera consiste en dígitos con valores arbitrarios, cada uno mayor que el anterior.
Tenemos 2 dígitos (0-1) en base 2 (binario), con los cuales representar cantidades. Esencialmente, base 2 es como contar hasta 10 cuando te faltan 8 dedos.

Cuando contamos hasta 10, en base 10 (decimal, como lo que siempre hemos utilizado), lo podemos pensar como contar con los dedos, levantando cada dedo señalando una unidad más, hasta que nos encontramos con el 10, que representa una mano completa. Podemos contar hasta el 20, que representa 2 manos enteras y así, hasta n.
La diferencia con base 2 es que cada dígito representa un dos, elevado a 0 en un inicio y aumentando en 1 por cada dígito, de derecha a izquierda.

# Modelo K, Stibitz
En el año 1936, G. Stibitz, utilizando dos relés y chatarra, logra hacer el primer 2-bit adder (una computadora, capaz de sumar 2 números en binario).
El equivalente a un 2-bit adder, utilizando un simulador de lógica:
<img width="829" height="591" alt="image" src="https://github.com/user-attachments/assets/ed002176-f7e0-4990-a966-f67f76ddad83" />

Esencialmente, la calculadora contiene dos luces señalizando el primer dígito y segundo (llamado carry-over, dado que se trae siempre del último dígito a la derecha). 

La tabla de verdad para lograr aquel 2-bit adder es la siguiente:
| A | B | S | Carry Over |
|:--|:-:|:-:|-----------:|
| 0 | 0 | 0 | 0          |
