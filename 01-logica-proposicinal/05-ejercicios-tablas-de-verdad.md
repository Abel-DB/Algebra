# Ejercicios Resueltos de Tablas de Verdad

## Ejercicio 1

[(¬p → q) ∧ ¬q] → p

| p | q | ¬p | ¬q | ¬p → q | (¬p → q) ∧ ¬q | R |
| - | - | -- | -- | ------ | ------------- | - |
| V | V | F  | F  | V      | F             | V |
| V | F | F  | V  | V      | V             | V |
| F | V | V  | F  | V      | F             | V |
| F | F | V  | V  | F      | F             | V |

**Clasificación:** Tautología

---

## Ejercicio 2

(¬p → q) ↔ (¬p ∧ ¬q)

| p | q | ¬p | ¬q | ¬p → q | ¬p ∧ ¬q | R |
| - | - | -- | -- | ------ | ------- | - |
| V | V | F  | F  | V      | F       | F |
| V | F | F  | V  | V      | F       | F |
| F | V | V  | F  | V      | F       | F |
| F | F | V  | V  | F      | V       | F |

**Clasificación:** Contradicción

---

## Ejercicio 3

(p ↔ ¬q) ⊕ ¬(p ∧ q)

| p | q | ¬q | p ↔ ¬q | p ∧ q | ¬(p ∧ q) | R |
| - | - | -- | ------ | ----- | -------- | - |
| V | V | F  | F      | V     | F        | F |
| V | F | V  | V      | F     | V        | F |
| F | V | F  | V      | F     | V        | F |
| F | F | V  | F      | F     | V        | V |

**Clasificación:** Contingencia

---

## Ejercicio 4

[(p → ¬q) ∧ p] ⊕ (¬p ∧ q)

| p | q | ¬q | p → ¬q | (p → ¬q) ∧ p | ¬p ∧ q | R |
| - | - | -- | ------ | ------------ | ------ | - |
| V | V | F  | F      | F            | F      | F |
| V | F | V  | V      | V            | F      | V |
| F | V | F  | V      | F            | V      | V |
| F | F | V  | V      | F            | F      | F |

**Clasificación:** Contingencia

---

## Ejercicio 5

[(¬p ⊕ q) → p] ∧ ¬(q → ¬p)

| p | q | ¬p | ¬p ⊕ q | (¬p ⊕ q) → p | q → ¬p | ¬(q → ¬p) | R |
| - | - | -- | ------ | ------------ | ------ | --------- | - |
| V | V | F  | V      | V            | F      | V         | V |
| V | F | F  | F      | V            | V      | F         | F |
| F | V | V  | F      | V            | V      | F         | F |
| F | F | V  | V      | F            | V      | F         | F |

**Clasificación:** Contingencia

---

## Ejercicio 6

[¬p → (¬q ∨ ¬p)] → [(p → ¬q) ∧ ¬q]

| p | q | ¬p | ¬q | ¬q ∨ ¬p | ¬p → (¬q ∨ ¬p) | p → ¬q | (p → ¬q) ∧ ¬q | R |
| - | - | -- | -- | ------- | -------------- | ------ | ------------- | - |
| V | V | F  | F  | F       | V              | F      | F             | F |
| V | F | F  | V  | V       | V              | V      | V             | V |
| F | V | V  | F  | V       | V              | V      | F             | F |
| F | F | V  | V  | V       | V              | V      | V             | V |

**Clasificación:** Contingencia

---

## Ejercicio 7

[(¬p ∧ q) → ¬r] ↔ [r ∧ ¬(p ∨ ¬q)]

| p | q | r | ¬p | ¬q | ¬r | ¬p∧q | (¬p∧q)→¬r | p∨¬q | ¬(p∨¬q) | r∧¬(p∨¬q) | R |
| - | - | - | -- | -- | -- | ---- | --------- | ---- | ------- | --------- | - |
| V | V | V | F  | F  | F  | F    | V         | V    | F       | F         | F |
| V | V | F | F  | F  | V  | F    | V         | V    | F       | F         | F |
| V | F | V | F  | V  | F  | F    | V         | V    | F       | F         | F |
| V | F | F | F  | V  | V  | F    | V         | V    | F       | F         | F |
| F | V | V | V  | F  | F  | V    | F         | F    | V       | V         | F |
| F | V | F | V  | F  | V  | V    | V         | F    | V       | F         | F |
| F | F | V | V  | V  | F  | F    | V         | V    | F       | F         | F |
| F | F | F | V  | V  | V  | F    | V         | V    | F       | F         | F |

**Clasificación:** Contradicción

---

## Ejercicio 8

[(p → ¬r) ∧ (p → ¬q)] ∨ [(¬p → r) → ¬q]

| p | q | r | p→¬r | p→¬q | (p→¬r)∧(p→¬q) | ¬p→r | (¬p→r)→¬q | R |
| - | - | - | ---- | ---- | ------------- | ---- | --------- | - |
| V | V | V | F    | F    | F             | V    | F         | F |
| V | V | F | V    | F    | F             | V    | F         | F |
| V | F | V | F    | V    | F             | V    | V         | V |
| V | F | F | V    | V    | V             | V    | V         | V |
| F | V | V | V    | V    | V             | V    | F         | V |
| F | V | F | V    | V    | V             | F    | V         | V |
| F | F | V | V    | V    | V             | V    | V         | V |
| F | F | F | V    | V    | V             | F    | V         | V |

**Clasificación:** Contingencia

---

## Ejercicio 9

[(¬p ∧ ¬r) ∨ q] ↔ [(r ∨ p) → ¬q]

| p | q | r | ¬p | ¬r | ¬p∧¬r | (¬p∧¬r)∨q | r∨p | ¬q | (r∨p)→¬q | R |
| - | - | - | -- | -- | ----- | --------- | --- | -- | -------- | - |
| V | V | V | F  | F  | F     | V         | V   | F  | F        | F |
| V | V | F | F  | V  | F     | V         | V   | F  | F        | F |
| V | F | V | F  | F  | F     | F         | V   | V  | V        | F |
| V | F | F | F  | V  | F     | F         | V   | V  | V        | F |
| F | V | V | V  | F  | F     | V         | V   | F  | F        | F |
| F | V | F | V  | V  | V     | V         | F   | F  | V        | V |
| F | F | V | V  | F  | F     | F         | V   | V  | V        | F |
| F | F | F | V  | V  | V     | V         | F   | V  | V        | V |

**Clasificación:** Contingencia

---

## Ejercicio 10

[(p → q) ↔ r] ∧ [(p ∨ r) → (¬r ∧ p)]

| p | q | r | p→q | (p→q)↔r | p∨r | ¬r | ¬r∧p | (p∨r)→(¬r∧p) | R |
| - | - | - | --- | ------- | --- | -- | ---- | ------------ | - |
| V | V | V | V   | V       | V   | F  | F    | F            | F |
| V | V | F | V   | F       | V   | V  | V    | V            | F |
| V | F | V | F   | F       | V   | F  | F    | F            | F |
| V | F | F | F   | V       | V   | V  | V    | V            | V |
| F | V | V | V   | V       | V   | F  | F    | F            | F |
| F | V | F | V   | F       | F   | V  | F    | V            | F |
| F | F | V | V   | V       | V   | F  | F    | F            | F |
| F | F | F | V   | F       | F   | V  | F    | V            | F |

**Clasificación:** Contingencia
