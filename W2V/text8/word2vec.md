[참조01](https://python-explorer.tistory.com/32)

원-핫 인코딩
- 1과 0으로만 표현된다.
- 이런 형태를 희소벡터/희소행렬 이라 부른다.
- 단어가 같은 단어인지 아닌지를 비교 할 수 있으나 서로 비슷한지는 알 수 없다.
- 새로운 단어를 추가할 때마다 벡터의 차원이 무한으로 증가된다.

--> 이런 단점을 극복하기 위해 다차원 공간에 단어들을 벡터화 하는 방식을 제안했다.
특정 차원을 정해놓고 이 차원에 단어의 정보를 분산하여 표현하는 것 = 분산표현 임베딩 기법
대표적인 예로 구글의 word2vec이 있는데, 딥러닝을 통한 비지도학습 알고리즘을 이용한 예측 모델이다.

분산 표현(Word2Vec)
- float 형태로 표현된다.
- 단어 임베딩 벡터가 여러 차원에 표현된다.
- 유사한 의미를 갖는 단어들이 비슷한 위치에 분포된다.
- 새로운 단어를 추가해도 벡터의 차원은 유지된다.

