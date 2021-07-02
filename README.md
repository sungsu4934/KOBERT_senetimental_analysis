# KOBERT_senetimental_analysis
  - 출처:  https://github.com/kimwoonggon/publicservant_AI/blob/master/2_(Hugging%2B%ED%95%9C%EA%B8%80BERT)%EB%84%A4%EC%9D%B4%EB%B2%84%20%EA%B0%90%EC%84%B1%EB%B6%84%EC%84%9D%2090%25%20%EB%8B%AC%EC%84%B1%ED%95%98%EA%B8%B0.ipynb

### KoBERT를 활용하여 이진분류 구현
 1. 목적: 한국어 뉴스 데이터를 통해 사고유무 관련 기사 판별
 1. sample_train.xlsx, sample_test.xlsx : 사고유무에 대해 간단히 라벨링 된 뉴스데이터 (사고O: 0, 사고X: 1)
 2. KoBERT(tensorflow)_colab.ipynb: colab 버전으로 구성하였으며 KoBERT에 DNN을 쌓아 감성분석 모델 훈련부터 테스트까지 구현

### 총평
 1. 매우 적은 소수의 데이터와 불균형한 데이터 임에도 훌륭한 성능
 2. keras에 익숙한 사람에게 큰 어려움 없이 활용 가능하며 다중분류로 쉽게 전환 가능
