# Comparación de Métodos

## Introducción

En Análisis Combinatorio existen tres métodos principales:

* Combinaciones
* Permutaciones
* Variaciones

La dificultad más común consiste en identificar cuál utilizar en cada problema.

Para ello debemos responder tres preguntas:

1. ¿Importa el orden?
2. ¿Se utilizan todos los elementos?
3. ¿Existe repetición?

---

# Tabla Comparativa

| Método        | ¿Importa el orden? | ¿Se usan todos los elementos? | ¿Puede existir repetición? |
| ------------- | ------------------ | ----------------------------- | -------------------------- |
| Combinaciones | No                 | No necesariamente             | Sí o No                    |
| Permutaciones | Sí                 | Sí                            | Sí o No                    |
| Variaciones   | Sí                 | No necesariamente             | Sí o No                    |

---

# Combinaciones

## Características

✓ El orden NO importa.

✓ Solo interesa la selección de elementos.

---

### Ejemplo

Seleccionar 3 estudiantes para formar un grupo.

```text
ABC = BAC = CAB
```

Todos representan el mismo grupo.

---

### Fórmulas

#### Sin Repetición

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

#### Con Repetición

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

---

# Permutaciones

## Características

✓ El orden SÍ importa.

✓ Intervienen todos los elementos.

---

### Ejemplo

Ordenar las letras:

```text
A B C
```

No es lo mismo:

```text
ABC
```

que

```text
BAC
```

---

### Fórmulas

#### Permutación Simple

```text
P(n) = n!
```

---

#### Permutación con Repetición

```text
                 n!
P = -----------------------
     n₁! · n₂! · ... · nk!
```

---

#### Permutación Circular

```text
PC(n) = (n-1)!
```

---

# Variaciones

## Características

✓ El orden SÍ importa.

✓ No necesariamente intervienen todos los elementos.

---

### Ejemplo

Formar códigos de 2 símbolos utilizando:

```text
A, B, C
```

Se consideran distintos:

```text
AB
BA
```

---

### Fórmulas

#### Variación Sin Repetición

```text
           m!
V(m,n) = --------
          (m-n)!
```

Condición:

```text
m ≥ n
```

---

#### Variación Con Repetición

```text
VR(m,n) = mⁿ
```

Condiciones:

```text
m > 0
n > 0
```

---

# Método de Identificación

Para resolver un ejercicio sigue el siguiente esquema:

## Paso 1

¿Importa el orden?

### Si NO

```text
→ Combinación
```

### Si SÍ

Continuar al paso 2.

---

## Paso 2

¿Se utilizan todos los elementos?

### Si SÍ

```text
→ Permutación
```

### Si NO

```text
→ Variación
```

---

# Ejemplos de Identificación

## Ejemplo 1

Elegir 4 estudiantes de un curso para formar una comisión.

```text
Orden NO importa
```

Resultado:

```text
→ Combinación
```

---

## Ejemplo 2

Asignar los cargos de presidente, vicepresidente y secretario entre 10 candidatos.

```text
Orden SÍ importa

No participan todos los candidatos
```

Resultado:

```text
→ Variación
```

---

## Ejemplo 3

Ordenar 8 libros diferentes en una repisa.

```text
Orden SÍ importa

Participan todos los elementos
```

Resultado:

```text
→ Permutación
```

---

# Resumen General de Fórmulas

## Combinación Sin Repetición

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

---

## Combinación Con Repetición

```text
               (n+k-1)!
CR(n,k) = ----------------
           k!(n-1)!
```

---

## Permutación Simple

```text
P(n) = n!
```

---

## Permutación Con Repetición

```text
                 n!
P = -----------------------
     n₁! · n₂! · ... · nk!
```

---

## Permutación Circular

```text
PC(n) = (n-1)!
```

---

## Variación Sin Repetición

```text
           m!
V(m,n) = --------
          (m-n)!
```

---

## Variación Con Repetición

```text
VR(m,n) = mⁿ
```

---

# Regla de Oro

```text
¿El orden NO importa?
→ Combinación

¿El orden importa y se usan todos los elementos?
→ Permutación

¿El orden importa y se usa solo una parte de los elementos?
→ Variación
```

---

# Conclusión

La clave para identificar correctamente un método combinatorio consiste en analizar:

✓ Si el orden importa.

✓ Si participan todos los elementos.

✓ Si existe repetición.

Responder estas preguntas permite seleccionar la fórmula adecuada y resolver correctamente cualquier problema de Análisis Combinatorio.
