# Tablas de Verdad

Las tablas de verdad son una herramienta fundamental en lógica proposicional que permiten determinar el valor de verdad de una proposición compuesta a partir de todas las combinaciones posibles de sus proposiciones simples.

---

## Número de filas

El número de filas de una tabla de verdad depende de la cantidad de proposiciones simples.

Se calcula con la fórmula:

Número de filas = 2^n

Donde:
- n = número de proposiciones

### Ejemplos

- 1 proposición → 2 filas
- 2 proposiciones → 4 filas
- 3 proposiciones → 8 filas
- 4 proposiciones → 16 filas

---

## Número de columnas

El número de columnas depende de:

Columnas = proposiciones simples + operaciones lógicas

### Ejemplo

Para (p ∨ q) ∧ ¬p:

- p, q → 2 columnas
- p ∨ q → 1 columna
- ¬p → 1 columna
- resultado final → 1 columna

Total: 5 columnas

---

## Orden de los valores de verdad

Es fundamental respetar el orden correcto para evitar errores.

---

### Para 2 proposiciones

| p | q |
|---|---|
| V | V |
| V | F |
| F | V |
| F | F |

---

### Para 3 proposiciones

| p | q | r |
|---|---|---|
| V | V | V |
| V | V | F |
| V | F | V |
| V | F | F |
| F | V | V |
| F | V | F |
| F | F | V |
| F | F | F |

---

## Método práctico (patrón)

Para construir rápidamente la tabla:

### Para 3 variables (p, q, r)

- p cambia cada 4 filas → V V V V / F F F F
- q cambia cada 2 filas → V V / F F / V V / F F
- r cambia cada 1 fila → V / F / V / F ...

---

## Procedimiento para construir una tabla de verdad

1. Identificar las proposiciones simples
2. Calcular el número de filas (2^n)
3. Construir las columnas base (p, q, r...)
4. Aplicar los conectores paso a paso
5. Obtener la columna final

---

## Ejemplo paso a paso

Proposición:

(p ∨ q) ∧ ¬p

---

### Paso 1: Variables

p, q → 2 variables

Número de filas = 2^2 = 4

---

### Paso 2: Tabla base

| p | q |
|---|---|
| V | V |
| V | F |
| F | V |
| F | F |

---

### Paso 3: Resolver operaciones

| p | q | p ∨ q | ¬p | Resultado |
|---|---|-------|----|----------|
| V | V | V     | F  | F        |
| V | F | V     | F  | F        |
| F | V | V     | V  | V        |
| F | F | F     | V  | F        |

---

## Interpretación de resultados

La última columna representa el valor final de la proposición.

Se utiliza para clasificarla como:

- Tautología
- Contradicción
- Contingencia

---

## Recomendaciones importantes

- Resolver siempre paso a paso
- No mezclar operaciones en una sola columna
- Verificar cada columna antes de continuar
- Usar paréntesis correctamente

---

## Errores comunes

- No respetar el orden de valores
- Calcular mal el número de filas
- Saltar pasos en operaciones
- Confundir conectores lógicos

---

## Importancia de las tablas de verdad

Permiten:

- Analizar proposiciones complejas
- Verificar razonamientos
- Identificar tipos de proposiciones
- Aplicar lógica en programación y matemática

---
