## Subspace & Basis

Subspace(부분공간) : 선형결합에 대해 닫혀있는 n차원 공간에 대한 부분집합. 임의의 n차원 공간에 대해, n차원 공간에 포함 되면서 n차원 벡터들에 대해 선형결합 연산이 닫혀있는 공간.   
Span{ $\mathbf{v_{1}}, \mathbf{v_{2}}, ..., \mathbf{v_{p}}$ }은 항상 Subspace이다.   

</br>

Basis(기저 벡터) : Subspace가 주어졌을 때 Subspace를 fully span하는 벡터들(subspace를 모두 덮는다 = 표현 가능하다)   
- basis를 만족하는 벡터들은 서로 linearly independent해야 한다.
- basis는 유일하지 않다.
- 각각의 basis는 해당 subspace를 unique하게 표현한다.(같은 점이라도 선형결합으로 표현되는 가중치가 다르다)

</br>

Dimension of subspace : Subspace의 basis의 벡터 개수   
Rank of Matrix : rankA = dim ColA $\to$ column space의 dimension   
                 Matrix의 rank가 작다 $\to$ data의 feature는 많아도 사실상 적은 정보를 담고있다.(A의 열벡터가 선형의존이라 하나의 벡터로도 나머지 값들이 표현되므로. 그리고 이러한 사실이 모델을 망친다.)
                
