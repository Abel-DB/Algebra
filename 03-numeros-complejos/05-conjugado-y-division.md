# Conjugado y División de Números Complejos

## Conjugado de un Número Complejo

El conjugado de un número complejo se obtiene cambiando el signo de la parte imaginaria.

Si:

$$
z = a + bi
$$

su conjugado se define como:

$$
\overline{z} = a - bi
$$

---

## Ejemplos

### Ejemplo 1

Dado:

$$
z = 3 + 4i
$$

su conjugado es:

$$
\overline{z} = 3 - 4i
$$

---

### Ejemplo 2

Dado:

$$
z = -2 - 5i
$$

su conjugado es:

$$
\overline{z} = -2 + 5i
$$

---

### Ejemplo 3

Dado:

$$
z = 7
$$

como la parte imaginaria es cero:

$$
\overline{z}=7
$$

---

## Interpretación Geométrica

En el plano complejo, un número complejo y su conjugado son simétricos respecto al eje real.

Por ejemplo:

$$
z = 4 + 3i
$$

y

$$
\overline{z}=4-3i
$$

tienen la misma parte real, pero partes imaginarias opuestas.

```text
            ↑
         4i |
         3i |      ● z
         2i |
         1i |
------------+----------------→
         -1i|
         -2i|
         -3i|      ● z̄
         -4i|
```

---

## Propiedades del Conjugado

Sea:

$$
z=a+bi
$$

Entonces se cumplen las siguientes propiedades.

### Doble conjugado

$$
\overline{\overline{z}}=z
$$

---

### Conjugado de una suma

$$
\overline{z_1+z_2} = \overline{z_1} + \overline{z_2}
$$

---

### Conjugado de una resta

$$
\overline{z_1-z_2} = \overline{z_1} - \overline{z_2}
$$

---

### Conjugado de un producto

$$
\overline{z_1z_2} = \overline{z_1} \cdot \overline{z_2}
$$

---

## Producto de un Complejo por su Conjugado

Una propiedad muy importante es:

$$
z\overline{z} = (a+bi)(a-bi)
$$

Desarrollando:

$$
a^2-abi+abi-b^2i^2
$$

Los términos imaginarios se cancelan:

$$
a^2-b^2(-1)
$$

$$
a^2+b^2
$$

Por lo tanto:

$$
z\overline{z}=a^2+b^2
$$

El resultado siempre es un número real.

---

### Ejemplo

$$
(3+4i)(3-4i)
$$

$$
=9-12i+12i-16i^2
$$

$$
=9+16
$$

$$
=25
$$

---

# División de Números Complejos

## Idea Fundamental

No es conveniente dejar números imaginarios en el denominador.

Para eliminar la parte imaginaria del denominador se multiplica tanto el numerador como el denominador por el conjugado del denominador.

---

## Fórmula General

Sea:

$$
\frac{a+bi}{c+di}
$$

Multiplicamos por:

$$
\frac{c-di}{c-di}
$$

obteniendo:

$$
\frac{(a+bi)(c-di)}
{(c+di)(c-di)}
$$

Como:

$$
(c+di)(c-di) = c^2+d^2
$$

el denominador se vuelve un número real.

Finalmente:

$$
\frac{a+bi}{c+di} = \frac{(ac+bd)+(bc-ad)i} {c^2+d^2}
$$

---

## Ejemplo 1

Calcular:

$$
\frac{3+2i}{1+i}
$$

Multiplicamos por el conjugado del denominador:

$$
\frac{3+2i}{1+i}
\cdot
\frac{1-i}{1-i}
$$

Numerador:

$$
(3+2i)(1-i)
$$

$$
=3-3i+2i-2i^2
$$

$$
=3-i+2
$$

$$
=5-i
$$

Denominador:

$$
(1+i)(1-i)
$$

$$
=1-i^2
$$

$$
=2
$$

Resultado:

$$
\frac{5-i}{2}
$$

o equivalentemente:

$$
\frac{5}{2}-\frac{1}{2}i
$$

---

## Ejemplo 2

Calcular:

$$
\frac{4-i}{2+3i}
$$

Multiplicamos por el conjugado:

$$
\frac{4-i}{2+3i}
\cdot
\frac{2-3i}{2-3i}
$$

Numerador:

$$
(4-i)(2-3i)
$$

$$
=8-12i-2i+3i^2
$$

$$
=8-14i-3
$$

$$
=5-14i
$$

Denominador:

$$
(2+3i)(2-3i)
$$

$$
=4+9
$$

$$
=13
$$

Resultado:

$$
\frac{5-14i}{13}
$$

---

## Procedimiento para Dividir Complejos

1. Identificar el denominador.
2. Hallar su conjugado.
3. Multiplicar numerador y denominador por dicho conjugado.
4. Desarrollar las multiplicaciones.
5. Reemplazar:

$$
i^2=-1
$$

6. Simplificar el resultado.

---

## Resumen

- El conjugado de:

$$
a+bi
$$

es:

$$
a-bi
$$

- Un complejo multiplicado por su conjugado produce un número real:

$$
(a+bi)(a-bi)=a^2+b^2
$$

- Para dividir números complejos se utiliza el conjugado del denominador.
- El objetivo es transformar el denominador en un número real.
- La división de complejos sigue las mismas reglas algebraicas básicas que los números reales.
