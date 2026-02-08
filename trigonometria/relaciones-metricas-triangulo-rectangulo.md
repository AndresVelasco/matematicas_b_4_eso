# Relaciones Métricas en el Triángulo Rectángulo
## 4º ESO — Geometría

---

## 1. Introducción

En este tema estudiamos la estructura interna del **triángulo rectángulo**.

Un triángulo rectángulo tiene:
- Un ángulo de 90°
- Dos catetos ($c_1$ y $c_2$)
- Una hipotenusa ($h$)

Si trazamos la **altura desde el ángulo recto hasta la hipotenusa**:
- La hipotenusa se divide en dos segmentos: $p$ y $q$
- Aparece la altura $a$
- Se forman dos triángulos rectángulos más pequeños (semejantes al original)
- Surgen las llamadas **relaciones métricas**

---

## 2. Resumen de fórmulas

### Pitágoras
$$
h^2 = c_1^2 + c_2^2
$$

### Teorema del cateto (para cada cateto)
$$
c_1^2 = h \cdot p
$$
$$
c_2^2 = h \cdot q
$$

### Teorema de la altura
$$
a^2 = p \cdot q
$$

### Relación de segmentos en la hipotenusa
$$
h = p + q
$$

---

## 3. Esquema visual (bien etiquetado)

### 3.1 Triángulo rectángulo (sin dibujar la altura)

    c2
    |
    |
    |\
    | \   h
    |  \
    |   \
    |____\
       c1

- Catetos: $c_1$ (base) y $c_2$ (vertical)
- Hipotenusa: $h$ (lado inclinado)

> Nota: aquí **no es que la altura no exista**; simplemente **no la estamos dibujando**.

---

### 3.2 Triángulo rectángulo (dibujando la altura a la hipotenusa)

La altura $a$ parte del ángulo recto y cae perpendicular a la hipotenusa, dividiéndola en $p$ y $q$.

          (vértice)
             *
            /|
           / |
          /  | c2
         /   |
        /    |
       /  |  |
      /   |a |
     /____|__|
        p   q
        \_____\
            h

- La hipotenusa queda dividida: $h = p + q$
- Altura: $a$
- Proyecciones: $p$ y $q$

---

## 4. Explicación detallada (algebra + sentido)

### 4.1 Teorema de Pitágoras

En todo triángulo rectángulo:

$$
h^2 = c_1^2 + c_2^2
$$

Ejemplo:
Si $c_1 = 6$ y $c_2 = 8$:

$$
h = \sqrt{6^2 + 8^2} = \sqrt{36 + 64} = \sqrt{100} = 10
$$

---

### 4.2 Teorema del cateto

Cada cateto al cuadrado es igual a la hipotenusa por su proyección.

$$
c_1^2 = h \cdot p
$$

$$
c_2^2 = h \cdot q
$$

Ejemplo:
Si $h = 10$ y $p = 6$:

$$
c_1 = \sqrt{10 \cdot 6} = \sqrt{60}
$$

---

### 4.3 Teorema de la altura

La altura al cuadrado es el producto de las proyecciones.

$$
a^2 = p \cdot q
$$

Ejemplo:
Si $p = 4$ y $q = 9$:

$$
a = \sqrt{4 \cdot 9} = \sqrt{36} = 6
$$

---

## 5. Conexión entre los teoremas (por qué encajan)

Sabemos que:

$$
h = p + q
$$

Por el teorema del cateto:

$$
c_1^2 = h \cdot p
$$
$$
c_2^2 = h \cdot q
$$

Sumamos:

$$
c_1^2 + c_2^2 = h\cdot p + h\cdot q = h(p + q)
$$

Como $p + q = h$:

$$
c_1^2 + c_2^2 = h^2
$$

Y recuperamos Pitágoras.

---

## 6. Resumen final (de bolsillo)

- Pitágoras: $h^2 = c_1^2 + c_2^2$
- Cateto: $c_1^2 = hp$ y $c_2^2 = hq$
- Altura: $a^2 = pq$
- Segmentos: $h = p + q$
