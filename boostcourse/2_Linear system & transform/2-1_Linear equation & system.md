## Linear Equation

$$a_{1}x_{1} + a_{2}x_{2} + ... + a_{n}x_{n} = b  \to  a^{T}x=b$$

</br>

## Matrix Equation

$$
\begin{bmatrix}
a_{1}^{T}\\
a_{2}^{T}\\
\vdots\\
a_{n}^{T}\\
\end{bmatrix} x = \begin{bmatrix}
b_{1}\\
b_{2}\\
\vdots\\
b_{n}\\
\end{bmatrix}
$$

만약 행렬 A가 역행렬이 존재한다면, 위 방정식은 유일한 해 $\mathsf{x}=A^{-1}\mathsf{b}$ 를 가진다.   
만약 행렬 A가 역행렬이 존재하지 않는다면, 방정식의 해는 존재하지 않거나 무수히 많은 해를 가진다.

</br>

## Identity & Inverse Matrix

단위행렬과 역행렬은 **정사각 행렬에서만 정의**한다.   
Identity  matrix : diagonal entries are all 1 others 0.   
Inverse matrix : $A^{-1}A = AA^{-1} = I$  &nbsp;  (기본적으로 행렬은 교환법칙이 성립하지 않지만, 역행렬의 경우에는 교환법칙이 성립한다. $\to$ $A^{-1}A = I$ 인데 $AA^{-1} \ne I$ 인 경우는 없다.)

</br>

## 직사각 행렬 A에 대해서


$$Ax = b \quad (A \in R^{m \times n})$$

1. m > n (over-determined system)
   data의 feature 수보다 sample의 수가 많은 경우 = 미지수보다 방정식의 수가 더 많은 경우 -> 방정식의 해가 존재하지 않는다.   
   Least square solution으로 최적의 근사해를 찾아낸다.
2. m < n (under-determined system)
   sample의 수보다 data의 feature 수가 많은 경우 = 만족해야 하는 방정식의 수보다 미지수의 수가 더 많다 -> 방정식의 해가 무수히 많다.   
   Regularization을 통해 가장 안정적인 가중치를 찾아낸다.
