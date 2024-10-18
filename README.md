# java-calculator-precourse

## ✔️ 프로젝트 개요

- 덧셈할 문자열을 입력한다.
  - 구분자를 기준으로 숫자를 분리한다.
- 분리한 각 숫자의 합을 출력한다.

## ✔️ 구현 기능 목록

### 덧셈할 문자열 입력을 요구하는 문구 출력 기능

- [x] 덧셈할 문자열을 입력을 요구하는 문구를 콘솔에 출력한다.

### 덧셈할 문자열 입력 기능

- [x] 뷰에서 구분자와 양수로 구성된 문자열을 입력받는다.
- [ ] 입력 단에서의 검증
  - [ ] 빈 문자열이 입력된 경우를 검증한다.

### 입력된 문자열에 구분자 여부를 확인하는 기능

- [x] 입력된 문자열에 구분자가 있는 경우
  - [x] 쉼표(`,`) 또는 콜론(`:`) 구분자가 사용된 경우를 검증한다.
  - [x] 커스텀 구분자(`//`와 `\n` 사이에 위치하는 문자)를 사용한 경우를 검증한다.
  - [x] 구분자가 올바르게 정의되었는지 검증한다.

### 덧셈할 문자열에서 숫자를 추출하는 기능

- [x] 구분자를 기준으로 숫자를 추출하는 기능을 만든다.
- [x] 추출한 숫자 검증
  - [x] 양수가 입력되었는지 검증한다.
  - [x] 양수가 아닌 문자가 입력되었는지 검증한다.
  - [x] 양수가 아닌 음수가 입력되었는지 검증한다.

### 숫자를 더하는 기능
- [x] 문자열에서 추출한 숫자들을 더하는 기능을 만든다.

### 덧셈한 문자열을 출력하는 기능

- [x] 구분자가 있는 경우 모든 양수를 더한 값을 출력한다.
- [x] 구분자가 없는 경우 입력받은 양수를 출력한다.