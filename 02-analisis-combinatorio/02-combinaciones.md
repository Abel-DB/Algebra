# Combinaciones

## Introducción

El análisis combinatorio estudia técnicas de conteo que permiten determinar la cantidad de formas en que pueden organizarse o seleccionarse elementos.

Dentro del análisis combinatorio se encuentran tres herramientas fundamentales:

* Combinaciones
* Permutaciones
* Variaciones

En este tema estudiaremos las combinaciones.

---

## Definición

Una combinación es una selección o agrupación de elementos en la cual el orden no es importante.

Si dos grupos contienen los mismos elementos, se consideran iguales aunque estén escritos en distinto orden.

Ejemplo:

```text
AB = BA
```

porque contienen exactamente los mismos elementos.

Por esta razón, cuando el orden no importa, utilizamos combinaciones.

---

## Interpretación

Para identificar una combinación debemos responder la siguiente pregunta:

### ¿Importa el orden?

```text
NO
```

Si el orden no importa, estamos ante una combinación.

Ejemplo:

Se tienen tres estudiantes:

```text
A, B y C
```

y se desea formar grupos de dos estudiantes.

Posibles grupos:

```text
AB
AC
BC
```

Observemos que:

```text
AB = BA
```

Por lo tanto, el orden no genera una nueva agrupación.

---

# Combinaciones Ordinarias (Sin Repetición)

## Definición

Son agrupaciones formadas a partir de un conjunto de elementos donde:

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

### Condición

```text
n ≥ k
```

No es posible seleccionar más elementos de los que existen.

---

## Ejemplo

Seleccionar 5 cartas de un conjunto de 9 cartas.

Datos:

```text
n = 9
k = 5
```

Aplicando la fórmula:

```text
           9!
C(9,5) = ---------
         (9-5)!5!

           9!
C(9,5) = -------
          4!5!

C(9,5) = 126
```

Respuesta:

```text
126 formas
```

---

## Aplicaciones

Las combinaciones ordinarias se utilizan en:

* Formación de grupos.
* Comités.
* Jurados.
* Equipos deportivos.
* Sorteos.
* Selección de representantes.

---

# Combinaciones con Repetición

## Definición

Son agrupaciones formadas a partir de un conjunto de elementos donde:

* El orden no importa.
* Los elementos pueden repetirse.

---

## Fórmula

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

Donde:

* n = número de tipos de elementos.
* k = cantidad de elementos seleccionados.

---

## Ejemplo

Una pastelería ofrece 10 tipos de pasteles.

Se desea seleccionar 6 pasteles.

Datos:

```text
n = 10
k = 6
```

Aplicando:

```text
                 (10+6-1)!
CR(10,6) = ----------------
               6!(10-1)!

                 15!
CR(10,6) = -----------
               6!9!

CR(10,6) = 5005
```

Respuesta:

```text
5005 formas
```

---

## Aplicaciones

Las combinaciones con repetición se utilizan en:

* Selección de productos.
* Distribución de objetos.
* Problemas de inventario.
* Elección de artículos permitiendo repeticiones.

---

# Ecuaciones con Combinaciones

## Definición

Son ecuaciones en las cuales aparece una expresión combinatoria y se busca determinar el valor de una variable desconocida.

La incógnita puede encontrarse en:

* n
* k

o dentro de expresiones algebraicas asociadas a ellos.

---

## Fórmula Utilizada

Las ecuaciones con combinaciones utilizan la misma fórmula de las combinaciones ordinarias:

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

No existe una fórmula diferente para las ecuaciones con combinaciones.

La diferencia es que uno de los parámetros es desconocido y debe determinarse.

---

## Procedimiento General

Para resolver una ecuación con combinaciones:

1. Escribir la fórmula correspondiente.
2. Sustituir los datos conocidos.
3. Simplificar los factoriales.
4. Resolver la ecuación resultante.
5. Verificar la solución obtenida.

---

## Ejemplo de Ecuación con Combinaciones

Resolver:

```text
C(x,2) = 21
```

Aplicando la fórmula:

```text
          x!
C(x,2)= ---------
        (x-2)!2!
```

Sustituyendo:

```text
      x!
------------- = 21
 (x-2)!·2
```

Simplificando factoriales:

```text
x(x-1)
------ = 21
  2
```

Multiplicando por 2:

```text
x(x-1)=42
```

```text
x²-x-42=0
```

Factorizando:

```text
(x-7)(x+6)=0
```

Soluciones:

```text
x₁ = 7
x₂ = -6
```

Como en combinatoria no existen cantidades negativas de elementos:

```text
x = 7
```

---

## Observación

Las ecuaciones con combinaciones constituyen una aplicación de las combinaciones ordinarias.

En algunos casos pueden aparecer soluciones negativas o no enteras, pero únicamente se aceptan aquellas que tengan sentido dentro del contexto combinatorio.

---

# Identificación de Problemas de Combinación

Un problema es de combinaciones cuando:

✓ El orden no importa.

✓ Solo interesa la selección de elementos.

✓ Puede existir o no repetición.

Ejemplos:

* Formar un comité.
* Elegir representantes.
* Seleccionar estudiantes.
* Escoger cartas.
* Formar grupos de trabajo.

---

# Resumen General

## Combinación Ordinaria

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

Condición:

```text
n ≥ k
```

---

## Combinación con Repetición

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

---

## Regla de Oro

```text
AB = BA
```

El orden no importa.

Cuando el orden no importa, utilizamos combinaciones.
