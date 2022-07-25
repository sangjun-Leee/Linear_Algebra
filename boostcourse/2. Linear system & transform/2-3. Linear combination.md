## 선형 결합(Linear Combination)

p개의 벡터에 각각 실수배를 하고 모두 더한다.

```math
c_{1}v_{1} + c_{2}v_{2} + ... + c_{p}v_{p}
```

From Matrix equation to Vector equation

```math
Ax = b \quad \Rightarrow \quad a_{1}x_{1} + a_{2}x_{2} + a_{3}x_{3} = b
```

```math
\begin{bmatrix}
60 & 5.5 & 1 \\
65 & 5.0 & 0 \\
55 & 6.0 & 1
\end{bmatrix}
\begin{bmatrix}
x_{1}\\
x_{2}\\
x_{3}
\end{bmatrix} =
\begin{bmatrix}
66\\
74\\
78
\end{bmatrix}
\quad \Rightarrow \quad
\begin{bmatrix}
60\\
65\\
55
\end{bmatrix}x_{1}
+
\begin{bmatrix}
5.5\\
5.0\\
6.0
\end{bmatrix}x_{2}
+
\begin{bmatrix}
1\\
0\\
1
\end{bmatrix}x_{3} = 
\begin{bmatrix}
66\\
74\\
78
\end{bmatrix}
```

</br>

## Span

재료벡터들의 가능한 모든 선형결합의 집합.   
