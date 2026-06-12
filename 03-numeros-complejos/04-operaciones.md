# Operaciones con Números Complejos

## Introducción

Los números complejos pueden sumarse, restarse, multiplicarse y dividirse siguiendo reglas algebraicas similares a las utilizadas con los números reales.

La única diferencia importante es la presencia de la unidad imaginaria:

$$
i^2 = -1
$$

Esta propiedad permite simplificar los resultados obtenidos durante las operaciones.

---

## Suma de Números Complejos

Para sumar dos números complejos se agrupan las partes reales y las partes imaginarias.

Sean:

$$
z_1 = a + bi
$$

$$
z_2 = c + di
$$

Entonces:

$$
z_1 + z_2 = (a+c) + (b+d)i
$$

### Ejemplo 1

$$
(3+2i)+(4+5i)
$$

Agrupando términos semejantes:

$$
=(3+4)+(2+5)i
$$

$$
=7+7i
$$

### Ejemplo 2

$$
(5-3i)+(2+7i)
$$

$$
=(5+2)+(-3+7)i
$$

$$
=7+4i
$$

---

## Resta de Números Complejos

La resta se realiza restando las partes reales y las partes imaginarias por separado.

$$
z_1-z_2=(a-c)+(b-d)i
$$

### Ejemplo 1

$$
(8+6i)-(3+2i)
$$

$$
=(8-3)+(6-2)i
$$

$$
=5+4i
$$

### Ejemplo 2

$$
(4-5i)-(2+3i)
$$

$$
=(4-2)+(-5-3)i
$$

$$
=2-8i
$$

---

## Multiplicación de Números Complejos

Para multiplicar dos números complejos se aplica la propiedad distributiva.

Sean:

$$
z_1=a+bi
$$

$$
z_2=c+di
$$

Entonces:

$$
(a+bi)(c+di)
$$

Desarrollando:

$$
ac+adi+bci+bdi^2
$$

Como:

$$
i^2=-1
$$

obtenemos:

$$
(ac-bd)+(ad+bc)i
$$

### Fórmula General

$$
(a+bi)(c+di)
=
(ac-bd)+(ad+bc)i
$$

---

### Ejemplo 1

$$
(2+3i)(1+4i)
$$

Aplicando la distributiva:

$$
=2+8i+3i+12i^2
$$

Sustituyendo:

$$
i^2=-1
$$

$$
=2+11i-12
$$

$$
=-10+11i
$$

---

### Ejemplo 2

$$
(5-i)(2+3i)
$$

$$
=10+15i-2i-3i^2
$$

$$
=10+13i+3
$$

$$
=13+13i
$$

---

## Potencias de la Unidad Imaginaria

Las potencias de $i$ siguen un patrón periódico.

### Primeras Potencias

$$
i^0 = 1
$$

$$
i^1 = i
$$

$$
i^2 = -1
$$

$$
i^3 = -i
$$

$$
i^4 = 1
$$

A partir de aquí el ciclo se repite.

| Potencia | Resultado |
|-----------|-----------|
| $i^0$ | $1$ |
| $i^1$ | $i$ |
| $i^2$ | $-1$ |
| $i^3$ | $-i$ |
| $i^4$ | $1$ |

---

## Método Rápido para Potencias de i

Para calcular una potencia elevada de $i$, se divide el exponente entre 4 y se utiliza el residuo.

### Ejemplo

Calcular:

$$
i^{27}
$$

Dividiendo:

$$
27 \div 4 = 6
$$

Residuo:

$$
3
$$

Por tanto:

$$
i^{27}=i^3
$$

$$
=-i
$$

---

### Ejemplo

Calcular:

$$
i^{42}
$$

Dividiendo:

$$
42 \div 4 = 10
$$

Residuo:

$$
2
$$

Entonces:

$$
i^{42}=i^2
$$

$$
=-1
$$

---

## Propiedades Básicas

Sean:

$$
z_1=a+bi
$$

$$
z_2=c+di
$$

Se cumplen las siguientes propiedades:

### Conmutativa de la suma

$$
z_1+z_2=z_2+z_1
$$

### Conmutativa de la multiplicación

$$
z_1z_2=z_2z_1
$$

### Asociativa de la suma

$$
(z_1+z_2)+z_3
=
z_1+(z_2+z_3)
$$

### Asociativa de la multiplicación

$$
(z_1z_2)z_3
=
z_1(z_2z_3)
$$

### Distributiva

$$
z_1(z_2+z_3)
=
z_1z_2+z_1z_3
$$

---

## Resumen

- La suma y la resta se realizan agrupando partes reales e imaginarias.
- La multiplicación utiliza la propiedad distributiva.
- Siempre debe reemplazarse:

$$
i^2=-1
$$

- Las potencias de $i$ siguen un ciclo de cuatro términos:

$$
1,\ i,\ -1,\ -i
$$

- Los números complejos cumplen las propiedades algebraicas básicas de suma y multiplicación.
