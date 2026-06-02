# EJERCICIOS MIXTOS ELEMENTALES

# EJERCICIO 1

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

K = (2x + 3)³

W = (1 - 5x)³

Tomando en cuenta que la constante de K y W se incrementan en 1. Si ese resultado es par se considera verdadero; en su defecto, falso.

Verificar si se cumple el verdadero para la implicación, con K antecedente y W consecuente.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Producto notable: Cubo de un binomio.
* Identificación de la constante de un polinomio.
* Paridad de números enteros.
* Implicación lógica.

### Procedimientos algebraicos

### Desarrollo de K

K = (2x + 3)³

Aplicando:

(a + b)³ = a³ + 3a²b + 3ab² + b³

K = (2x)³ + 3(2x)²(3) + 3(2x)(3)² + 3³

K = 8x³ + 36x² + 54x + 27

∴ Cₖ = 27

---

### Desarrollo de W

W = (1 - 5x)³

Aplicando:

(a - b)³ = a³ - 3a²b + 3ab² - b³

W = 1 - 15x + 75x² - 125x³

∴ Cw = 1

---

## Paso N° 2: Verificación

### Aplicación de la condición

Las constantes se incrementan en 1.

Para K:

27 + 1 = 28

28 es par.

∴ K = V

Para W:

1 + 1 = 2

2 es par.

∴ W = V

### Tabla proposicional

K → W

| K | W | K→W |
| - | - | --- |
| V | V | V   |
| V | F | F   |
| F | V | V   |
| F | F | V   |

### Matemáticamente

Se obtienen:

* 3 valores verdaderos.
* 1 valor falso.

### Proposicionalmente

K → W = V

∴ La implicación es verdadera.

---

# EJERCICIO 2

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

K = (1 - 7x)³

W = (2 + 5x)³

Tomando en cuenta que las constantes de K y W triplican su valor. Si ese resultado es impar se considera falso; en su defecto verdadero.

Verificar si se cumple el verdadero para la disyunción exclusiva con K antecedente y W consecuente.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Producto notable: Cubo de un binomio.
* Identificación de la constante de un polinomio.
* Paridad de números enteros.
* Disyunción exclusiva.

### Procedimientos algebraicos

### Desarrollo de K

K = (1 - 7x)³

Aplicando:

(a - b)³ = a³ - 3a²b + 3ab² - b³

K = 1 - 21x + 147x² - 343x³

∴ Cₖ = 1

---

### Desarrollo de W

W = (2 + 5x)³

Aplicando:

(a + b)³ = a³ + 3a²b + 3ab² + b³

W = 8 + 60x + 150x² + 125x³

∴ Cw = 8

---

## Paso N° 2: Verificación

### Aplicación de la condición

Las constantes triplican su valor.

Para K:

3(1) = 3

3 es impar.

∴ K = F

Para W:

3(8) = 24

24 es par.

∴ W = V

### Tabla proposicional

K ⊕ W

| K | W | K⊕W |
| - | - | --- |
| V | V | F   |
| V | F | V   |
| F | V | V   |
| F | F | F   |

### Matemáticamente

Se obtienen:

* 2 valores verdaderos.
* 2 valores falsos.

### Proposicionalmente

K ⊕ W = V

### Por lo tanto

La disyunción exclusiva es verdadera.

---

# EJERCICIO 3

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

K = (2x + 1/3)³

W = (5 - 2x/3)³

Tomando en cuenta que las constantes de K y W duplican su valor más 1. Si ese resultado es par se considera verdadero; en su defecto, falso.

Verificar si se cumple el verdadero para la doble implicación con K consecuente y W antecedente.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Producto notable: Cubo de un binomio.
* Operaciones con fracciones.
* Identificación de la constante de un polinomio.
* Paridad de números.
* Bicondicional o doble implicación.

### Procedimientos algebraicos

### Desarrollo de K

K = (2x + 1/3)³

Aplicando:

(a + b)³ = a³ + 3a²b + 3ab² + b³

K = 8x³ + 4x² + (2/3)x + 1/27

