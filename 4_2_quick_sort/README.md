1. 퀵 정렬에 대해서
    1. 분할 정복 방법론으로 구현한 정렬 알고리즘이다.
    2. 평균적으로 O(n log n)의 시간이 걸린다. (최악은 O(n^2))

2. 퀵 정렬의 구현 방법
    1. `Step 1-1: 가장 왼쪽의 요소를 pivot으로 선택한다. [기본 단계]`
    2. `Step 1-2: 만약 배열의 크기가 2 미만인 경우 중지한다.`
    3. `Step 1-3: 양쪽의 값들이 자신보다 작은/큰 수만 있도록 분류한다.`
    4. `Step 2: 양쪽 값들을 입력으로 재귀호출한다. [재귀 단계]`

3. 두 가지 구현 방법
    1. shallow copy한 새로운 배열에 대해 재귀 호출하는 방법이 있고,
    2. 원래 배열 값과 left, right로 인덱스 값을 넘기는 방법이 있다.