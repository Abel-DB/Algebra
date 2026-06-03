# Tablas de Verdad

Las tablas de verdad son herramientas que permiten determinar el valor de verdad de una proposición compuesta a partir de los valores de verdad de sus proposiciones simples.

---

## ¿Para qué sirven?

Las tablas de verdad permiten:

* Analizar proposiciones compuestas.
* Verificar razonamientos lógicos.
* Clasificar proposiciones.
* Determinar equivalencias lógicas.

---

## Número de filas

El número de filas de una tabla de verdad depende de la cantidad de variables proposicionales.

### Fórmula

2^n

Donde:

* n = número de variables proposicionales.

### Ejemplos

| Variables | Filas |
| --------- | ----- |
| 1         | 2     |
| 2         | 4     |
| 3         | 8     |
| 4         | 16    |

---

## Construcción de valores de verdad

### Una variable

| p |
| - |
| V |
| F |

---

### Dos variables

| p | q |
| - | - |
| V | V |
| V | F |
| F | V |
| F | F |

---

### Tres variables

| p | q | r |
| - | - | - |
| V | V | V |
| V | V | F |
| V | F | V |
| V | F | F |
| F | V | V |
| F | V | F |
| F | F | V |
| F | F | F |

---

## Construcción de una tabla de verdad

### Ejemplo

Proposición:

p ∧ q

### Paso 1

Construir las columnas de las variables.

| p | q |
| - | - |
| V | V |
| V | F |
| F | V |
| F | F |

### Paso 2

Aplicar el conector lógico.

| p | q | p ∧ q |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

---

## Ejemplo con varios conectores

Proposición:

(p ∨ q) ∧ ¬p

### Paso 1

Construir las variables.

| p | q |
| - | - |
| V | V |
| V | F |
| F | V |
| F | F |

### Paso 2

Calcular ¬p.

| p | q | ¬p |
| - | - | -- |
| V | V | F  |
| V | F | F  |
| F | V | V  |
| F | F | V  |

### Paso 3

Calcular p ∨ q.

| p | q | p ∨ q |
| - | - | ----- |
| V | V | V     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

### Paso 4

Calcular (p ∨ q) ∧ ¬p.

| p | q | p ∨ q | ¬p | (p ∨ q) ∧ ¬p |
| - | - | ----- | -- | ------------ |
| V | V | V     | F  | F            |
| V | F | V     | F  | F            |
| F | V | V     | V  | V            |
| F | F | F     | V  | F            |

---

## Interpretación de resultados

La última columna de la tabla representa el valor de verdad final de la proposición.

Esta columna será utilizada posteriormente para clasificar la proposición como:

* Tautología.
* Contradicción.
* Contingencia.

---

## Recomendaciones

* Resolver primero las expresiones entre paréntesis.
* Aplicar la jerarquía de operadores lógicos.
* Trabajar una columna a la vez.
* Revisar cuidadosamente cada fila.

---

## Errores frecuentes

* Construir un número incorrecto de filas.
* Resolver varios conectores al mismo tiempo.
* Ignorar los paréntesis.
* Confundir el orden de los valores V y F.

---

## Resumen

* Una tabla de verdad muestra todos los posibles valores de una proposición.
* El número de filas depende de la cantidad de variables.
* La última columna contiene el resultado final.
* Las tablas de verdad permiten clasificar proposiciones y analizar razonamientos.
