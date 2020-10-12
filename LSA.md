# Latent Semantic Analysis (LSA)

LDA는 SVD를 통해 차원을 축소시킴으로써 단어의 잠재적인 의미를 이용한다.

Document Term Matrix(DTM) = A = U &Sigma; V<sup>t</sup>

U의 column vector: 각 토픽에 대한 문서들의 분포 정보
V의 row vector: 각 토픽에 대한 단어들의 분포 정보

A' = U<sub>t</sub> &Sigma;<sub>t</sub> V<sub>t</sub><sup>T</sup>

상위 t개만 선택해 차원을 축소시킨다.