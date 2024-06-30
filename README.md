# DM2023-2
데이터마이닝

[과제 1]<br>
 A Priori 알고리즘을 사용하여 연관규칙을 찾아내서 출력하는 프로그램을 작성
- 단, bulit-in 라이브러리만 사용
  - 예를 들어, csv 파일을 읽기 위해서는 csv 모듈을 사용할 수 있지만, efficient-apriori와 같은 3rd party 라이브러리는 사용할 수 없음 (3rd party 라이브러리를 사용하면 점수 X)
  - docs.python.org에서 검색된 라이브러리만 사용

제약조건
- A Priori 알고리즘을 구현함에 있어 basket 내용 전부를 메모리에 저장하지 말 것. 즉, 첨부된 파일을 반드시 여러 번 읽을 것!
- 연관규칙 마이닝 코드는 10초안에 수행되도록 함 (효율적으로 작성)
--------------
<h4>[과제 2]</h4>
수업시간에 배운 Content-based recommendation, Collaborative filtering, Latent factor model 등을 구현하여 test data에 일정 성능 이상(RMSE 1.1이하) 달성

- 주의사항: 추천과 관련된 3rd party 라이브러리는 사용할 수 없음.

  - 예를 들어, automatic differentiation (gradient descent)를 위해 pytorch를 사용할 수 있으나, pytorch/torchrec 같은 라이브리러는 사용할 수 없음.

