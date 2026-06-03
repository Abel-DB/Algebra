# Variaciones

## Definición

Una variación es una agrupación ordenada de elementos tomada de un conjunto.

En las variaciones:

* El orden sí importa.
* No necesariamente participan todos los elementos.

Por esta razón, dos agrupaciones con los mismos elementos pero en diferente orden se consideran distintas.

Ejemplo:

```text
AB ≠ BA
```

---

## Interpretación

Supongamos que se tienen los elementos:

```text
A, B y C
```

y se desea formar agrupaciones de 2 elementos.

Posibles agrupaciones:

```text
AB
AC
BA
BC
CA
CB
```

Observamos que:

```text
AB ≠ BA
```

porque el orden ha cambiado.

Por lo tanto:

✓ El orden importa.

✓ No se utilizan necesariamente todos los elementos.

---

# Variaciones Sin Repetición

## Definición

Son agrupaciones donde:

* El orden importa.
* Los elementos no pueden repetirse.
* No intervienen necesariamente todos los elementos.

---

## Fórmula

```text
           m!
V(m,n) = --------
          (m-n)!
```

Donde:

* m = número total de elementos.
* n = número de elementos seleccionados.

### Condición

```text
m ≥ n
```

---

## Ejemplo 1

¿Cuántos números de 3 cifras pueden formarse con:

```text
1, 2, 3, 4 y 5
```

sin repetir?

### Datos

```text
m = 5
n = 3
```

### Aplicando

```text
           5!
V(5,3) = --------
             2!

V(5,3)=5·4·3

V(5,3)=60
```

### Respuesta

```text
60 formas
```

---

## Ejemplo 2

¿De cuántas formas diferentes pueden cubrirse los puestos de presidente, vicepresidente y tesorero de un club si existen 12 candidatos?

### Datos

```text
m = 12
n = 3
```

### Aplicando

```text
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

## Aplicaciones

* Formación de códigos.
* Contraseñas sin repetición.
* Organización de posiciones.
* Asignación de cargos.
* Números sin repetición.

---

# Variaciones Con Repetición

## Definición

Son agrupaciones donde:

* El orden importa.
* Los elementos pueden repetirse.

---

## Fórmula

```text
VR(m,n)=mⁿ
```

Donde:

* m = número total de elementos disponibles.
* n = cantidad de posiciones.

### Condiciones

```text
m > 0
n > 0
```

No existe restricción entre ellos.

---

## Ejemplo 1

¿Cuántos números capicúas de cuatro cifras existen?

### Forma

```text
abba
```

con:

```text
a ≠ 0
```

### Aplicando

```text
VR(9,1) · VR(10,1)

= 9 · 10

= 90
```

### Respuesta

```text
90 números capicúas
```

---

## Ejemplo 2

Con el punto (•) y la raya (—) del sistema Morse,

¿cuántas señales distintas pueden enviarse usando como máximo cuatro pulsaciones?

### Aplicando

```text
VR(2,1)=2

VR(2,2)=4

VR(2,3)=8

VR(2,4)=16
```

### Total

```text
2+4+8+16

=30
```

### Respuesta

```text
30 señales distintas
```

---

## Aplicaciones

* PIN de seguridad.
* Contraseñas.
* Códigos de acceso.
* Matrículas.
* Identificadores.

---

# Ecuaciones con Variaciones

## Definición

Son ecuaciones en las cuales aparece una expresión de variación y se busca determinar el valor de una variable desconocida.

La incógnita puede encontrarse en:

* m
* n

o dentro de expresiones algebraicas asociadas.

---

## Fórmulas Utilizadas

### Variación Sin Repetición

```text
           m!
V(m,n) = --------
          (m-n)!
```

### Variación Con Repetición

```text
VR(m,n)=mⁿ
```

---

## Procedimiento General

1. Escribir la fórmula correspondiente.
2. Sustituir los datos conocidos.
3. Simplificar factoriales o potencias.
4. Resolver la ecuación resultante.
5. Verificar la solución obtenida.

---

## Ejemplo 1

Resolver:

```text
V(x,4)=20V(x,2)
```

### Soluciones

```text
x₁=-2

x₂=7
```

### Verificación

Como:

```text
m ≥ n
```

la solución válida es:

```text
x=7
```

---

## Ejemplo 2

Resolver:

```text
2V(x-1,2)-4=V(x+1,2)
```

### Soluciones

```text
x₁=0

x₂=7
```

### Verificación

La solución válida es:

```text
x=7
```

---

## Observación

Las ecuaciones con variaciones constituyen una aplicación de las variaciones ordinarias y de las variaciones con repetición.

---

# Diferencia con las Combinaciones

En una combinación:

```text
AB = BA
```

El orden no importa.

En una variación:

```text
AB ≠ BA
```

El orden sí importa.

---

# Diferencia con las Permutaciones

En una permutación:

```text
Se utilizan todos los elementos.
```

En una variación:

```text
Se utiliza solamente una parte de los elementos.
```

---

# Identificación de Problemas de Variaciones

Un problema es de variaciones cuando:

✓ El orden importa.

✓ No necesariamente participan todos los elementos.

✓ Puede existir o no repetición.

Ejemplos:

* Formación de códigos.
* Contraseñas.
* Asignación de cargos.
* Selección de campeón y subcampeón.
* Números de varias cifras.

---

# Resumen

## Variación Sin Repetición

```text
           m!
V(m,n) = --------
          (m-n)!
```

Condición:

```text
m ≥ n
```

---

## Variación Con Repetición

```text
VR(m,n)=mⁿ
```

Condiciones:

```text
m > 0
n > 0
```

---

## Regla de Oro

```text
AB ≠ BA
```

Cuando el orden importa y no necesariamente participan todos los elementos, se utilizan variaciones.
