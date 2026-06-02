# Conectores Lógicos

Los conectores lógicos son símbolos que permiten combinar proposiciones simples para formar proposiciones compuestas.

Cada conector representa una operación lógica específica y posee una tabla de verdad asociada.

---

## Clasificación de conectores

Los principales conectores lógicos son:

* Negación (¬)
* Conjunción (∧)
* Disyunción (∨)
* Implicación (→)
* Bicondicional (↔)
* Disyunción exclusiva (⊕)

---

## Resumen de conectores

| Conector             | Símbolo | Lectura        |
| -------------------- | ------- | -------------- |
| Negación             | ¬       | No             |
| Conjunción           | ∧       | Y              |
| Disyunción           | ∨       | O              |
| Implicación          | →       | Si... entonces |
| Bicondicional        | ↔       | Si y solo si   |
| Disyunción exclusiva | ⊕       | O uno u otro   |

---

## Negación (¬p)

La negación cambia el valor de verdad de una proposición.

Se lee:

> "No p"

### Tabla de verdad

| p | ¬p |
| - | -- |
| V | F  |
| F | V  |

### Ejemplo

* p: "Llueve"
* ¬p: "No llueve"

---

## Conjunción (p ∧ q)

Representa la operación lógica:

> "p y q"

Solo es verdadera cuando ambas proposiciones son verdaderas.

### Tabla de verdad

| p | q | p ∧ q |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

### Ejemplo

* p: "Llueve"
* q: "Hace frío"

Proposición:

> "Llueve y hace frío"

---

## Disyunción (p ∨ q)

Representa la operación lógica:

> "p o q"

Es una disyunción inclusiva.

Es verdadera cuando al menos una proposición es verdadera.

### Tabla de verdad

| p | q | p ∨ q |
| - | - | ----- |
| V | V | V     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

### Ejemplo

* p: "Llueve"
* q: "Hace frío"

Proposición:

> "Llueve o hace frío"

### Observación

La disyunción sigue siendo verdadera cuando ambas proposiciones son verdaderas.

---

## Implicación (p → q)

Representa la relación:

> "Si p, entonces q"

Solo es falsa cuando la primera proposición es verdadera y la segunda es falsa.

### Tabla de verdad

| p | q | p → q |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | V     |
| F | F | V     |

### Ejemplo

* p: "Estudio"
* q: "Apruebo"

Proposición:

> "Si estudio, entonces apruebo"

### Observación

La implicación únicamente es falsa en el caso:

```text id="wsgxkh"
V → F
```

En cualquier otro caso será verdadera.

---

## Bicondicional (p ↔ q)

Representa la relación:

> "p si y solo si q"

Es verdadera cuando ambas proposiciones tienen el mismo valor de verdad.

### Tabla de verdad

| p | q | p ↔ q |
| - | - | ----- |
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | V     |

### Ejemplo

* p: "Hay luz"
* q: "El interruptor está encendido"

Proposición:

> "Hay luz si y solo si el interruptor está encendido"

---

## Disyunción exclusiva (p ⊕ q)

Representa la relación:

> "O bien p o bien q, pero no ambas"

Es verdadera únicamente cuando exactamente una proposición es verdadera.

### Tabla de verdad

| p | q | p ⊕ q |
| - | - | ----- |
| V | V | F     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

### Ejemplo

* p: "Voy al cine"
* q: "Voy a estudiar"

Proposición:

> "O voy al cine o voy a estudiar, pero no ambas cosas."

---

## Comparación entre disyunción y disyunción exclusiva

| Caso | p ∨ q | p ⊕ q |
| ---- | ----- | ----- |
| V, V | V     | F     |
| V, F | V     | V     |
| F, V | V     | V     |
| F, F | F     | F     |

---

## Jerarquía de operaciones lógicas

Cuando una expresión contiene varios conectores, se resuelve en el siguiente orden:

1. Paréntesis
2. Negación (¬)
3. Conjunción (∧)
4. Disyunción (∨)
5. Implicación (→)
6. Bicondicional (↔)

---

## Observaciones importantes

* La disyunción (∨) es inclusiva.
* La disyunción exclusiva (⊕) excluye que ambas proposiciones sean verdaderas.
* La implicación puede ser verdadera aunque la primera proposición sea falsa.
* Los paréntesis ayudan a evitar ambigüedades.
* La jerarquía de operadores debe respetarse al construir tablas de verdad.

---

## Resumen

| Símbolo | Nombre               |
| ------- | -------------------- |
| ¬       | Negación             |
| ∧       | Conjunción           |
| ∨       | Disyunción           |
| →       | Implicación          |
| ↔       | Bicondicional        |
| ⊕       | Disyunción exclusiva |

### Ideas clave

* ¬ cambia el valor de verdad.
* ∧ requiere ambas verdaderas.
* ∨ requiere al menos una verdadera.
* → solo es falsa cuando V → F.
* ↔ requiere igualdad de valores de verdad.
* ⊕ requiere exactamente una verdadera.
