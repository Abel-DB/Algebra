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
= 5040 \cdot 2 = 10080
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
PR = \frac{10!}{5! \cdot 2! \cdot 3!} = \frac{10 \cdot 9 \cdot 8 \cdot 7 \cdot 6 \cdot \cancel{5!}}
{\cancel{5!} \cdot (2 \cdot 1) \cdot (3 \cdot 2 \cdot 1)} = \frac{10 \cdot 9 \cdot 8 \cdot 7 \cdot 6}
{2 \cdot 6} = 5 \cdot 9 \cdot 8 \cdot 7 = 2520
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
= 2 + 4 + 8 + 16 = 30
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
V_{10}^{3} = \frac{10!}{(10-3)!} = \frac{10!}{7!} = \frac{10\cdot9\cdot8\cdot7!}{7!} = 10\cdot9\cdot8 = 720
$$

### Respuesta

**720**

---

# Ejercicio 5

**La asociación 25 de Mayo está formada por 55 personas, de las cuales 30 son mujeres y 25 varones. ¿De cuántas formas se puede escoger un comité de 5 personas que incluya 3 mujeres y 2 varones?**

### Fórmula

Las combinaciones están dadas por:

$$
C_n^k=\frac{n!}{k!(n-k)!}
$$

### Mujeres

$$
C_{30}^{3} = \frac{30!}{3!(30-3)!} = \frac{30!}{3!\,27!} = \frac{30\cdot29\cdot28\cdot27!}
{(3\cdot2\cdot1)\cdot27!} = 10\cdot29\cdot14 = 4060
$$

### Varones

$$
C_{25}^{2} = \frac{25!}{2!(25-2)!} = \frac{25!}{2!\cdot23!} = \frac{25\cdot24\cdot23!}
{(2\cdot1)\cdot23!} = 25\cdot12 = 300
$$

### Total

$$
4060\cdot300 = 1218000
$$

### Respuesta

**1218000**

---

# Ejercicio 6

**Doce amigos van de viaje. Para ello utilizan tres vehículos. Si deciden ir cuatro en cada vehículo y solo cinco de ellos tienen licencia, ¿de cuántas maneras diferentes podrían realizar el viaje?**

### Fórmulas

Permutaciones:

$$
P(n)=n!
$$

Combinaciones:

$$
C_n^k=\frac{n!}{k!(n-k)!}
$$

### Conductores

Se deben elegir 3 conductores entre los 5 que tienen licencia:

$$
C_5^3
= \frac{5!}{3!(5-3)!} = \frac{5!}{3!\,2!} = \frac{5\cdot4\cdot3!}
{(3!)(2\cdot1)} = 5\cdot2 = 10
$$

### Distribución de los pasajeros

De los 9 amigos restantes, se eligen 3 para acompañar al primer conductor:

$$
C_9^3
= \frac{9!}{3!(9-3)!} = \frac{9!}{3!\,6!} = \frac{9\cdot8\cdot7\cdot6!}
{(3\cdot2\cdot1)\cdot6!} = 3\cdot4\cdot7 = 84
$$

Para el segundo vehículo:

$$
C_6^3
= \frac{6!}{3!(6-3)!} = \frac{6!}{3!\,3!} = \frac{6\cdot5\cdot4\cdot3!}
{(3\cdot2\cdot1)\cdot3!} = 2\cdot5\cdot2 = 20
$$

Para el tercer vehículo:

$$
C_3^3 = 1
$$

### Orden de los vehículos

Los 3 conductores pueden asignarse a los 3 vehículos de:

$$
P_3 = 3! = 3\cdot2\cdot1 = 6
$$

### Total

$$
10\cdot6\cdot84\cdot20\cdot1 = 100800
$$

### Respuesta

**100800**

---

# Ejercicio 7

**A un congreso asisten 50 personas, de las cuales 20 hablan inglés, 16 alemán y 14 español. ¿Cuántos diálogos diferentes pueden establecerse sin intérprete?**

### Fórmula

Las combinaciones están dadas por:

