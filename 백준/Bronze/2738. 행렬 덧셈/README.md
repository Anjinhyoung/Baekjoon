# [Bronze V] 행렬 덧셈 - 2738 

[문제 링크](https://www.acmicpc.net/problem/2738) 

### 성능 요약

메모리: 110948 KB, 시간: 128 ms

### 분류

구현, 수학

### 제출 일자

2024년 2월 18일 17:45:50

### 문제 설명

<p>N*M크기의 두 행렬 A와 B가 주어졌을 때, 두 행렬을 더하는 프로그램을 작성하시오.</p>

### 입력 

 <p>첫째 줄에 행렬의 크기 N 과 M이 주어진다. 둘째 줄부터 N개의 줄에 행렬 A의 원소 M개가 차례대로 주어진다. 이어서 N개의 줄에 행렬 B의 원소 M개가 차례대로 주어진다. N과 M은 100보다 작거나 같고, 행렬의 원소는 절댓값이 100보다 작거나 같은 정수이다.</p>

### 출력 

 <p>첫째 줄부터 N개의 줄에 행렬 A와 B를 더한 행렬을 출력한다. 행렬의 각 원소는 공백으로 구분한다.</p>


### 이 문제를 풀고 난 후
* 맨 처음에 2차원 리스트를 어떻게 입력값으로 채울지 고민을 했다.
* 그래서 생각한 게 extend() + for문을 이용하는 거라고 생각했었는데... 당연히 실패했다.
* 하지만 append() + for()문을 이용하니깐 성공했다.
* 이 문제에서 extend()랑 append()에 차이점을 제대로 알 수 있었다.
  * list.append(x)는 리스트 끝에 x 1개를 그대로 넣습니다.
  * list.extend(iterable)는 리스트 끝에 가장 바깥쪽 iterable의 모든 항목을 넣습니다.
