# Ejercicios Resueltos de Combinaciones

## Ejercicio 1

Se premia un concurso de lectura de cuentos para niños con el sorteo de 4 bicicletas. En el concurso participaron 10 niños.

¿De cuántas formas pueden entregarse las bicicletas?

### Análisis

Debemos seleccionar 4 niños entre 10 participantes.

No interesa el orden en que sean elegidos.

Por ejemplo:

Juan, Ana, Pedro y Luis

representa el mismo grupo que:

Luis, Pedro, Ana y Juan

Por lo tanto:

✓ El orden NO importa.

✓ No existe repetición.

### Identificación

COMBINACIÓN ORDINARIA

### Datos

```text
n = 10
k = 4
```

### Fórmula

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

### Desarrollo

```text
            10!
C(10,4)=-----------
         (10-4)!4!

            10!
C(10,4)=-------
          6!4!

C(10,4)=210
```

### Respuesta

```text
210 formas
```

---

## Ejercicio 2

Se tienen los 4 ases de una baraja y se desean tomar al azar 2 cartas.

¿Cuántas combinaciones pueden resultar?

### Análisis

Solo interesa seleccionar 2 cartas.

No importa el orden.

Por ejemplo:

As de corazones y As de picas

es el mismo grupo que:

As de picas y As de corazones.

### Identificación

COMBINACIÓN ORDINARIA

### Datos

```text
n = 4
k = 2
```

### Fórmula

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

### Desarrollo

```text
           4!
C(4,2)=---------
         2!2!

C(4,2)=6
```

### Respuesta

```text
6 combinaciones
```

---

## Ejercicio 3

De los 15 mejores estudiantes de un colegio se desean seleccionar 10 para representar a la institución en un concurso de ortografía.

### Análisis

Solo interesa elegir estudiantes.

No importa el orden de selección.

Por lo tanto:

✓ El orden NO importa.

✓ No existe repetición.

### Identificación

COMBINACIÓN ORDINARIA

### Datos

```text
n = 15
k = 10
```

### Fórmula

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

### Desarrollo

```text
             15!
C(15,10)=-----------
          10!(15-10)!

             15!
C(15,10)=-------
            10!5!

C(15,10)=3003
```

### Respuesta

```text
3003 formas
```

---

## Ejercicio 4

Se desea formar un comité de 7 personas que incluya exactamente 3 mujeres, de un grupo formado por 5 mujeres y 9 hombres.

### Análisis

El comité debe estar formado por:

```text
3 mujeres
4 hombres
```

El orden no importa.

Por lo tanto:

✓ Combinación.

### Identificación

COMBINACIÓN ORDINARIA

### Datos

```text
Mujeres = 5
Hombres = 9

Elegir:

3 mujeres
4 hombres
```

### Fórmula

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

### Desarrollo

Primero seleccionamos las mujeres:

```text
C(5,3)=10
```

Luego seleccionamos los hombres:

```text
C(9,4)=126
```

```text
10 × 126

= 1260
```

### Respuesta

```text
1260 comités
```

---

## Ejercicio 5

Hallar el valor de k, sabiendo que el número de variaciones de k elementos tomados de 2 en 2 es el doble del número de combinaciones de k elementos tomados de 3 en 3.

### Análisis

En el problema aparecen:

✓ Variaciones.

✓ Combinaciones.

Debemos utilizar ambas fórmulas y resolver la ecuación.

### Identificación

ECUACIÓN CON COMBINACIONES

### Datos

```text
V(k,2)=2C(k,3)
```

### Fórmulas

Variación:

```text
           k!
V(k,2)=---------
         (k-2)!
```

Combinación:

```text
           k!
C(k,3)=---------
        (k-3)!3!
```

### Desarrollo

Sustituyendo:

```text
        k!
------------- =
      (k-2)!

        2k!
------------------
   (k-3)!3!
```

Simplificando:

```text
k(k-1)=
k(k-1)(k-2)/3
```

Multiplicando por 3:

```text
3k(k-1)=
k(k-1)(k-2)
```

Dividiendo por:

```text
k(k-1)
```

obtenemos:

```text
3=k-2
```

```text
k=5
```

### Verificación

