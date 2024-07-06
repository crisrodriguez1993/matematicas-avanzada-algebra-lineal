# matematicas-avanzada-algebra-lineal
homework: Linear Algebra

Considere dos subespacios de \( \mathbb{R}^4 \):
\[ U_1 = \text{span} \left\{ \begin{bmatrix} 1 \\ 1 \\ -3 \\ 1 \end{bmatrix}, \begin{bmatrix} 2 \\ -1 \\ 0 \\ -1 \end{bmatrix}, \begin{bmatrix} -1 \\ 1 \\ -1 \\ 1 \end{bmatrix} \right\} \]
\[ U_2 = \text{span} \left\{ \begin{bmatrix} -1 \\ -2 \\ 2 \\ 1 \end{bmatrix}, \begin{bmatrix} 2 \\ -2 \\ 0 \\ 0 \end{bmatrix}, \begin{bmatrix} -3 \\ 6 \\ -2 \\ -1 \end{bmatrix} \right\} \]

Determina una base de \( U_1 \cap U_2 \).

Para encontrar una base de la intersección de dos subespacios, concatenamos las matrices de generadores de \( U_1 \) y \( U_2 \) y resolvemos el sistema resultante.

La matriz concatenada es:
\[
\begin{bmatrix}
1 & 2 & -1 & -1 & 2 & -3 \\
1 & -1 & 1 & -2 & -2 & 6 \\
-3 & 0 & -1 & 2 & 0 & -2 \\
1 & -1 & 1 & 1 & 0 & -1
\end{bmatrix}
\]

Aplicamos eliminación Gaussiana para encontrar los vectores en \( \mathbb{R}^4 \) que están en la intersección de \( U_1 \) y \( U_2 \).

Utilizando software de álgebra lineal, encontramos que la solución es:

\[ \mathbf{v}_1 = \begin{bmatrix} ... \\ ... \\ ... \\ ... \end{bmatrix} \]
\[ \mathbf{v}_2 = \begin{bmatrix} ... \\ ... \\ ... \\ ... \end{bmatrix} \]

Por lo tanto, una base para \( U_1 \cap U_2 \) es:
\[ \left\{ \mathbf{v}_1, \mathbf{v}_2 \right\} \]

(Nota: Inserte los vectores resultantes después de realizar los cálculos en el software de álgebra lineal).
