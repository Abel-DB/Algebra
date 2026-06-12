## Ejercicio a)

Resolver:

$$
x^2-2x+2=0
$$

### Aplicando la fórmula general

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$

Datos:

$$
a=1,\quad b=-2,\quad c=2
$$

Sustituyendo:

$$
x=\frac{-(-2)\pm\sqrt{(-2)^2-4(1)(2)}}{2(1)}
$$

$$
x=\frac{2\pm\sqrt{4-8}}{2}
$$

$$
x=\frac{2\pm\sqrt{-4}}{2}
$$

Sabemos que:

$$
\sqrt{-4}=2i
$$

Entonces:

$$
x=\frac{2\pm2i}{2}
$$

$$
x=1\pm i
$$

### Solución

$$
\boxed{x=1+i,\quad x=1-i}
$$

---

## Ejercicio b)

Resolver:

$$
x^2+3=0
$$

Despejando:

$$
x^2=-3
$$

Aplicando raíz cuadrada:

$$
x=\pm\sqrt{-3}
$$

Separando:

$$
x=\pm\sqrt3\sqrt{-1}
$$

Como:

$$
\sqrt{-1}=i
$$

obtenemos:

$$
x=\pm\sqrt3,i
$$

### Solución

$$
\boxed{x=\pm\sqrt3,i}
$$

---

## Ejercicio c)

Resolver:

$$
x^2-2x+4=0
$$

### Fórmula general

$$
a=1,\quad b=-2,\quad c=4
$$

$$
x=\frac{-(-2)\pm\sqrt{(-2)^2-4(1)(4)}}{2(1)}
$$

$$
x=\frac{2\pm\sqrt{4-16}}{2}
$$

$$
x=\frac{2\pm\sqrt{-12}}{2}
$$

$$
x=\frac{2\pm2\sqrt3,i}{2}
$$

Simplificando:

$$
x=1\pm\sqrt3,i
$$

### Solución

$$
\boxed{x=1+\sqrt3,i,\quad x=1-\sqrt3,i}
$$

---

## Ejercicio d)

Resolver:

$$
x^2+x+1=0
$$

Datos:

$$
a=1,\quad b=1,\quad c=1
$$

Aplicando fórmula general:

$$
x=\frac{-1\pm\sqrt{1-4}}{2}
$$

$$
x=\frac{-1\pm\sqrt{-3}}{2}
$$

$$
x=\frac{-1\pm\sqrt3,i}{2}
$$

Separando términos:

$$
x=-\frac12\pm\frac{\sqrt3}{2}i
$$

### Solución

$$
\boxed{
x=-\frac12+\frac{\sqrt3}{2}i,\quad
x=-\frac12-\frac{\sqrt3}{2}i
}
$$

---

## Ejercicio e)

Resolver:

$$
x^3-6x^2+21x-26=0
$$

### Ruffini

Probamos (x=2):

```text
 2 | 1  -6  21  -26
   |    2  -8   26
   ----------------
     1  -4  13   0
```

Entonces:

$$
(x-2)(x^2-4x+13)=0
$$

Primera raíz:

$$
x=2
$$

Ahora resolvemos:

$$
x^2-4x+13=0
$$

Aplicando fórmula general:

$$
x=\frac{4\pm\sqrt{16-52}}{2}
$$

$$
x=\frac{4\pm\sqrt{-36}}{2}
$$

$$
x=\frac{4\pm6i}{2}
$$

$$
x=2\pm3i
$$

### Solución

$$
\boxed{x=2,\quad x=2+3i,\quad x=2-3i}
$$

---

## Ejercicio f)

Resolver:

$$
x^3+1=0
$$

### Suma de cubos

$$
x^3+1=(x+1)(x^2-x+1)
$$

Entonces:

$$
(x+1)(x^2-x+1)=0
$$

Primera raíz:

$$
x=-1
$$

Ahora resolvemos:

$$
x^2-x+1=0
$$

$$
x=\frac{1\pm\sqrt{1-4}}{2}
$$

$$
x=\frac{1\pm\sqrt{-3}}{2}
$$

$$
x=\frac12\pm\frac{\sqrt3}{2}i
$$

### Solución

$$
\boxed{
x=-1,\quad
x=\frac12+\frac{\sqrt3}{2}i,\quad
x=\frac12-\frac{\sqrt3}{2}i
}
$$

---

## Ejercicio g)

Resolver:

$$
x^4-1=0
$$

### Diferencia de cuadrados

$$
x^4-1=(x^2-1)(x^2+1)
$$

Nuevamente:

$$
x^2-1=(x-1)(x+1)
$$

Entonces:

$$
(x-1)(x+1)(x^2+1)=0
$$

Primeras raíces:

$$
x=1
$$

$$
x=-1
$$

Ahora:

$$
x^2+1=0
$$

$$
x^2=-1
$$

$$
x=\pm i
$$

### Solución

$$
\boxed{x=1,\quad x=-1,\quad x=i,\quad x=-i}
$$

---

## Ejercicio h)

Resolver:

$$
x^4-3x^3-2x^2+10x-12=0
$$

### Primera Ruffini

Probamos (x=3):

```text
 3 | 1  -3  -2  10  -12
   |    3   0  -6   12
   --------------------
     1   0  -2   4   0
```

Obtenemos:

$$
x^3-2x+4
$$

### Segunda Ruffini

Probamos (x=-2):

```text
-2 | 1   0  -2   4
    |   -2   4  -4
    ----------------
      1  -2   2   0
```

Obtenemos:

$$
x^2-2x+2
$$

Entonces:

$$
(x-3)(x+2)(x^2-2x+2)=0
$$

Raíces reales:

$$
x=3
$$

$$
x=-2
$$

Ahora resolvemos:

$$
x^2-2x+2=0
$$

$$
x=\frac{2\pm\sqrt{-4}}{2}
$$

$$
x=\frac{2\pm2i}{2}
$$

$$
x=1\pm i
$$

### Solución

$$
\boxed{x=-2,\quad x=3,\quad x=1+i,\quad x=1-i}
$$
