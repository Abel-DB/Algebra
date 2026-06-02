# Permutaciones

## Definición

Una permutación es una agrupación u ordenación de elementos en la que el orden sí importa.

Dos agrupaciones con los mismos elementos pero en diferente orden se consideran distintas.

Ejemplo:

ABC ≠ BAC

porque representan ordenaciones diferentes.

Por esta razón, cuando el orden importa, utilizamos permutaciones.

---

## Interpretación

Supongamos que se tienen tres letras:

A, B y C

Las posibles ordenaciones son:

ABC

ACB

BAC

BCA

CAB

CBA

Observamos que cada cambio de posición genera una nueva agrupación.

Por lo tanto:

✓ El orden importa.

---

# Permutaciones Sin Repetición

## Definición

Son agrupaciones donde:

* Intervienen todos los elementos.
* Ningún elemento se repite.
* El orden importa.

---

## Fórmula

```text
P(n) = n!
```

Donde:

* n = número total de elementos.

---

## Ejemplo

¿De cuántas formas pueden ordenarse 5 personas en una fila?

Datos:

```text
n = 5
```

Aplicando:

```text
P(5) = 5!

P(5) = 5·4·3·2·1

P(5) = 120
```

Respuesta:

```text
120 formas
```

---

# Aplicaciones

Las permutaciones sin repetición se utilizan en:

* Ordenamiento de personas.
* Formación de códigos.
* Organización de asientos.
* Distribución de objetos.

---

# Permutaciones Con Repetición

## Definición

Son agrupaciones donde algunos elementos pueden repetirse.

---

## Fórmula

```text
                 n!
P = -----------------------
     n₁! · n₂! · ... · nk!
```

Donde:

* n = número total de elementos.
* n₁, n₂, ..., nk = cantidad de repeticiones de cada elemento.

---

## Ejemplo

¿Cuántas palabras diferentes pueden formarse con la palabra:

MATEMATICA

Frecuencias:

```text
M = 2
A = 3
T = 2
E = 1
I = 1
C = 1
```

Total de letras:

```text
n = 10
```

Aplicando:

```text
              10!
P = ----------------
     2!·3!·2!
```

Resultado:

```text
P = 151200
```

Respuesta:

```text
151200 formas
```

---

# Aplicaciones

Las permutaciones con repetición se utilizan en:

* Formación de palabras.
* Ordenamiento de símbolos.
* Códigos con caracteres repetidos.

---

# Permutaciones Circulares

## Definición

Son agrupaciones donde los elementos se ordenan alrededor de una circunferencia.

Las rotaciones se consideran iguales.

---

## Fórmula

```text
PC(n) = (n - 1)!
```

---

## Ejemplo

¿De cuántas formas pueden sentarse 6 personas alrededor de una mesa redonda?

Datos:

```text
n = 6
```

Aplicando:

```text
PC(6) = (6 - 1)!

PC(6) = 5!

PC(6) = 120
```

Respuesta:

```text
120 formas
```

---

# Aplicaciones

Las permutaciones circulares se utilizan en:

* Distribución de personas en mesas redondas.
* Ubicación de objetos en círculos.
* Problemas de organización circular.

---

# Resumen

## Permutación Sin Repetición

```text
P(n) = n!
```

## Permutación Con Repetición

```text
                 n!
P = -----------------------
     n₁! · n₂! · ... · nk!
```

## Permutación Circular

```text
PC(n) = (n - 1)!
```

---

## Recordatorio

```text
ABC ≠ BAC
```

Cuando el orden importa, utilizamos permutaciones.
