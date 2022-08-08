## Eigenvectors and Eigenvalues

$$A\mathbf{x} = \lambda\mathbf{x} \qquad A\in\mathbb{R}^{n\times n}, \ \mathbf{x} \ne \mathbf{0}$$

위 식을 만족하는 영이 아닌 벡터 $\mathbf{x}$를 $A$의 eigenvector, $\lambda$를 $A$의 eigenvalue 라고 한다.

</br>

**\<선형 변환 관점에서의 고유벡터, 고유값>**

선형 변환 $T( \mathbf{x} )=A\mathbf{x}$를 생각해보자.   
일반적으로 선형변환은 입력벡터의 방향과 크기를 모두 바꿔준다.   
만약 입력벡터가 $A$의 고유벡터라면, 선형변환 $A$는 고유벡터에 대하여 방향은 바꿔주지 않고 그 크기만 고유값만큼 변환해준다.

![img](../img/4_Eigen Decomposition/transformation perspective.png)
