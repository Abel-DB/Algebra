# Conectores Lógicos

Los conectores lógicos son símbolos que permiten combinar proposiciones simples para formar proposiciones compuestas.

Cada conector define una operación lógica específica y tiene una tabla de verdad asociada.

---

## Clasificación de conectores

Los principales conectores lógicos son:

- Negación
- Conjunción
- Disyunción
- Implicación
- Bicondicional
- Disyunción exclusiva

---

## Negación (~p)

La negación cambia el valor de verdad de una proposición.

Se lee: "no p"

### Tabla de verdad

| p | ~p |
|---|---|
| V | F |
| F | V |

### Ejemplo

- p: "Llueve"
- ~p: "No llueve"

---

## Conjunción (p ∧ q)

Representa la operación lógica "y".

Solo es verdadera cuando ambas proposiciones son verdaderas.

### Tabla de verdad

| p | q | p ∧ q |
|---|---|-------|
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

### Ejemplo

- p: "Llueve"
- q: "Hace frío"
- p ∧ q: "Llueve y hace frío"

---

## Disyunción (p ∨ q)

Representa la operación lógica "o" (inclusivo).

Es verdadera cuando al menos una proposición es verdadera.

### Tabla de verdad

| p | q | p ∨ q |
|---|---|-------|
| V | V | V     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

### Ejemplo

- p: "Llueve"
- q: "Hace frío"
- p ∨ q: "Llueve o hace frío"

---

## Implicación (p → q)

Representa la relación "si p, entonces q".

Solo es falsa cuando p es verdadera y q es falsa.

### Tabla de verdad

| p | q | p → q |
|---|---|-------|
| V | V | V     |
| V | F | F     |
| F | V | V     |
| F | F | V     |

### Ejemplo

- p: "Estudio"
- q: "Apruebo"
- p → q: "Si estudio, entonces apruebo"

---

## Bicondicional (p ↔ q)

Representa "p si y solo si q".

Es verdadera cuando ambas proposiciones tienen el mismo valor de verdad.

### Tabla de verdad

| p | q | p ↔ q |
|---|---|-------|
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | V     |

### Ejemplo

- p: "Hay luz"
- q: "El interruptor está encendido"
- p ↔ q: "Hay luz si y solo si el interruptor está encendido"

---

## Disyunción exclusiva (p ⊕ q)

Representa "o bien p o bien q, pero no ambos".

Es verdadera solo cuando exactamente una proposición es verdadera.

### Tabla de verdad

| p | q | p ⊕ q |
|---|---|-------|
| V | V | F     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

### Ejemplo

- p: "Voy al cine"
- q: "Voy a estudiar"
- p ⊕ q: "O voy al cine o voy a estudiar (pero no ambos)"

---

## Jerarquía de operaciones lógicas

Cuando una proposición tiene varios conectores, se resuelve en el siguiente orden:

1. Paréntesis
2. Negación (¬, ~)
3. Conjunción (∧)
4. Disyunción (∨)
5. Implicación (→)
6. Bicondicional (↔)

---

## Observaciones importantes

- La disyunción (∨) es inclusiva
- La disyunción exclusiva (⊕) excluye que ambas sean verdaderas
- La implicación puede ser verdadera aunque la primera proposición sea falsa
- Es importante usar paréntesis para evitar ambigüedades

---

## Ejemplo combinado

Proposición:

(p ∨ q) ∧ ~p

Interpretación:

"Ocurre p o q, y además no ocurre p"

---
