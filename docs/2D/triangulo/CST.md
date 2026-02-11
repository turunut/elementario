# CST – Triángulo de Deformación Constante

## 1. Cinemática

El campo de desplazamientos se aproxima como:

$$
u(x,y) = N_i(x,y) u_i
$$

## 2. Matriz B

$$
\varepsilon = B u
$$

donde

$$
B =
\begin{bmatrix}
\frac{\partial N_i}{\partial x} & 0 \\
0 & \frac{\partial N_i}{\partial y} \\
\frac{\partial N_i}{\partial y} & \frac{\partial N_i}{\partial x}
\end{bmatrix}
$$

## 3. Matriz de rigidez

$$
K = \int_\Omega B^T D B \, d\Omega
$$

---

## 4. Implementación en Python

```python
def stiffness_CST(Xe, D):
    # implementación
    pass
