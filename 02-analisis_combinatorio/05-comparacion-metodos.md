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

### Fórmula

Sin repetición:

```text
           n!
C(n,k) = ---------
         (n-k)! k!
```

Con repetición:

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

Permutación sin repetición:

```text
P(n) = n!
```

Permutación con repetición:

```text
                 n!
P = -----------------------
     n₁! · n₂! · ... · nk!
```

Permutación circular:

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

Variación sin repetición:

```text
           m!
V(m,n) = --------
          (m-n)!
```

Variación con repetición:

```text
VR(m,n) = mⁿ
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

## Permutación Sin Repetición

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
