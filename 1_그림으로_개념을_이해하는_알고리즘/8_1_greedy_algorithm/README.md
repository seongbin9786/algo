1. 탐욕 알고리즘의 활용 예시
    1. 수업 시간표 짜기 문제 - 되도록 많은 수업을 듣고 싶을 때
        1. `Step 1: 가장 빨리 끝나는 과목을 고른다.`
        2. `Step 2: 첫 번째 과목이 끝난 후에 시작하는 과목 중 가장 빨리 끝나는 과목을 고른다.`
    2. 배낭 채우기 문제 - 한 가방에 최대한 비싼 것들을 넣고 싶을 때
        1. `Step 1: 가방에 들어갈 수 있는 가장 비싼 물건을 골라 넣는다.`
        2. `Step 2: 남아있는 물건 중 가장 비싼 물건을 골라 넣는다.`
        3. 이번 탐욕 알고리즘은 가장 좋은 답을 내지는 못했지만, 정답에 가까운 결과를 냈다.
    3. 전국에서 라디오 쇼 하기 - 가장 적은 방송국을 순회하고 싶을 때
        1. 대상 주(state)가 있고, 주(state)를 담당하는 방송국이 있다.
        2. `Step 1: 방송 대상 주(state)를 가장 많이 커버하는 방송국을 찾는다.`
        3. `Step 2: 남은 방송 대상 주(state)를 가장 많이 커버하는 방송국을 찾는다.`
        4. 이번 탐욕 알고리즘의 실행 시간은 `O(n^2)`인데, 부분집합으로 풀었으면 `O(2^n)`이었다.

2. 탐욕 알고리즘이란
    1. 멋지게 말하자면, `각 단계에서 국소 최적해를 찾아 전역 최적해를 구한다.` 라고 할 수 있다.
    2. `눈 앞에 가장 좋아 보이는 것을 쌓아나가면 전체적으로도 가장 좋다`는 것
    3. 탐욕 알고리즘은 거의 정답과 비슷한 답을 유추한다. 그래서 `근사 알고리즘`이라고 한다.
    4. 탐욕 알고리즘은 전역 최적화를 목표로 하지만, 실제로는 국소 최적화를 한다.
    
3. 근사 알고리즘
    1. 근사 알고리즘은 정확한 답을 계산하는 데 시간이 너무 많이 걸릴 때 사용한다.
    2. `얼마나 빠른가`, `정답(최적해)에 얼마나 가까운가`로 성능을 판단한다.
    3. 탐욕 알고리즘은 작성하기도 쉽고 빠르기 때문에 좋은 근사 알고리즘이 될 수 있습니다.
