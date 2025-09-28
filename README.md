A Byte of Python 한국어판: https://bop.wikibook.co.kr/


[과제1]
k-nn, svm, one class svm을 사용하여 아래 조건을 만족하는 프로그램을 작성하라. 
Iris 데이터셋 사용하여 정상 클래스는 setosa (label=0)이고, 테스트 데이터는 전체 클래스 (setosa + versicolor + virginica)이다. 
이상치 탐지는 정상 데이터만 학습 후 다른 클래스는 이상치로 취급한다.

[과제2]
(데이터 준비는)
 2차원 합성 데이터 생성
- make_blobs(n_samples=200, centers=3, cluster_std=1.0) → 구형 클러스터
- make_moons(n_samples=200, noise=0.05) → 비선형 반달 형태

학생들은 두 데이터셋을 번갈아 사용하면서 결과 비교

(제출물은) 
- K-Means와 DBSCAN의 클러스터링 결과 그래프
- WCSS, Silhouette Score 계산 결과
- 각 알고리즘의 장단점 분석 보고서

[텐서플로 기능설명]
https://chatgpt.com/share/68c63f98-0038-8001-86bc-cef1864fc7c7

[과제: MNIST 분류기 제작 및 개선]
본 과목의 실습프로그램이 있는 https://github.com/juhumkwon/-S3I- 에서 
Assignment_MNIST_분류기_제작_및_개선.ipynb을 활용하여 아래 [세부 과제 내용]을 수행하라.\

먼저, 위 코드에 대해 기본 MLP 모델을 구현하고,
Dropout, Batch Normalization, Optimizer, 초기화 방법 등 다양한 설정을 적용하여, 가장 좋은 성능을 내는 방법을 선택하고 분석하시오.

[세부 과제 내용]
- 제공된 템플릿 코드에서 TODO 부분을 완성하시오.
- 각 실험 시나리오에 대해 모델을 학습시키고, 훈련/검증 손실 및 정확도 곡선을 기록하시오.
- Test Accuracy를 비교하여 가장 좋은 성능을 낸 모델을 선택하시오.
- 추가적인 실험(예: learning rate 변경, hidden layer 수 변경)을 진행하여 성능의 변화를 관찰하시오.