∴ Cₖ = 1/27

---

### Desarrollo de W

W = (5 - 2x/3)³

Aplicando:

(a - b)³ = a³ - 3a²b + 3ab² - b³

W = 125 - 50x + (20/3)x² - (8/27)x³

∴ Cw = 125

---

## Paso N° 2: Verificación

### Aplicación de la condición

Para K:

2(1/27) + 1

= 2/27 + 27/27

= 29/27

29/27 no es par.

∴ K = F

Para W:

2(125) + 1

= 251

251 es impar.

∴ W = F

### Tabla proposicional

W ↔ K

| W | K | W↔K |
| - | - | --- |
| V | V | V   |
| V | F | F   |
| F | V | F   |
| F | F | V   |

### Matemáticamente

Se obtienen:

* 2 valores verdaderos.
* 2 valores falsos.

### Proposicionalmente

W ↔ K = V

### Por lo tanto

La doble implicación es verdadera.

---

# EJERCICIO 4

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

(X³ + 125) = 0

(Y² - 4) = 0

Si la mayoría (o partes iguales) de los valores de X son números reales, X se considera verdadero; en su defecto falso.

Si la mayoría (o partes iguales) de los valores de Y son números reales, Y se considera falso; en su defecto verdadero.

Verificar si X o Y generan como resultado proposicional la validación falsa.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Ecuaciones polinómicas.
* Factorización por suma de cubos.
* Factorización por diferencia de cuadrados.
* Fórmula general.
* Propiedad del producto nulo.
* Determinación de raíces reales y complejas.
* Disyunción lógica.

### Procedimientos algebraicos

### Resolución de X

Conceptos aplicados:

* Suma de cubos.
* Fórmula general.

X³ + 125 = 0

X³ + 5³ = 0

Aplicando:

a³ + b³ = (a + b)(a² - ab + b²)

(X + 5)(X² - 5X + 25) = 0

Aplicando la propiedad del producto nulo:

X + 5 = 0

X = -5

Para el segundo factor:

X² - 5X + 25 = 0

Aplicando fórmula general:

x = (-b ± √(b² - 4ac))/2a

Donde:

a = 1

b = -5

c = 25

x = (5 ± √(25 - 100))/2

x = (5 ± √(-75))/2

x = (5 ± 5√3 i)/2

Valores de X:

X₁ = -5

X₂ = (5 + 5√3 i)/2

X₃ = (5 - 5√3 i)/2

Cantidad de soluciones reales = 1

Cantidad de soluciones complejas = 2

La mayoría de las soluciones son complejas.

---

### Resolución de Y

Concepto aplicado:

* Diferencia de cuadrados.

Y² - 4 = 0

Y² - 2² = 0

Aplicando:

a² - b² = (a - b)(a + b)

(Y - 2)(Y + 2) = 0

Aplicando la propiedad del producto nulo:

Y = 2

Y = -2

Valores de Y:

Y₁ = 2

Y₂ = -2

Cantidad de soluciones reales = 2

---

## Paso N° 2: Verificación

### Aplicación de la condición

#### Para X

La mayoría de los valores no son reales.

∴ X = F

#### Para Y

La mayoría de los valores son reales.

Según la condición:

∴ Y = F

### Tabla proposicional

X ∨ Y

| X | Y | X∨Y |
| - | - | --- |
| V | V | V   |
| V | F | V   |
| F | V | V   |
| F | F | F   |

### Matemáticamente

Se obtienen:

* 3 valores verdaderos.
* 1 valor falso.

### Proposicionalmente

X = F

Y = F

X ∨ Y = F

### Verificación solicitada

Se pidió verificar si generan una validación falsa.

Como:

X ∨ Y = F

### Por lo tanto

La validación proposicional es falsa.

---

# EJERCICIO 5

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

(X³ - 27) = 0

(Y² - 25) = 0

Si la mayoría (o partes iguales) de los valores de X son números complejos, X se considera verdadero; en su defecto falso.

Si la mayoría (o partes iguales) de los valores de Y son números reales, Y se considera falso; en su defecto verdadero.