$$
C_n^k=\frac{n!}{k!(n-k)!}
$$

Como un diálogo se establece entre dos personas:

$$
C_n^2=\frac{n!}{2!(n-2)!}
$$

### Inglés

$$
C_{20}^{2} = \frac{20!}{2!(20-2)!} = \frac{20!}{2!\cdot18!} = \frac{20\cdot19\cdot18!}
{(2\cdot1)\cdot18!} = 10\cdot19 = 190
$$

### Alemán

$$
C_{16}^{2} = \frac{16!}{2!(16-2)!} = \frac{16!}{2!\cdot14!} = \frac{16\cdot15\cdot14!}
{(2\cdot1)\cdot14!} = 8\cdot15 = 120
$$

### Español

$$
C_{14}^{2} = \frac{14!}{2!(14-2)!} = \frac{14!}{2!\cdot12!} = \frac{14\cdot13\cdot12!}
{(2\cdot1)\cdot12!} = 7\cdot13 = 91
$$

### Total

$$
190+120+91 = 401
$$

### Respuesta

**401**

---

# Ejercicio 8

**¿Cuántos anagramas se pueden formar con las letras de la palabra "COCACOLA", si las letras LA deben estar juntas en cualquier orden?**

### Datos

En la palabra **COCACOLA** tenemos:

- C = 3
- O = 2
- A = 2
- L = 1

Las letras **L** y **A** deben permanecer juntas, por lo que forman un bloque.

El bloque puede escribirse de dos formas:

$$
(LA) o (AL)
$$

Las permutaciones del bloque son:

$$
P_2 = 2! = 2
$$

### Formación del bloque

Al considerar el bloque como un solo elemento, quedan:

- Bloque
- C = 3
- O = 2
- A = 1

En total:

$$
7 \text{ elementos}
$$

Aplicamos permutaciones con repetición:

$$
PR_7^{3,2,1}
= \frac{7!}{3!\cdot2!\cdot1!}
$$

### Desarrollo

$$
2!\cdot\frac{7!}{3!\cdot2!\cdot1!} = 2!\cdot
\frac{7\cdot6\cdot5\cdot4\cdot3!}
{3!\cdot(2\cdot1)\cdot1} = 2\cdot
\frac{7\cdot6\cdot5\cdot4}
{2} = 2\cdot(7\cdot3\cdot5\cdot4) = 2\cdot420 = 840
$$

### Respuesta

**840**

---

# Ejercicio 9

**De un grupo de tres perros, tres gatos y tres canarios, se desea escoger tres mascotas, donde por lo menos debe haber un gato. ¿De cuántas maneras se pueden elegir las mascotas?**

### Método del complemento

Calculamos:

- Todas las formas posibles de elegir 3 mascotas.
- Menos las formas en que no se elige ningún gato.

$$
N(\text{al menos un gato})
= C_9^3 - C_6^3
$$

### Elegir 3 mascotas entre las 9 disponibles

$$
C_9^3
= \frac{9!}{3!(9-3)!}
$$

$$
= \frac{9!}{3!\,6!}
$$

$$
= \frac{9\cdot8\cdot7\cdot6!}
{(3\cdot2\cdot1)\cdot6!}
$$

$$
= \frac{9\cdot8\cdot7}{6}
$$

$$
= 3\cdot4\cdot7
$$

$$
= 84
$$

### Elegir 3 mascotas sin gatos

Si no se escoge ningún gato, solamente pueden elegirse entre los 3 perros y los 3 canarios.

$$
C_6^3
= \frac{6!}{3!(6-3)!}
$$

$$
= \frac{6!}{3!\,3!}
$$

$$
= \frac{6\cdot5\cdot4\cdot3!}
{(3\cdot2\cdot1)\cdot3!}
$$

$$
= \frac{6\cdot5\cdot4}{6}
$$

$$
= 2\cdot5\cdot2
$$

$$
= 20
$$

### Total

$$
C_9^3 - C_6^3
$$

$$
= 84 - 20
$$

$$
= 64
$$

### Respuesta

**64**