```text
V(5,2)=20
```

```text
C(5,3)=10
```

```text
2·C(5,3)=20
```

Se verifica la igualdad.

### Respuesta

```text
k = 5
```

## Conclusión

Los ejercicios anteriores muestran aplicaciones de:

✓ Combinaciones ordinarias.

✓ Selección de grupos.

✓ Ecuaciones con combinaciones.

-----------------------

# Ejercicios Resueltos de Permutaciones

## Ejercicio 6

¿Cuántos números distintos de tres cifras pueden escribirse con los dígitos:

1, 5 y 7?

### Análisis

Se utilizan todos los dígitos disponibles.

El orden sí importa.

Por ejemplo:

```text
157 ≠ 751
```

### Identificación

PERMUTACIÓN SIMPLE

### Datos

```text
n = 3
```

### Fórmula

```text
P(n)=n!
```

### Desarrollo

```text
P(3)=3!

P(3)=3·2·1

P(3)=6
```

### Respuesta

```text
6 números distintos
```

---

## Ejercicio 7

¿De cuántas formas pueden sentarse 10 personas en una fila de butacas?

### Análisis

Participan todas las personas.

El orden sí importa.

No es lo mismo:

```text
ABCDEF...
```

que

```text
BACDEF...
```

### Identificación

PERMUTACIÓN SIMPLE

### Datos

```text
n = 10
```

### Fórmula

```text
P(n)=n!
```

### Desarrollo

```text
P(10)=10!

P(10)=3628800
```

### Respuesta

```text
3628800 formas
```

---

## Ejercicio 8

¿Cuántos números distintos pueden formarse con las cifras:

1,1,5,5,5?

### Análisis

Participan todas las cifras.

El orden importa.

Existen repeticiones:

```text
1 se repite 2 veces

5 se repite 3 veces
```

### Identificación

PERMUTACIÓN CON REPETICIÓN

### Datos

```text
n = 5

n₁ = 2

n₂ = 3
```

### Fórmula

```text
                 n!
P = -----------------------
     n₁! · n₂!
```

### Desarrollo

```text
            5!
P = ----------------
      2! · 3!

           120
P = -------------
        2 · 6

P = 10
```

### Respuesta

```text
10 números distintos
```

---

## Ejercicio 9

Con las letras de la palabra:

LIBRO

¿Cuántas palabras distintas pueden formarse?

### Análisis

La palabra tiene:

```text
L
I
B
R
O
```

Todas las letras son diferentes.

Se utilizan todas las letras.

El orden importa.

### Identificación

PERMUTACIÓN SIMPLE

### Datos

```text
n = 5
```

### Fórmula

```text
P(n)=n!
```

### Desarrollo

```text
P(5)=5!

P(5)=5·4·3·2·1

P(5)=120
```

### Respuesta

```text
120 palabras
```

---

## Ejercicio 10

¿De cuántas formas pueden sentarse 4 personas alrededor de una mesa circular?

### Análisis

Participan todas las personas.

El orden importa.

La disposición es circular.

Las rotaciones se consideran iguales.

### Identificación

PERMUTACIÓN CIRCULAR

### Datos

```text
n = 4
```

### Fórmula

```text
PC(n)=(n-1)!
```

### Desarrollo

```text
PC(4)=(4-1)!

PC(4)=3!

PC(4)=3·2·1

PC(4)=6
```

### Respuesta

```text
6 formas
```

## Conclusión

Los ejercicios anteriores muestran aplicaciones de:

✓ Permutaciones simples.

✓ Permutaciones con repetición.

✓ Permutaciones circulares.

---------------

# Ejercicios Resueltos de Variaciones

## Ejercicio 11

¿Cuántos números de tres cifras distintas pueden formarse con:

1, 2, 3, 4 y 5?

### Análisis

Se desea formar números de 3 cifras utilizando 5 dígitos disponibles.

El orden importa.

Por ejemplo:

```text
123 ≠ 321
```

No participan todos los elementos.

No se permiten repeticiones.

### Identificación

VARIACIÓN SIN REPETICIÓN

### Datos

```text
m = 5
n = 3
```

### Fórmula

```text
           m!
V(m,n) = --------
          (m-n)!
```

