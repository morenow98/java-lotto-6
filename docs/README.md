# 🎰  미션 - 로또

---

## 📮 기능

### 구입 금액 입력 및 검증 기능
- [X] `구입 금액을 입력해 주세요.` 메시지를 출력한다.
- [X] 구입 금액을 입력받는다.
- [X] 입력된 금액이 1000으로 나누어 떨어지는 지 확인한다.
  - [X] 사용자가 잘못된 값을 입력할 경우 에러 메시지 출력 후 재입력받는다.

### 로또 구매 및 출력 기능
- [X] 구매한 개수를 알려주는 메시지를 다음과 같이 출력한다. <br>
  ```
  8개를 구매했습니다.
  ```
- [X] 로또를 구매한다.
- [X] 구매한 로또를 전부 출력한다. 각 로또는 다음과 같이 출력한다. <br>
  ```
  [8, 21, 23, 41, 42, 43] 
  ```

### 당첨 번호와 보너스 번호 입력 기능
- [X] `당첨 번호를 입력해 주세요.` 메시지를 출력한다.
- [X] 당첨번호 6개를 입력받는다.
- [X] `보너스 번호를 입력해 주세요.` 메시지를 출력한다.
- [X] 보너스번호 1개를 입력받는다.
- [X] 당첨번호가 `,` 로 나누어진 6개의 1부터 45사이의 정수인지 확인한다.
  - [X] 사용자가 잘못된 값을 입력할 경우 에러 메시지 출력 후 재입력받는다.
- [X] 보너스번호가 1부터 45사이의 정수인지 확인한다.
  - [X] 사용자가 잘못된 값을 입력할 경우 에러 메시지 출력 후 당첨 번호부터 재입력받는다.

### 당첨 통계 및 출력 기능
- [X] `당첨 통계` 와 `---` 메시지를 출력한다.
- [X] 당첨이 얼마나 됐는지 통계를 낸다.
  - [X] 당첨 번호와 로또 번호들을 비교한다.
    - [X] 일치하는 번호가 몇 개인지 확인한다.
- [X] 수익률을 계산한다.
- [X] 5등부터 1등까지 각각 몇 개가 당첨됐는지와 수익률을 다음과 같이 출력한다. <br>
  ```
  3개 일치 (5,000원) - 1개
  4개 일치 (50,000원) - 0개
  5개 일치 (1,500,000원) - 0개
  5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
  6개 일치 (2,000,000,000원) - 0개
  총 수익률은 62.5%입니다.
  ```