Verificar si X y Y generan como resultado proposicional la validación verdadera.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Ecuaciones polinómicas.
* Factorización por diferencia de cubos.
* Factorización por diferencia de cuadrados.
* Fórmula general.
* Propiedad del producto nulo.
* Determinación de raíces reales y complejas.
* Conjunción lógica.

### Procedimientos algebraicos

### Resolución de X

Conceptos aplicados:

* Diferencia de cubos.
* Fórmula general.

X³ - 27 = 0

X³ - 3³ = 0

Aplicando:

a³ - b³ = (a - b)(a² + ab + b²)

(X - 3)(X² + 3X + 9) = 0

Aplicando la propiedad del producto nulo:

X = 3

Para el segundo factor:

X² + 3X + 9 = 0

Aplicando fórmula general:

x = (-3 ± √(9 - 36))/2

x = (-3 ± √(-27))/2

x = (-3 ± 3√3 i)/2

Valores de X:

X₁ = 3

X₂ = (-3 + 3√3 i)/2

X₃ = (-3 - 3√3 i)/2

Cantidad de valores reales = 1

Cantidad de valores complejos = 2

---

### Resolución de Y

Concepto aplicado:

* Diferencia de cuadrados.

Y² - 25 = 0

Y² - 5² = 0

Aplicando:

a² - b² = (a - b)(a + b)

(Y - 5)(Y + 5) = 0

Aplicando la propiedad del producto nulo:

Y = 5

Y = -5

Valores de Y:

Y₁ = 5

Y₂ = -5

Cantidad de valores reales = 2

---

## Paso N° 2: Verificación

### Aplicación de la condición

#### Para X

Cantidad de complejos = 2

Cantidad de reales = 1

La mayoría son complejos.

∴ X = V

#### Para Y

La mayoría son reales.

Según la condición:

∴ Y = F

### Tabla proposicional

X ∧ Y

| X | Y | X∧Y |
| - | - | --- |
| V | V | V   |
| V | F | F   |
| F | V | F   |
| F | F | F   |

### Matemáticamente

Se obtienen:

* 1 valor verdadero.
* 3 valores falsos.

### Proposicionalmente

X = V

Y = F

X ∧ Y = F

### Verificación solicitada

Se pidió verificar si generan una validación verdadera.

Como:

X ∧ Y = F

No generan una validación verdadera.

### Por lo tanto

La conjunción es falsa.

---

# EJERCICIO 6

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

K = (X + 1)(2X − 3)³

W = (1 + 3X)³

Tomando en cuenta que a la constante K y W se le triplica su valor; si ese valor es impar se considera falso, en su defecto verdadero.

Verificar si se cumple el verdadero para la implicación, con K antecedente y W consecuente.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Producto notable: Cubo de un binomio.
* Multiplicación de polinomios.
* Identificación de la constante de un polinomio.
* Paridad de números enteros.
* Implicación lógica.

### Procedimientos algebraicos

### Desarrollo de K

K = (X + 1)(2X − 3)³

Primero desarrollamos:

(2X − 3)³

Aplicando:

(a − b)³ = a³ − 3a²b + 3ab² − b³

(2X − 3)³

= (2X)³ − 3(2X)²(3) + 3(2X)(3)² − 3³

= 8X³ − 36X² + 54X − 27

Ahora multiplicamos:

K = (X + 1)(8X³ − 36X² + 54X − 27)

K = 8X⁴ − 36X³ + 54X² − 27X + 8X³ − 36X² + 54X − 27

K = 8X⁴ − 28X³ + 18X² + 27X − 27

Por lo tanto:

Ck = −27

---

### Desarrollo de W

W = (1 + 3X)³

Aplicando:

(a + b)³ = a³ + 3a²b + 3ab² + b³

W

= 1³ + 3(1)²(3X) + 3(1)(3X)² + (3X)³

= 1 + 9X + 27X² + 27X³

Por lo tanto:

Cw = 1

---

## Paso N° 2: Verificación

### Aplicación de la condición

Las constantes triplican su valor.

#### Para K

