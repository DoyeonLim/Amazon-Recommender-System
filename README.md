# 2022_Summer_RecSys_T11_Ah_Chu
CUAI 5th Summer Conference Project Repository   
Check out Paper at    
Check out Presentation at   

<br>

## 👪 Teammates
- **Jungjoon Kim** : School of Applied Statistics, Chung-Ang University
- **Yejin Kwon** : School of Applied Statistics, Chung-Ang University
- **Gyeongbin Park** : School of Computer Science & Engineering, Chung-Ang University
- **Doyeon Lim** : School of Computer Science & Engineering, Chung-Ang University

<br>

## 📄Abstract
Amazon Review Dataset을 이용하여 추천시스템 모델을 구현한다. 그 과정에서 자연어처리 기술을 이용하여 Meta Data의 상품 description 항목을 임베딩하여 성능을 높였다. 또한 최신 모델인 BiVAE를 이용해 성능을 높일 수 있었다. 

<br>

## 🔧Models(Paper Link)
- [BiVAE(Bilateral Variational Autoencoder)](https://dl.acm.org/doi/pdf/10.1145/3437963.3441759)
- [NCF(Neural Collaborative Filtering)](https://liqiangnie.github.io/paper/p173-he.pdf)
- [LightFM](http://ceur-ws.org/Vol-1448/paper4.pdf)

<br>

## 🔍Evaluation
|**MODEL**|**NCF**|**lightfm**|**lightfm(meta)**|**matrix factorization**|**matrix factorization(meta)**|**BIVAE**|
|---|---|---|---|---|---|---|
|**MAP**|0.004876|0.000179|0.005266|0.016408|0.016474|0.036288|
|**NDCG**|0.011440|0.000793|0.015583|0.031498|0.032077|0.085151|
|**PRECISION@K**|0.009011|0.000772|0.013203|0.021136|0.020952|0.057221|
|**RECALL@K**|0.011217|0.000858|0.017592|0.043550|0.042821|0.058966|


