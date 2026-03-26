# 🐍 Hightech_python_20260319
**python class contents**

---
### [1] 파이썬 흐름 제어 (flow control)
* **(if)** : 조건 만족하는 경우에만 실행
* **(if..else)** : 조건 만족하는 경우와 아닌 경우를 구분하여 실행 내용이 달라짐
* **(if..elif..else)** : 여러 개의 조건 만족 여부를 판단하고 각 조건에 따라 실행 내용이 달라짐
* **(Nested if..elif..else)** : 조건 구문 내부에 다른 조건 구문을 둘 수 있음
* **(for loop)** : 반복 접근 가능한 객체/연산에 처리 과정에 사용
* **(for loop + range)**
    * *** range : 숫자의 시퀀스를 생성하는 기능 제공
* **(while loop, while loop + else)** : while 루프는 조건을 만족한다면 계속 실행  
* **(break and continue)**
    * *** break : 반복 루프를 종료(루프 바로 다음의 명령문으로 실행 흐름 변경)
    * *** continue : 현재 반복의 나머지 코드를 건너떠 루프 진행
* **(pass)**
    * *** 빈 명령문(null statement)
    * *** 인터프리터가 이 명령문을 무시하지는 않지만, 아무런 작업을 수행x(주석은 인터프리터가 그 자체를 무시함)
    * *** 추후에 구현되어야할 loop, function 등의 구현 부분에 사용

---

### [2] 함수 (function)   
* 특정 작업을 수행하기 위한 관련된 명령문(statement)의 그룹
* 프로그램을 더 작고, 모듈 청크(chunk)로 나눌 수 있음
* 코드의 중복성 낮추고, 재사용성을 높일 수 있음 -> 간단하게 쓸수있다, 구조가 유연하다
* **선언양식** : 
  ```python
  def function_name(parameters) :
      """ docsting """ 
      statement (s)
---
  
### [3] Function arguments (인자)
Default arguments : 선언시에 인자의 기본값(default value)을 지정해줌, Default 이후에 모든 모든 인자는 기본값이 존재해야함(중요!)

Keyword arguments : 인자 전달시에, 위치 또는 키워드를 기반으로 적용, 키워드 인자 뒤에 위치를 사용하면 오류 발생

Arbitary arguments : 별표*를 인자명 앞에 사용, 인자에 대한 임의의 개수를 반영할 수 있음(tuple 변환 일어남)

---

### [4] 주요 개념 및 특수 함수
Recursion (재귀) : 함수가 자기 자신을 호출하는 것(기본값으로 최대 재귀깊이(depth)는 1000이긴 하지만 파이썬 버전, 성능에 따라 다름)

Anonymous/Lambda function (매우 중요)

이름(name)없이 정의된 함수

lambda 키워드를 사용해서 정의함

선언 방식(하나의 expression만 허용)

Modules
