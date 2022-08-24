## Diagonalization

정사각 행렬 A를 대각화 하면 대각행렬 D를 만들 수 있다.

```math
D = V^{-1}AV
```

대각화는 항상 가능한 것은 아니다.   
위 식을 만족하는 $V$를 찾을 수 있고 역행렬이 존재할 때 대각화가 가능.(A is diagonalizable)   

```math
D = V^{-1}AV \ \to \ VD = AV
```
```math
V = \[\mathbf{v_{1}} \ \mathbf{v_{2}} \ \cdots \ \mathbf{v_{n}}] \qquad D = \begin{bmatrix}
\lambda_{1} & 0 & \cdots & 0 \\
0 & \lambda_{2} & \ddots & \vdots \\
\vdots & \ddots & \ddots & 0 \\
0 & \cdots & 0 & \lambda_{n}
\end{bmatrix}
```

$v_{i}$는 $V$의 column vector

```math
AV = A \begin{bmatrix}
\mathbf{v_{1}} & \mathbf{v_{2}} & \cdots & \mathbf{v_{n}}
\end{bmatrix} = \begin{bmatrix}
A \mathbf{v_{1}} & A \mathbf{v_{2}} & \cdots & A \mathbf{v_{n}}
\end{bmatrix} \qquad VD = begin{bmatrix}
\mathbf{v_{1}} & \mathbf{v_{2}} & \cdots & \mathbf{v_{n}}
\end{bmatrix} \begin{bmatrix}
\lambda_{1} & 0 & \cdots & 0 \\
0 & \lambda_{2} & \ddots & \vdots \\
\vdots & \ddots & \ddots & 0 \\
0 & \cdots & 0 & \lambda_{n}
\end{bmatrix} = \begin{bmatrix}
\lambda_{1} \mathbf{v_{1}} & \lambda_{2} \mathbf{v_{2}} & \cdots & \lambda_{n} \mathbf{v_{n}}
\end{bmatrix}
