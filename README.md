# Data Analysis


## 2강 실습
### 실습 내용
- 리스트 슬라이싱
- 리스트 컴프리헨션
- 문자열 형식화
- 컨텍스트 관리 

#### ❕Aha moment
- with
- 파일 관리 -> close()
- 복수개의 파일
- URL 연결 관리

## 3강 실습
### 실습 내용
- 언패킹
- 언더스코어
- 예외 처리
- 함수형 프로그래밍

#### ❕Aha moment
- 언패킹 -> Javascript 구조분해 할당과 비슷함
- 예외처리 -> Javascript `try` `catch` `finally`
- lambda -> Javascript 화살표 함수랑 비슷함 lambda 명칭을 써서 정의한다
  #### e.g.
  ```python
  adjust_salary = lambda salary: f'{salary * 1.1:.0f}
  ```
  - salary 인수, 파라미터 자리
  - return문 없어도 됨
- `map`, `filter` 그리고 `functools`에 있는 `reduce`
  - Javascript와 의미는 비슷하지만 문법이 약간 다르다.
    ```
    map(함수, 데이터)
    ```
    - 두번째 인수 데이터를 받고 첫번째 인수자리에 가공할 함수를 넣어준다. (lambda를 바로 작성하거나 따로 변수로 만들어 작성해도 됨)
    - 데이터가 첫번째 인수 함수인자로 하나씩 인덱스별로 넘어가 작동됨.
    - Javascript callback function를 생각하면 이해하기 쉽다.
