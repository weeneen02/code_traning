통계 계산
===

현장에서 통계는 중요하다. 응답시간이나 렌더링 시간을 측정할 때 데이터를 수집하면
잘못된 값을 쉽게 찾는데 도움이 된다. 예를 들어, 표준편자는 어떤 값이 기준치 내에
있는지 밖에 있는지를 구별하는 데 도움이 된다.
  웹사이트의 응답시간을 밀리초로 받는 프로그램을 작성하라. 사용자가 'done'이라고
입력할 때까지 응답시간을 받는다.
  그 다음 평균 응답시간, 최소 응답시간, 최대 응답시간, 표준편차를 출력하자.

  평균 값을 구하는 방법은 아래와 같다.

1. 모든 값의 합계를 구한다.
2. 합계를 값의 개수로 나눈다.

  표준 편차를 구하는 방법은 다음과 같다.

1. 각각의 값과 평균의 차를 구하고 이를 제곱한다.
2. 제곱한 값들의 평균을 구한다.
3. 이 평균에 루트를 씌운다.

출력 예
Enter a number: 100
Enter a number: 200
Enter a number: 1000
Enter a number: 300
Enter a number: done
Numbers: 100, 200, 1000, 300
The average is 400.
The minimum is 100.
The maximum is 1000.
The standard deviation is 400.25

제약 조건
* 입력 부분과 계산 부분을 수행하기 위해 루프와 배열을 사용할 것
* 배열에는 done 값을 넣으면 안 됨
* 숫자를 문자열로 변환시킬 것
* 입력 부분은 처리 부분, 출력 부분과 분리시킬 것

도전 과제
* 숫자 배열을 취하여 결과를 봔환시키는 mean, max, min, standard Deviation 함수를
  호출하도록 프로그램을 수정해보자.
* 숫자를 직접 입력 받은 대신 외부 파일에서 숫자를 읽도록 프로그램을 수정해 보자.
