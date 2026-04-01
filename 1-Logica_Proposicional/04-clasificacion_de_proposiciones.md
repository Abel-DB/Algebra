# Clasificación de Proposiciones

Las proposiciones compuestas pueden clasificarse según los valores de verdad que toman en su tabla de verdad.

Esta clasificación se realiza observando la columna final (resultado).

---

## Tautología

Una tautología es una proposición que siempre es verdadera, sin importar los valores de verdad de las proposiciones simples.

### Característica

- Todos los valores en la tabla final son verdaderos (V)

### Ejemplo

Proposición:
p ∨ ~p

| p | ~p | Resultado |
|---|----|----------|
| V | F  | V        |
| F | V  | V        |

### Interpretación

Siempre ocurre, independientemente del valor de p.

---

## Contradicción

Una contradicción es una proposición que siempre es falsa.

### Característica

- Todos los valores en la tabla final son falsos (F)

### Ejemplo

Proposición:
p ∧ ¬p

| p | ~p | Resultado |
|---|----|----------|
| V | F  | F        |
| F | V  | F        |

### Interpretación

Nunca puede cumplirse.

---

## Contingencia

Una contingencia es una proposición que puede ser verdadera o falsa dependiendo de los valores de sus variables.

### Característica

- La tabla final contiene valores verdaderos y falsos

### Ejemplo

Proposición:
p ∧ q

| p | q | Resultado |
|---|---|----------|
| V | V | V        |
| V | F | F        |
| F | V | F        |
| F | F | F        |

---

## Método para clasificar proposiciones

1. Construir la tabla de verdad
2. Observar la última columna

### Resultado:

- Todos V → Tautología
- Todos F → Contradicción
- Mezcla de V y F → Contingencia

---

## Importancia de la clasificación

Permite:

- Determinar la validez de expresiones lógicas
- Identificar proposiciones siempre verdaderas
- Detectar contradicciones
- Analizar razonamientos

---

## Ejemplos adicionales

### Ejemplo 1

Proposición:
p → p

Resultado: siempre verdadero → Tautología

---

### Ejemplo 2

Proposición:
(p ∧ q) → p

Resultado: siempre verdadero → Tautología

---

### Ejemplo 3

Proposición:
p ⊕ p

Resultado: siempre falso → Contradicción

---

## Relación con tablas de verdad

La clasificación depende directamente de la tabla de verdad.

Sin construir la tabla, no se puede determinar con certeza el tipo de proposición.

---

## Resumen

- Tautología: siempre verdadera
- Contradicción: siempre falsa
- Contingencia: combinación de valores

---
