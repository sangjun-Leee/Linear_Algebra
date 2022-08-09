## Linear Independence

$$x_{1}v_{1} + x_{2}v_{2} + ... + x_{p}v_{p} = 0$$

</br>

- 위의 선형방정식의 해가 **오직 하나만 존재** ( $\mathbf{x}=\vec{0}$, trivial solution) 하면 $\mathbf{v}$ **벡터들은 선형 독립**.   
trivial solutoin이외의 해(non-trivial solution)가 존재하면 $\mathbf{v}$ **벡터들은 선형 의존**.
- **선형 의존인 벡터는 Span을 확장시키지 못한다.** &nbsp; $\to$ &nbsp; Span{ $v_{1}, v_{2}$ } = Span{ $v_{1}, v_{2}, v_{3}$ }
- 만약 non-trivial solution이 존재한다면, $x_{1}v_{1} + x_{2}v_{2} + ... + x_{p-1}v_{p-1} = -x_{p}v_{p}$의 꼴로 변형했을때,( $x_{p} \ne 0$ )   
$v_{1}, v_{2}, ..., v_{p-1}$의 Span 안에 $v_{p}$가 포함된다.( $v_{p}$ 를 나머지 벡터들의 선형결합으로 표현할 수 있다) &nbsp; $\to$ &nbsp; 따라서 선형의존이 된다.

</br>

## Uniqueness of solution for Ax=b

선형독립(linear independent)인 경우 Ax=b의 해가 있을 때, 그 해는 유일하다.   
만약 해가 유일하지 않다면 b를 만들 수 있는 A의 column 벡터들의 선형결합이 많다는 뜻이고 b벡터를 0벡터로 옮겼을 때도 해가 여러개(non-trivial solution)있다는 뜻이므로 모순이된다.

만약 미지수의 수(벡터의 수)보다 방정식의 수(벡터의 차원)가 작으면 선형 의존이 되어버리기 때문에 방정식의 해가 무수히 많다.(벡터의 span이 차원 전체를 다 덮게 되므로)
