# Combinaciones

## Definición

Una combinación es una selección de elementos en la cual el orden no importa.

Si dos grupos contienen los mismos elementos, se consideran iguales aunque estén escritos en distinto orden.

Ejemplo:

AB = BA

porque contienen exactamente los mismos elementos.

Por esta razón, cuando el orden no importa, utilizamos combinaciones.

---

## Interpretación

Supongamos que se tienen tres estudiantes:

A, B y C

y se desea formar grupos de dos estudiantes.

Posibles grupos:

AB

AC

BC

Observemos que:

AB y BA representan el mismo grupo.

Por lo tanto, el orden no genera una nueva agrupación.

---

# Combinaciones Sin Repetición

## Definición

Son agrupaciones donde:

* El orden no importa.
* Los elementos no pueden repetirse.

---

## Fórmula

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

Donde:

* n = número total de elementos.
* k = número de elementos seleccionados.

---

## Ejemplo

Seleccionar 5 cartas de un conjunto de 9 cartas.

Datos:

n = 9

k = 5

```text
           9!
C(9,5) = ---------
         (9-5)! 5!

           9!
C(9,5) = -------
          4! 5!
```

Resultado:

```text
C(9,5) = 126
```

Respuesta:

126 formas.

---

## ¿De dónde surge la fórmula?

Las variaciones cuentan todas las formas posibles considerando el orden.

Sin embargo, en una combinación:

```text
ABC = BAC = CAB
```

Todas representan el mismo grupo.

Por ello se divide entre k! para eliminar las repeticiones producidas por el orden.

---

# Combinaciones Con Repetición

## Definición

Son agrupaciones donde:

* El orden no importa.
* Los elementos pueden repetirse.

---

## Fórmula

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

---

## Ejemplo

Una pastelería ofrece 10 tipos de pasteles.

Se desea seleccionar 6 pasteles.

Datos:

n = 10

k = 6

```text
                 (10+6-1)!
CR(10,6) = ----------------
               6!(10-1)!

                 15!
CR(10,6) = -----------
               6!9!
```

Resultado:

```text
CR(10,6) = 5005
```

Respuesta:

5005 formas.

---

# Aplicaciones

Las combinaciones se utilizan en:

* Formación de grupos.
* Equipos deportivos.
* Comités.
* Jurados.
* Selección de representantes.
* Sorteos.
* Juegos de cartas.

---

# ¿Cuándo Utilizar Combinaciones?

Utilizamos combinaciones cuando:

✓ El orden no importa.

✓ Solo interesa la selección de elementos.

✓ Puede existir o no repetición.

---

# Resumen

## Combinación Sin Repetición

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

## Combinación Con Repetición

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

## Recordatorio

```text
ABC = BAC = CAB
```

Todas representan el mismo grupo.

Por ello se utiliza una combinación y no una permutación o variación.
