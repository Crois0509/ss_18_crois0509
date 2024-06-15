코드 스타터 캠프 2주차 미션을 위한 저장소입니다.

# Step1: 로또 당첨번호 생성기 순서도 생성하기

* 이번 Step 1에서는 랜덤한 로또 당첨 번호를 생성하는 함수의 순서도부터 만들어 보기. 

* 이 함수는 다음과 같은 기능을 갖는다.
    * 1부터 45 사이의 랜덤한 숫자를 생성한다.
    * Collection 타입 중 하나의 형태로, 6개의 랜덤한 숫자를 저장한다.
        * 6개의 숫자는 **'서로 겹치지 않아야'** 한다.
    * 이 함수는 6개의 랜덤한 숫자를 저장한 Collection 타입 중 하나의 형태로 값을 반환한다.
* [작업 디렉토리](./CodeStarterCamp_Week2/Step1/)

# Step2: 내 번호와 맞추어보기!
* Step1의 순서도를 바탕으로 로또 당첨 번호를 생성하는 함수를 생성한다.
* 내가 찍은 번호 배열을 myLottoNumbers 변수에 할당한다.
* 찍은 번호와 로또 당첨 번호의 겹치는 숫자를 확인하는 함수를 생성한다.
    * 겹치는 번호를 포함하는 문구를 print 한다.
        * "축하합니다! 겹치는 번호는 1, 2, 3, 4, 5, 6 입니다!"
    * 만약 겹치는 번호가 없다면 다음과 같은 문구를 print한다.
        * "아쉽지만 겹치는 번호가 없습니다."
* [작업 파일](./CodeStarterCamp_Week2/Step2/LottoNumbersFactory.swift)
