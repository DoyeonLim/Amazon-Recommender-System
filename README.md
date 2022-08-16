# 2022_Summer_RecSys_T11_Ah_Chu
CUAI 5th Summer Conference Project Repository   
Check out Paper at [Link](https://github.com/woog2ee/KDrama-Chatbots/blob/main/CUAI%20%EB%8F%99%EA%B3%84%20%EC%BB%A8%ED%8D%BC%EB%9F%B0%EC%8A%A4%20Short%20Paper%20NLP%ED%8C%80.pdf)   
Check out Presentation at [Link](https://github.com/woog2ee/KDrama-Chatbots/blob/main/CUAI%20%EB%8F%99%EA%B3%84%20%EC%BB%A8%ED%8D%BC%EB%9F%B0%EC%8A%A4%20Presentation%20NLP%ED%8C%80.pdf)   

## 👪 Teammates
- **Jungjoon Kim** : School of Applied Statistics, Chung-Ang University
- **Yejin Kwon** : School of Applied Statistics, Chung-Ang University
- **Gyeongbin Park** : School of Computer Science & Engineering, Chung-Ang University
- **Doyeon Lim** : School of Computer Science & Engineering, Chung-Ang University

<br>

## Abstract
Amazon Review Dataset을 이용하여 추천시스템 모델을 구현한다. 그 과정에서 자연어처리 기술을 이용하여 Meta Data의 상품 description 항목을 임베딩하여 성능을 높였다. 또한 최신 모델인 BiVAE를 이용해 성능을 높일 수 있었다. 

<br>

## Models(Paper Link)
- [BiVAE(Bilateral Variational Autoencoder)](https://dl.acm.org/doi/pdf/10.1145/3437963.3441759)
- [NCF(Neural Collaborative Filtering)](https://liqiangnie.github.io/paper/p173-he.pdf)
- [LightFM](http://ceur-ws.org/Vol-1448/paper4.pdf)

<br>

## Evaluation
|**MODEL|NCF(100 epoch)|BIVAE(50 epoch)|BIVAE(100 epoch)|lightfm|lightfm(meta)|matrix factorization|matrix factorization(category)**|
|---|---|---|---|
|**MAP**|0.011440|0.021827|0.032151|0.036288|0.000179|0.005266|0.016408|0.015506|0.016474|
|**NDCG**|0.011440|0.050682|0.075207|0.085151|0.000793|0.015583|0.031498|0.031121|0.032077|
|**PRECISION@K**|0.009011|0.032808|0.049084|0.057221|0.000772|0.013203|0.021136|0.021282|0.020952|
|**RECALL@K**|0.011217|0.032780|0.048843|0.058966|0.000858|0.017592|0.043550|0.043070|0.042821


