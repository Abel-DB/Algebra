# Clasificación de Proposiciones

La clasificación de proposiciones consiste en analizar la columna final de una tabla de verdad para determinar el comportamiento lógico de una proposición.

Las proposiciones pueden clasificarse como:

* Tautología
* Contradicción
* Contingencia

---

## Tautología

Una tautología es una proposición que resulta verdadera en todos los casos posibles.

### Característica

Todos los valores de la columna final son verdaderos.

### Ejemplo

Proposición:

p ∨ ¬p

| p | ¬p | p ∨ ¬p |
| - | -- | ------ |
| V | F  | V      |
| F | V  | V      |

### Observación

Una tautología siempre será verdadera independientemente de los valores de las variables proposicionales.

---

## Contradicción

Una contradicción es una proposición que resulta falsa en todos los casos posibles.

### Característica

Todos los valores de la columna final son falsos.

### Ejemplo

Proposición:

p ∧ ¬p

| p | ¬p | p ∧ ¬p |
| - | -- | ------ |
| V | F  | F      |
| F | V  | F      |

### Observación

Una contradicción nunca puede ser verdadera.

---

## Contingencia

Una contingencia es una proposición que presenta tanto valores verdaderos como falsos.

### Característica

La columna final contiene una combinación de valores verdaderos y falsos.

### Ejemplo

Proposición:

p ∧ q

| p | q | p ∧ q |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

### Observación

La mayoría de las proposiciones que aparecen en ejercicios son contingencias.

---

## Comparación

| Clasificación | Resultado final |
| ------------- | --------------- |
| Tautología    | Todo V          |
| Contradicción | Todo F          |
| Contingencia  | Mezcla de V y F |

---

## Método de clasificación

Para clasificar una proposición:

1. Construir la tabla de verdad.
2. Identificar la última columna.
3. Analizar los resultados.

### Regla rápida

Si la última columna es:

* Todo V → Tautología
* Todo F → Contradicción
* V y F mezclados → Contingencia

---

## Ejemplos rápidos

### Ejemplo 1

| Resultado |
| --------- |
| V         |
| V         |
| V         |
| V         |

Clasificación:

**Tautología**

---

### Ejemplo 2

| Resultado |
| --------- |
| F         |
| F         |
| F         |
| F         |

Clasificación:

**Contradicción**

---

### Ejemplo 3

| Resultado |
| --------- |
| V         |
| F         |
| V         |
| F         |

Clasificación:

**Contingencia**

---

## Errores frecuentes

* Analizar una columna intermedia en lugar de la última.
* Construir incorrectamente la tabla de verdad.
* Confundir contingencia con contradicción.
* Clasificar sin verificar todos los resultados.

---

## Resumen

| Tipo          | Regla                      |
| ------------- | -------------------------- |
| Tautología    | Todos los resultados son V |
| Contradicción | Todos los resultados son F |
| Contingencia  | Existen V y F              |

### Ideas clave

* La clasificación se realiza utilizando la última columna de la tabla de verdad.
* Una tautología siempre es verdadera.
* Una contradicción siempre es falsa.
* Una contingencia puede ser verdadera o falsa según los valores de las variables.
