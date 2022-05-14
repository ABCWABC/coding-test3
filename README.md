# coding-test3
완주하지 못한 선수

  * 매개변수
  1. 마라톤에 참여한 선수들의 이름이 담긴 배열 participant
  2. 완주한 선수들의 이름이 담긴 배열 completion

## 구현과정

  1. 배열을 정렬 -> Arrays.sort(배열명)
  2. 인덱스로 값을 꺼내서 비교 -> !값1.equals(값2) 를 if문 조건문으로 사용
  3. 완주못한 선수가 있을 경우 -> return participant[i];
  4. 완주못한 선수가 completion 비교가 끝날때까지 없으면 participant의 마지막 자리에 있는선수가 완주못한 선수 -> return participant[completion.length];


## 보완할점

  1. HashMap을 써서 시간효율을 높인다.
