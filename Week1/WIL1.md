# What I Learned - 1st Week of Front-End Study, 2023, 2nd Semester

## 1. 개괄
자바스크립트의 대부분의 요소는 Java/C/C++와 비슷하다. 다만 다른 점은 Python과 같이 동적 타입 언어이면서 인터프리터 언어라 컴파일은 빠른 대신 구동이 느리다. 대신 호환성이 우수하다. WIL에서는 C/C++과 명시적으로 차이가 있는 부분 위주로 서술한다.

## 2. 자바스크립트의 객체
C/C++/Java와 비슷하다.

### 2.1. 자바스크립트 객체의 구조
딕셔너리와 비슷하다고 보면 된다. property = key, value = value라고 생각하면 편하다. 이런 키-값 쌍의 집합을 하나의 객체로 보는 것이다.
|객체||
|----|----|
|프로퍼티 1|밸류 1|
|프로퍼티 2|밸류 2|
|....|...|
|프로퍼티 N|밸류 N|

### 2.2. 자바스크립트 객체의 표현
1. Object Literal Style
    ```var (ObjName) = {"PropertyName1" : "PropertyVal1", 'PropertyName2' : "PropertyVal2"};```
2. Constructor
   ```var ObjName = new Object();```

## 3. 자바스크립트 함수
입력값에 대해 특정 연산을 한 후 값을 반환. 위치는 무관

### 3.1. 자바스크립트 함수의 표현


선언 : 앞에 function 키워드로 선언을 명시한다.
```function funcName(paramName) {연산식;}```

### 3.2. 객체의 메소드
프로퍼티 중 함수 객체를 참조하는 프로퍼티를 메소드(method)라 부른다.
메소드로 객체 지향 프로그래밍의 목표 중 encapsulation을 실현할 수 있다.

## 4. 사용자 인터페이스(UI)

### 4.1. 대화상자 입출력
1. alert : 경고 대화상자. 사용자의 주의를 환기하기 위한 기능이다.
2. prompt : 입력 대화상자. 문자열을 인수로 받는 칸이 생긴다.
3. confirm : 확인 대화상자. 확인을 위한 Y/N 선택이 가능하다.

### 4.2. 콘솔 입출력
1. dir : 객체의 대화형 목록 출력
2. error : 오류 메시지 출력
3. info : 메시지 타입 로그 출력
4. log : 일반 로그 출력
5. time : 처리 시간 측정용 타이머 시작
6. timeEnd : 처리 시간 측정용 타이머 종료 및 결과 출력(ms 단위)
7. trace : 스택 트레이스 출력
8. warn : 경고 메시지 출력

콘솔 입력 : ```Console.log("string", ObjName);```