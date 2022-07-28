## 선형 결합(Linear Combination)

p개의 벡터에 각각 실수배를 하고 모두 더한다.

$$c_{1}v_{1} + c_{2}v_{2} + ... + c_{p}v_{p}$$

</br>

From Matrix equation to Vector equation

$$Ax = b \qquad \qquad \Rightarrow \qquad \qquad a_{1}x_{1} + a_{2}x_{2} + a_{3}x_{3} = b$$

$$
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
$$

</br>

## Span

재료벡터들의 가능한 모든 선형결합의 집합.   

![img](boostcourse/img/2. Linear system & transform/Span.png)   
\<Span{v1, v2}>

</br>

기하학적 의미를 생각해 보면, 벡터의 차원 공간에서 재료벡터들의 선형결합으로 표현되는 공간으로 해석할 수 있다.

벡터 방정식에서 Span의 개념을 도입하면,

$$a_{1}x_{1} + a_{2}x_{2} + a_{3}x_{3} = b$$

- 위의 방정식에서 좌변은 $a_{1}, a_{2}, a_{3}$ 의 선형결합이므로, $a_{1}, a_{2}, a_{3}$ 의 Span을 의미한다.   
- 만약 $b$벡터가 $a_{1}, a_{2}, a_{3}$ 의 Span안에 포함된다면 : $a_{1}, a_{2}, a_{3}$ 의 선형결합으로 $b$를 만들 수 있다 $\to$ $x_{1}, x_{2}, x_{3}$(계수)를 찾을 수 있다 $\to$ 방정식의 해가 있다.
- 벡터 방정식에서, 미지수의 개수: 재료 벡터의 개수 / 방정식의 개수: 벡터의 차원    
- 방정식의 수 > 미지수의 수 $\to$ 전체 벡터공간 > 재료 벡터의 수 인 경우.   
- 벡터들이 놓여있는 공간의 차원이 재료벡터의 수보다 많다(크다). 따라서 재료 벡터의 선형결합으로 만들어지는 공간(Span)은 전체 차원에 비해 극히 좁은 영역이고 b벡터가 그 좁은 영역 위에 놓여있기 힘들다. 따라서 많은 경우 해가 없다.

**재료벡터들의 Span위에 b벡터가 놓일 경우(포함이 될 때) 방정식의 해가 존재**

