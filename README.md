# 🏎️ 자동차 경주 게임_조혜송

### 구현기능
0. 일시적으로 태그를 숨기는 함수
    - 게임 횟수 입력 받기,결과 출력와 관련 된 태그를 일시적으로 숨겨준다.
1. 자동차 이름을 입력받는 함수
    - 자동차 이름을 5 이하로 입력받는다.
    
    	:pushpin: 예외사항
        - 입력 없이 확인 버튼을 눌렀을 시
        - 5자를 초과하는 이름을 한 개라도 입력했을 시
        - "east,west,south,north" 가 아닌 다른 형태로 입력 했을 시에

        :pushpin: 올바르게 입력 되었을 때
        - 시도 횟수를 입력받는 화면을 그려준다.

2. 사용자로부터 시도 횟수를 입력받는 함수
    - 사용자로부터 숫자를 입력받는다.
    	
        :pushpin: 예외사항
        - 유효한 숫자 이외의 값을 입력했을 시
        - 1미만의 숫자를 입력 했을 시에

3. 자동차 경주 게임을 진행
    - 자동차들을 대상으로 random 한 값을 받는다.
    - random 한 숫자가 4 이상 일 때 한 칸 이동한다.
    - random 한 숫자가 3 이하 일 때 움직이지 않는다.
        :pushpin: 진행 결과 출력
        - 각 회차 마다 진행하는 자동차들의 이동 상황을 그려준다.
        
4. 최종 우승자를 출력하는 함수
    - 가장 많이 이동한 우승자를 계산하여 출력해준다.
