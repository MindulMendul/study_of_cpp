# 코테 풀 때 주의할 점 모음
### 코테풀면서 실수해서 눈물 봤던 사소한 실수들을 정리해둠.

1. 반드시 입력모양을 헷갈리지 말기
- 띄어쓰기가 있는지, 줄바꿈이 있는지 반드시 확인하기
- 입력값이 0부터 시작하는지, 1부터 시작하는지 확인하기

---

2. 반드시 출력모양을 헷갈리지 말기
- 띄어쓰기가 있는지, 줄바꿈이 있는지 반드시 확인하기
- 출력값이 0부터 시작하는지, 1부터 시작하는지 확인하기

---

3. 반드시 문제 조건을 확인하기
- N, M 값이 얼마나 커질지 항상 고려하기
(1초에 1억 번 계산을 기준으로 최적 알고리즘을 파악해보기)
- 최악을 가정할 때 알고리듬을 적용해도 풀 수 있다는 걸 확인하고 나서 코딩해도 늦지 않음. 골드 이하 문제에서는 반드시 그 조건을 만족하는 알고리듬을 내가 찾을 수 있다고 생각해야 함! (그리고 실제로 90%는 맞는 말이다.)

---

4. 기타 기억해야할 것
- 모든 배열을 받고 나서, 배열의 크기를 바꿀 거면 N, M 값도 변동이 있다는 점을 자각하기.
- 출력값을 보고, 중요한 정보와 중요하지 않은 정보를 확실히 구분해서 자료구조 만들어보기. //2295. (x,y,z,d) 쌍을 찾을 때, 중요한 정보는 d기 때문에, x+y 값을 임의로 수정해도 본질은 바뀌지 않음.