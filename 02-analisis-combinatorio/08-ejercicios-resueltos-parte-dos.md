# Ejercicio 1

**En la mesa presidencial está formada por ocho personas. ¿De cuántas formas distintas se pueden sentar, si el presidente y el secretario deben estar juntos?**

Como el presidente y el secretario deben permanecer juntos, se consideran como un solo bloque.

$$
P_{(n-1)} \cdot P_2
$$

$$
= P_{(8-1)} \cdot P_2
$$

$$
= P_7 \cdot P_2
$$

$$
= 7! \cdot 2!
$$

$$
= (7 \cdot 6 \cdot 5 \cdot 4 \cdot 3 \cdot 2 \cdot 1)(2 \cdot 1)
$$

$$
= 5040 \cdot 2
$$

$$
= 10080
$$

### Respuesta

**10080 formas distintas.**

---

# Ejercicio 2

**Se ordenan en una fila 5 bolas rojas, 2 bolas blancas y 3 bolas azules. Si las bolas de igual color no se distinguen entre sí, ¿de cuántas formas posibles pueden ordenarse?**

### Fórmula

Las permutaciones con repetición están dadas por:

$$
PR = \frac{n!}{n_1! \cdot n_2! \cdot n_3!}
$$

### Desarrollo

$$
PR = \frac{10!}{5! \cdot 2! \cdot 3!}
$$

$$
= \frac{10 \cdot 9 \cdot 8 \cdot 7 \cdot 6 \cdot 5!}
{5! \cdot (2 \cdot 1) \cdot (3 \cdot 2 \cdot 1)}
$$

$$
= \frac{10 \cdot 9 \cdot 8 \cdot 7 \cdot 6}
{2 \cdot 6}
$$

$$
= 5 \cdot 9 \cdot 8 \cdot 7
$$

$$
= 2520
$$

### Respuesta

**2520**

---

# Ejercicio 3

**Con el sistema Morse (punto y raya), ¿cuántas señales distintas se pueden enviar usando como máximo cuatro pulsaciones?**

### Datos

- \(m = 2\) símbolos (punto y raya)
- \(n =\) cantidad de pulsaciones

### Fórmula

$$
m^n
$$

### Desarrollo

Para una pulsación:

$$
2^1 = 2
$$

Para dos pulsaciones:

$$
2^2 = 4
$$

Para tres pulsaciones:

$$
2^3 = 8
$$

Para cuatro pulsaciones:

$$
2^4 = 16
$$

Como se permiten **hasta cuatro pulsaciones**, sumamos todas las posibilidades:

$$
2^1 + 2^2 + 2^3 + 2^4
$$

$$
= 2 + 4 + 8 + 16
$$

$$
= 6 + 8 + 16
$$

$$
= 14 + 16
$$

$$
= 30
$$

### Respuesta

**30**

---

# Ejercicio 4

**A un concurso literario se han presentado 10 candidatos con sus novelas. El cuadro de honor lo forman el ganador, el finalista y un accésit. ¿Cuántos cuadros de honor se pueden formar?**

### Fórmula

Las variaciones están dadas por:

$$
V_n^k=\frac{n!}{(n-k)!}
$$

### Desarrollo

$$
V_{10}^{3} = \frac{10!}{(10-3)!}
$$

$$
= \frac{10!}{7!}
$$

$$
= \frac{10\cdot9\cdot8\cdot7!}{7!}
$$

$$
= 10\cdot9\cdot8
$$

$$
= 90\cdot8
$$

$$
= 720
$$

### Respuesta

**720**
