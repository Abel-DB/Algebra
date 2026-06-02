# Variaciones

## Definición

Una variación es una agrupación ordenada de elementos tomada de un conjunto.

En las variaciones:

* El orden sí importa.
* No necesariamente participan todos los elementos.

Por esta razón, dos agrupaciones con los mismos elementos pero en diferente orden se consideran distintas.

Ejemplo:

AB ≠ BA

---

## Interpretación

Supongamos que se tienen los elementos:

A, B y C

y se desea formar agrupaciones de 2 elementos.

Posibles agrupaciones:

AB

AC

BA

BC

CA

CB

Observamos que:

AB ≠ BA

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

Condición:

```text
m > n
```

---

## Ejemplo

¿Cuántos números de 3 cifras pueden formarse con:

1, 2, 3, 4 y 5

sin repetir?

Datos:

```text
m = 5
n = 3
```

Aplicando:

```text
           5!
V(5,3) = --------
          (5-3)!

           5!
V(5,3) = ----
            2!

V(5,3) = 60
```

Respuesta:

```text
60 formas
```

---

# Aplicaciones

Las variaciones sin repetición se utilizan en:

* Formación de códigos.
* Contraseñas.
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
VR(m,n) = mⁿ
```

Donde:

* m = número total de elementos disponibles.
* n = cantidad de posiciones.

Condición:

```text
m > 0
n > 0
```

No existe restricción entre ellos.

---

## Ejemplo

¿Cuántos códigos de 4 caracteres pueden formarse utilizando:

1, 2 y 3

permitiendo repeticiones?

Datos:

```text
m = 3
n = 4
```

Aplicando:

```text
VR(3,4) = 3⁴

VR(3,4) = 81
```

Respuesta:

```text
81 formas
```

---

# Aplicaciones

Las variaciones con repetición se utilizan en:

* PIN de seguridad.
* Contraseñas.
* Códigos de acceso.
* Matrículas.
* Identificadores.

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

# Resumen

## Variación Sin Repetición

```text
           m!
V(m,n) = --------
          (m-n)!
```

Condición:

```text
m > n
```

---

## Variación Con Repetición

```text
VR(m,n) = mⁿ
```

Condiciones:

```text
m > 0
n > 0
```

---

## Recordatorio

```text
AB ≠ BA
```

Cuando el orden importa y no necesariamente participan todos los elementos, se utilizan variaciones.
