# 자동차 경주 게임

## 기능 목록

1. **n대의 자동차 이름 입력 받아 각 자동차 객체 생성**
   -쉼표(,)를 기준으로 구분하기.
   -5자 이하만 입력받기.
   - 빈 문자열 또는 NULL 값은 예외 처리.
   - 위 조건에 맞지 않는 입력을 할 경우  IllegalArgumentException을 발생시킨 후 애플리케이션은 종료 시키기.
   - 입력받은 자동차 객체의 초기 위치 설정 ( 모든 자동차의 위치를 0 설정)

2. **시도할 횟수 입력 받기**
   - 음의 값을 받으면  IllegalArgumentException을 발생시킨 후 애플리케이션은 종료 시키기.
   

3. **자동차 이동 로직 구현**
   - Randoms.pickNumberInRange(0, 9)` 메서드를 통해 생성된 무작위 값이 4 이상일 경우 자동차가 전진시키기.
  

4. **우승자 계산 및 출력**
   - 가장 멀리 전진한 자동차 계산하여 우승자 선정.
   - 매라운드 우승자 우승횟수 증가
   - 공동 우승자가 있을 경우 쉼표(,)로 구분하여 우승자 출력
