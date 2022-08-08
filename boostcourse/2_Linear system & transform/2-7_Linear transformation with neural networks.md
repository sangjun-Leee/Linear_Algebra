선형변환은 기존의 좌표공간을 새로운 좌표공간으로 변환해준다.

ex) 다음과 같은 선형변환은 (1, 0)을 (2, 3)으로, (0, 1)을 (1, 4)로 보낸다.

$$T(\begin{bmatrix}
1 \\
0
\end{bmatrix}) = \begin{bmatrix}
2 \\
3
\end{bmatrix}, \qquad T(\begin{bmatrix}
0 \\
1
\end{bmatrix}) = \begin{bmatrix}
1 \\
4
\end{bmatrix}$$

표준 기저벡터로 표현되는 2차원의 공간을 (2, 3), (1, 4)를 기준 기저벡터로 가지는 2차원의 공간으로 변환시킨다.

![img]()

</br>

$$\begin{bmatrix}
0.2 & -0.5 & 0.1 & 2 \\
1.5 & 1.3 & 2.1 & 1 \\
-0.2 & 0.3 & 0.7 & -1.3
\end{bmatrix} \begin{bmatrix}
x_{1} \\
x_{2} \\
x_{3} \\
x_{4}
\end{bmatrix} + \begin{bmatrix}
1.1 \\
3.2 \\
-1.2
\end{bmatrix} = \begin{bmatrix}
y_{1} \\
y_{2} \\
y_{3}
\end{bmatrix}$$

$$\Downarrow$$

$$\begin{bmatrix}
0.2 \\
1.5 \\
-0.2
\end{bmatrix} x_{1} + \begin{bmatrix}
-0.5 \\
1.3 \\
2.3
\end{bmatrix} x_{2} + ... + \begin{bmatrix}
1.1 \\
3.2 \\
-1.2
\end{bmatrix} \cdot 1 = \begin{bmatrix}
y_{1} \\
y_{2} \\
y_{3}
\end{bmatrix}$$

</br>

> input의 각 feature가 결과 노드에 어느정도의 영향을 끼치는지를 의미.   
> weight matrix의 각 열벡터가 feature의 가중치를 받아 결과 예측에 쓰인다.   
> 예를 들면, 키가 $x_{1}$인 사람은 키라는 feature가 당뇨에는 $0.2x_{1}$만큼의 영향을 끼치고, 몸무게가 $x_{2}$일 때, 몸무게는 당뇨에 $-0.5x_{2}$만큼 영향을 키친다.

$$\Downarrow$$

$$\begin{bmatrix}
0.2 & -0.5 & 0.1 & 2 & 1.1\\
1.5 & 1.3 & 2.1 & 1 & 3.2\\
-0.2 & 0.3 & 0.7 & -1.3 & -1.2
\end{bmatrix} \begin{bmatrix}
x_{1} \\
x_{2} \\
x_{3} \\
x_{4} \\
1
\end{bmatrix} = \begin{bmatrix}
y_{1} \\
y_{2} \\
y_{3}
\end{bmatrix}$$
