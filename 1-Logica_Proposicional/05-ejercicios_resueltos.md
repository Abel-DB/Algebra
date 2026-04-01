# Ejercicios Resueltos

---

## Ejercicio 1
[(¬p → q) ∧ ¬q] → p

| p | q | ¬p | ¬q | ¬p → q | (¬p → q) ∧ ¬q | R |
|---|---|----|----|--------|---------------|---|
| V | V | F  | F  | V      | F             | V |
| V | F | F  | V  | V      | V             | V |
| F | V | V  | F  | V      | F             | V |
| F | F | V  | V  | F      | F             | V |

Clasificación: Tautología

---

## Ejercicio 2
(¬p → q) ↔ (¬p ∧ ¬q)

| p | q | ¬p | ¬q | ¬p → q | ¬p ∧ ¬q | R |
|---|---|----|----|--------|---------|---|
| V | V | F  | F  | V      | F       | F |
| V | F | F  | V  | V      | F       | F |
| F | V | V  | F  | V      | F       | F |
| F | F | V  | V  | F      | V       | F |

Clasificación: Contradicción

---

## Ejercicio 3
(p ↔ ¬q) ⊕ ¬(p ∧ q)

| p | q | ¬q | p↔¬q | p∧q | ¬(p∧q) | R |
|---|---|----|------|-----|--------|---|
| V | V | F  | F    | V   | F      | F |
| V | F | V  | V    | F   | V      | F |
| F | V | F  | V    | F   | V      | F |
| F | F | V  | F    | F   | V      | V |

Clasificación: Contingencia

---

## Ejercicio 4
[(p → ¬q) ∧ p] ⊕ (¬p ∧ q)

| p | q | ¬q | p→¬q | (p→¬q)∧p | ¬p∧q | R |
|---|---|----|------|----------|------|---|
| V | V | F  | F    | F        | F    | F |
| V | F | V  | V    | V        | F    | V |
| F | V | F  | V    | F        | V    | V |
| F | F | V  | V    | F        | F    | F |

Clasificación: Contingencia

---

## Ejercicio 5
[(¬p ⊕ q) → p] ∧ ¬(q → ¬p)

| p | q | ¬p | ¬p⊕q | (¬p⊕q)→p | q→¬p | ¬(q→¬p) | R |
|---|---|----|------|----------|------|---------|---|
| V | V | F  | V    | V        | F    | V       | V |
| V | F | F  | F    | V        | V    | F       | F |
| F | V | V  | F    | V        | V    | F       | F |
| F | F | V  | V    | F        | V    | F       | F |

Clasificación: Contingencia

---

## Ejercicio 6
[¬p → (¬q ∨ ¬p)] → [(p → ¬q) ∧ ¬q]

| p | q | ¬p | ¬q | ¬q∨¬p | ¬p→(...) | p→¬q | (p→¬q)∧¬q | R |
|---|---|----|----|--------|-----------|------|------------|---|
| V | V | F  | F  | F      | V         | F    | F          | F |
| V | F | F  | V  | V      | V         | V    | V          | V |
| F | V | V  | F  | V      | V         | V    | F          | F |
| F | F | V  | V  | V      | V         | V    | V          | V |

Clasificación: Contingencia

---

## Ejercicio 7
(p → q) ∧ (q → p)

| p | q | p→q | q→p | R |
|---|---|-----|-----|---|
| V | V | V   | V   | V |
| V | F | F   | V   | F |
| F | V | V   | F   | F |
| F | F | V   | V   | V |

Clasificación: Contingencia

---

## Ejercicio 8
(p → q) ∨ (q → p)

| p | q | p→q | q→p | R |
|---|---|-----|-----|---|
| V | V | V   | V   | V |
| V | F | F   | V   | V |
| F | V | V   | F   | V |
| F | F | V   | V   | V |

Clasificación: Tautología

---

## Ejercicio 9
(p ∧ q) → (p ∨ q)

| p | q | p∧q | p∨q | R |
|---|---|-----|-----|---|
| V | V | V   | V   | V |
| V | F | F   | V   | V |
| F | V | F   | V   | V |
| F | F | F   | F   | V |

Clasificación: Tautología

---

## Ejercicio 10
(p ∨ q) → (p ∧ q)

| p | q | p∨q | p∧q | R |
|---|---|-----|-----|---|
| V | V | V   | V   | V |
| V | F | V   | F   | F |
| F | V | V   | F   | F |
| F | F | F   | F   | V |

Clasificación: Contingencia

---

## Ejercicio 11
¬(p ∧ q) ↔ (¬p ∨ ¬q)

| p | q | p∧q | ¬(p∧q) | ¬p | ¬q | ¬p∨¬q | R |
|---|---|-----|--------|----|----|--------|---|
| V | V | V   | F      | F  | F  | F      | V |
| V | F | F   | V      | F  | V  | V      | V |
| F | V | F   | V      | V  | F  | V      | V |
| F | F | F   | V      | V  | V  | V      | V |

Clasificación: Tautología

---

## Ejercicio 12
¬(p ∨ q) ↔ (¬p ∧ ¬q)

| p | q | p∨q | ¬(p∨q) | ¬p | ¬q | ¬p∧¬q | R |
|---|---|-----|--------|----|----|--------|---|
| V | V | V   | F      | F  | F  | F      | V |
| V | F | V   | F      | F  | V  | F      | V |
| F | V | V   | F      | V  | F  | F      | V |
| F | F | F   | V      | V  | V  | V      | V |

Clasificación: Tautología

---

## Ejercicio 13
(p ⊕ q) ↔ ¬(p ↔ q)

| p | q | p⊕q | p↔q | ¬(p↔q) | R |
|---|---|-----|-----|--------|---|
| V | V | F   | V   | F      | V |
| V | F | V   | F   | V      | V |
| F | V | V   | F   | V      | V |
| F | F | F   | V   | F      | V |

Clasificación: Tautología

---

## Ejercicio 14
(p ∧ ¬q) ∨ (¬p ∧ q)

| p | q | ¬q | p∧¬q | ¬p | ¬p∧q | R |
|---|---|----|------|----|------|---|
| V | V | F  | F    | F  | F    | F |
| V | F | V  | V    | F  | F    | V |
| F | V | F  | F    | V  | V    | V |
| F | F | V  | F    | V  | F    | F |

Clasificación: Contingencia

---

## Ejercicio 15
(p → q) ∧ ¬q → ¬p

| p | q | p→q | ¬q | (p→q)∧¬q | ¬p | R |
|---|---|-----|----|-----------|----|---|
| V | V | V   | F  | F         | F  | V |
| V | F | F   | V  | F         | F  | V |
| F | V | V   | F  | F         | V  | V |
| F | F | V   | V  | V         | V  | V |

Clasificación: Tautología
