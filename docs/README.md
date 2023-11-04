# 기능 목록

- [X] 구매 금액 입력 기능
  - [X] 1,000 으로 나누어 떨어지지 않으면 예외 발생(IllegalArgumentException)
- [X] 구매 금액 계산 기능
- [X] 모든 로또 번호 출력 기능
  - [X] 로또 번호 출력 기능 (오름차순)
    - [X] 1~45 범위의 중복 없는 랜덤 번호 6 개 선택 기능
    **camp.nextstep.edu.missionutils.Randoms pickUniqueNumbersInRange()**
- [X] 당첨 번호 입력 기능 (쉼표로 구분)
- [X] 보너스 번호 입력 기능
**camp.nextstep.edu.missionutils.Console readLine()**
  - [X] 로또 번호가 1~45 범위 밖이라면 예외 발생
  - [X] 로또 번호 개수가 6 개가 아니라면 예외 발생
  - [ ] 로또 번호에 중복된 숫자가 있으면 예외 발생
- [ ] 당첨 내역 계산 기능
  - [ ] 당첨 기준과 금액 enum 적용
- [ ] 당첨 내역 출력 기능 
- [ ] 수익률 계산 기능 (소수점 둘째 자리 반올림)
- [ ] 수익률 출력 기능