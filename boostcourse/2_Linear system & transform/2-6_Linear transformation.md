## Linear Transformation

$$T(c\mathbf{u} + d\mathbf{v}) = cT(\mathbf{u}) + dT(\mathbf{v})$$

ex1. $y=3x$ : linear transformation(o)

T(1) = 3, &nbsp; T(2) = 6   
T(4 $\cdot$ 1 + 5 $\cdot$ 2) = T(14) = 42   
4T(1) + 5T(2) = 12 + 30 = 42   

</br>

ex2. $y=3x+2$ : linear transformation(x)

T(1) = 5, &nbsp; T(2) = 8   
T(4 $\cdot$ 1 + 5 $\cdot$ 2) = T(14) = 44   
4T(1) + 5T(2) = 20 + 40 = 60   

</br>

간단한 트릭을 사용해 $y=3x+2$를 선형변환으로 만들 수 있다.

$$T : \begin{bmatrix}
3 & 2
\end{bmatrix} \begin{bmatrix}
x \\
1
\end{bmatrix} \qquad (\mathbb{R}^{2} \to \mathbb{R}^{1})$$

$$T(\begin{bmatrix}
1\\
1
\end{bmatrix}) = \begin{bmatrix}
3 & 2
\end{bmatrix} \begin{bmatrix}
1\\
1
\end{bmatrix} = 5, \quad T(\begin{bmatrix}
2\\
1
\end{bmatrix}) = \begin{bmatrix}
3 & 2
\end{bmatrix} \begin{bmatrix}
2\\
1
\end{bmatrix} = 8$$

$$T(4\begin{bmatrix}
1\\
1
\end{bmatrix} + 5\begin{bmatrix}
2\\
1
\end{bmatrix}) = T(\begin{bmatrix}
4\\
4
\end{bmatrix} + \begin{bmatrix}
10\\
5
\end{bmatrix}) = T(\begin{bmatrix}
14\\
9
\end{bmatrix}) = \begin{bmatrix}
3 & 2
\end{bmatrix} \begin{bmatrix}
14\\
9
\end{bmatrix} = 60$$

$$4T(\begin{bmatrix}
1\\
1
\end{bmatrix}) + 5T(\begin{bmatrix}
2\\
1
\end{bmatrix}) = 4 \times 5 + 5 \times 8 = 60$$