3(−27) = −81

−81 es impar.

∴ K = F

#### Para W

3(1) = 3

3 es impar.

∴ W = F

---

### Tabla proposicional

K → W

| K | W | K→W |
| - | - | --- |
| V | V | V   |
| V | F | F   |
| F | V | V   |
| F | F | V   |

### Matemáticamente

Se obtienen:

* 3 valores verdaderos.
* 1 valor falso.

### Proposicionalmente

K = F

W = F

K → W = V

---

### Por lo tanto

La implicación con K antecedente y W consecuente es verdadera.

---

# EJERCICIO 7

## Enunciado

Se tienen los siguientes modelos matemáticos y proposicionales:

(X³ − 125)(X² − 4) = 0

(Y² − 49)(27Y³ + 1000) = 0

Si la mayoría (o partes iguales) de los valores de X son números reales, X se considera verdadero; en su defecto falso.

Si la mayoría (o partes iguales) de los valores de Y son números reales, Y se considera falso; en su defecto verdadero.

Verificar si X entonces Y generan como resultado proposicional la validación verdadera.

---

# Solución

## Paso N° 1: Análisis preliminar

### Conceptos algebraicos aplicados

* Diferencia de cubos.
* Diferencia de cuadrados.
* Suma de cubos.
* Fórmula general.
* Propiedad del producto nulo.
* Números reales y complejos.
* Implicación lógica.

### Procedimientos algebraicos

### Resolución de X

(X³ − 125)(X² − 4) = 0

Aplicando diferencia de cubos:

X³ − 125

= X³ − 5³

= (X − 5)(X² + 5X + 25)

Aplicando diferencia de cuadrados:

X² − 4

= (X − 2)(X + 2)

Entonces:

(X − 5)(X² + 5X + 25)(X − 2)(X + 2) = 0

Soluciones reales:

X₁ = 5

X₂ = 2

X₃ = −2

Ahora resolvemos:

X² + 5X + 25 = 0

Aplicando fórmula general:

x = (-5 ± √(25 − 100))/2

x = (-5 ± √(-75))/2

x = (-5 ± 5√3 i)/2

Soluciones complejas conjugadas:

X₄ = (-5 + 5√3 i)/2

X₅ = (-5 − 5√3 i)/2

Cantidad de soluciones:

* Reales = 3
* Complejas = 2

La mayoría son reales.

∴ X = V

---

### Resolución de Y

(Y² − 49)(27Y³ + 1000) = 0

Aplicando diferencia de cuadrados:

Y² − 49

= (Y − 7)(Y + 7)

Aplicando suma de cubos:

27Y³ + 1000

= (3Y)³ + 10³

= (3Y + 10)(9Y² − 30Y + 100)

Entonces:

(Y − 7)(Y + 7)(3Y + 10)(9Y² − 30Y + 100) = 0

Soluciones reales:

Y₁ = 7

Y₂ = −7

Y₃ = −10/3

Ahora resolvemos:

9Y² − 30Y + 100 = 0

Aplicando fórmula general:

y = (30 ± √(900 − 3600))/18

y = (30 ± √(-2700))/18

y = (30 ± 30√3 i)/18

y = (5 ± 5√3 i)/3

Soluciones complejas conjugadas:

Y₄ = (5 + 5√3 i)/3

Y₅ = (5 − 5√3 i)/3

Cantidad de soluciones:

* Reales = 3
* Complejas = 2

La mayoría son reales.

Según la condición:

∴ Y = F

---

## Paso N° 2: Verificación

### Tabla proposicional

X → Y

| X | Y | X→Y |
| - | - | --- |
| V | V | V   |
| V | F | F   |
| F | V | V   |
| F | F | V   |

### Matemáticamente

Se obtienen:

* 3 valores verdaderos.
* 1 valor falso.

### Proposicionalmente

X = V

Y = F

X → Y = F

---

### Verificación solicitada

Se pidió verificar si generan una validación verdadera.

Como:

X → Y = F

No generan una validación verdadera.

### Por lo tanto

La validación proposicional es falsa.

