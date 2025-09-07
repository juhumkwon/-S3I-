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
