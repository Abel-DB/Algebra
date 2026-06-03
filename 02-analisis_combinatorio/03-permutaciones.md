# Permutaciones

## Introducción

Las permutaciones son técnicas de conteo utilizadas en análisis combinatorio para determinar cuántas formas diferentes existen de ordenar elementos.

La característica principal de las permutaciones es que:

```text
EL ORDEN SÍ IMPORTA
```

Por ejemplo:

```text
ABC ≠ BAC
```

Aunque contienen las mismas letras, representan ordenaciones distintas.

---

# Definición

Una permutación es una agrupación u ordenación de elementos en la que el orden de colocación produce resultados diferentes.

Se utilizan cuando:

* El orden importa.
* Participan todos los elementos del conjunto.
* Se desea contar ordenaciones posibles.

---

# Interpretación

Supongamos los elementos:

```text
A, B, C
```

Las posibles ordenaciones son:

```text
ABC
ACB
BAC
BCA
CAB
CBA
```

Observamos que cambiar la posición genera una nueva ordenación.

Por ello:

```text
ABC ≠ BAC
```

---

# Permutaciones Simples (Sin Repetición)

## Definición

Son permutaciones donde:

* Intervienen todos los elementos.
* Ningún elemento se repite.
* El orden importa.

---

## Fórmula

```text
P(n)=n!
```

---

## Ejemplo 1

¿Cuántos números distintos de tres cifras pueden escribirse con los dígitos:

```text
1, 5 y 7
```

### Datos

```text
n = 3
```

### Sustitución

```text
P(3)=3!
```

### Desarrollo

```text
P(3)=3·2·1

P(3)=6
```

### Respuesta

```text
6 números distintos
```

---

## Ejemplo 2

¿De cuántas formas pueden sentarse 10 personas en una fila de butacas?

### Datos

```text
n = 10
```

### Sustitución

```text
P(10)=10!
```

### Desarrollo

```text
P(10)=10·9·8·7·6·5·4·3·2·1

P(10)=3628800
```

### Respuesta

```text
3628800 formas
```

---

# Permutaciones con Repetición

## Definición

Son permutaciones donde:

* Intervienen todos los elementos.
* Algunos elementos se repiten.
* El orden importa.

---

## Fórmula

```text
                 n!
P = -----------------------
     n₁!·n₂!·...·nk!
```

Donde:

```text
n₁+n₂+...+nk=n
```

---

## Ejemplo 1

¿Cuántos números distintos pueden formarse con:

```text
1,1,5,5,5
```

### Datos

```text
n = 5

1 → 2 veces
5 → 3 veces
```

### Sustitución

```text
        5!
P = --------
      2!·3!
```

### Desarrollo

```text
P = 120/12

P = 10
```

### Respuesta

```text
10 números distintos
```

---

## Ejemplo 2

¿Cuántos números diferentes pueden formarse con las cifras del número:

```text
458870
```

### Identificación

El dígito:

```text
8
```

se repite dos veces.

### Datos

```text
n = 6
```

### Sustitución

```text
       6!
P = -------
        2!
```

### Desarrollo

```text
P = 720/2

P = 360
```

### Respuesta

```text
360 números distintos
```

---

# Permutaciones Circulares

## Definición

Son ordenaciones de elementos alrededor de una circunferencia.

Las rotaciones se consideran iguales.

Por ello se fija un elemento y se ordenan los restantes.

---

## Fórmula

```text
PC(n)=(n-1)!
```

---

## Ejemplo

¿De cuántas formas pueden sentarse las personas:

```text
A, B, C y D
```

alrededor de una mesa circular?

### Datos

```text
n = 4
```

### Sustitución

```text
PC(4)=(4-1)!
```

### Desarrollo

```text
PC(4)=3!

PC(4)=3·2·1

PC(4)=6
```

### Respuesta

```text
6 formas
```

---

# Aplicaciones

Las permutaciones se utilizan en:

* Organización de personas.
* Distribución de asientos.
* Formación de palabras.
* Creación de códigos.
* Ordenamiento de objetos.
* Problemas de ubicación circular.

---

# ¿Cómo identificar una permutación?

Utilizamos permutaciones cuando:

✓ El orden importa.

✓ Intervienen todos los elementos.

✓ Cambiar la posición produce una nueva ordenación.

Ejemplos:

```text
ABC ≠ BAC
```

```text
Primer lugar ≠ Segundo lugar
```

```text
Asiento 1 ≠ Asiento 2
```

---

# Resumen

## Permutación Simple

```text
P(n)=n!
```

---

## Permutación con Repetición

```text
                 n!
P = -----------------------
     n₁!·n₂!·...·nk!
```

---

## Permutación Circular

```text
PC(n)=(n-1)!
```

---

## Regla de Oro

```text
Si intervienen todos los elementos y el orden importa,
estamos ante una permutación.
```
