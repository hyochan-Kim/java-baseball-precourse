# 숫자 야구 게임

## 구현할 기능 목록

- game 함수
  - 전체 진행을 담당하면서, game logic 함수를 실행시킨다.
  - 완료 후에는 게임을 새로 시작할지 종료할지 입력 받는다.
  
- gameLogic 함수
  - makeRandomNumbers 함수를 실행시키고
  - 숫자를 입력받는다.
  - isValidInput 함수를 통해 유효한 입력인지 확인한다.
  - strikeBallCheck 함수를 통해 결과를 출력한다.
  
- makeRandomNumbers 함수
  math.random() 함수를 통해 1-9의 숫자를 랜덤으로 만든다.
  중복이 발생하면 다시 숫자를 뽑는다.
  
- isValidInput 함수
  사용자가 입력한 값의 길이가 3인지 확인한다. 아닐 시 false를 return한다.
  int형으로 변환될 수 있는지 확인한다.(숫자인지 확인) 안될 시 false를 return한다.
  숫자로 바꾸면서 배열에 저장하고 이 때 중복되는 숫자가 있으면 false를 return한다.
  유효한 숫자임이 확인되면 true를 return한다.
  
- strikeBallCheck 함수
  입력과 목표값을 비교하여 스트라이크, 볼 결과를 출력한다.
  두 값이 모두 0일시에는 낫싱을 출력한다.