### Desarrollo

```text
           5!
V(5,3) = --------
          (5-3)!

           5!
V(5,3) = ----
            2!

V(5,3)=5·4·3

V(5,3)=60
```

### Respuesta

```text
60 números
```

---

## Ejercicio 12

¿De cuántas formas diferentes pueden cubrirse los cargos de presidente, vicepresidente y tesorero entre 12 candidatos?

### Análisis

Los cargos son distintos.

No es lo mismo ser presidente que tesorero.

El orden importa.

No participan todos los candidatos.

No existe repetición.

### Identificación

VARIACIÓN SIN REPETICIÓN

### Datos

```text
m = 12
n = 3
```

### Fórmula

```text
           m!
V(m,n) = --------
          (m-n)!
```

### Desarrollo

```text
            12!
V(12,3)=---------
           (12-3)!

            12!
V(12,3)=---------
              9!

V(12,3)=12·11·10

V(12,3)=1320
```

### Respuesta

```text
1320 formas
```

---

## Ejercicio 13

¿Cuántos números de tres cifras pueden formarse con:

1, 2, 3, 4 y 5

permitiendo repeticiones?

### Análisis

El orden importa.

Por ejemplo:

```text
123 ≠ 321
```

Los elementos pueden repetirse.

Por ejemplo:

```text
111
222
515
```

son válidos.

### Identificación

VARIACIÓN CON REPETICIÓN

### Datos

```text
m = 5
n = 3
```

### Fórmula

```text
VR(m,n)=mⁿ
```

### Desarrollo

```text
VR(5,3)=5³

VR(5,3)=125
```

### Respuesta

```text
125 números
```

---

## Ejercicio 14

Con el punto (•) y la raya (—) del sistema Morse:

¿Cuántas señales distintas pueden enviarse usando como máximo cuatro pulsaciones?

### Análisis

Solo existen dos símbolos:

```text
•
—
```

El orden importa.

Los símbolos pueden repetirse.

Las señales pueden tener:

```text
1 pulsación
2 pulsaciones
3 pulsaciones
4 pulsaciones
```

### Identificación

VARIACIÓN CON REPETICIÓN

### Datos

```text
m = 2

n = 1,2,3,4
```

### Fórmula

```text
VR(m,n)=mⁿ
```

### Desarrollo

Para una pulsación:

```text
VR(2,1)=2
```

Para dos pulsaciones:

```text
VR(2,2)=4
```

Para tres pulsaciones:

```text
VR(2,3)=8
```

Para cuatro pulsaciones:

```text
VR(2,4)=16
```

Total:

```text
2+4+8+16

=30
```

### Respuesta

```text
30 señales distintas
```

---

## Ejercicio 15

Resolver:

```text
V(x,4)=20V(x,2)
```

### Análisis

La incógnita aparece dentro de una expresión de variación.

Debemos utilizar la fórmula de variación sin repetición y resolver la ecuación.

### Identificación

ECUACIÓN CON VARIACIONES

### Fórmula

```text
           x!
V(x,n)=---------
         (x-n)!
```

### Desarrollo

Sustituyendo:

```text
           x!              x!
--------- = 20 · ---------
(x-4)!           (x-2)!
```

Simplificando:

```text
x(x-1)(x-2)(x-3)

=20x(x-1)
```

Dividiendo por:

```text
x(x-1)
```

obtenemos:

```text
(x-2)(x-3)=20
```

Desarrollando:

```text
x²-5x+6=20
```

```text
x²-5x-14=0
```

Buscamos dos números cuyo producto sea:

```text
-14
```

y cuya suma sea:

```text
-5
```

Factorizando:

```text
(x-7)(x+2)=0
```

Soluciones:

```text
x₁=7

x₂=-2
```

### Verificación

Para que exista:

V(x,4)

debe cumplirse:

x ≥ 4

Por lo tanto:

x = -2  ✗

No cumple la condición.

x = 7   ✓

Cumple la condición.

### Respuesta

```text
x = 7
```

## Conclusión

Los ejercicios anteriores muestran aplicaciones de:

✓ Variaciones sin repetición.

✓ Variaciones con repetición.

✓ Ecuaciones con variaciones.
