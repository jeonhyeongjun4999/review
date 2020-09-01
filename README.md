# review
> 2020.08.19


메서드 재정의
wrapper클래스 
깊은복사 얕은복사
예외(Exception) 학습
스플릿 사용시 for문을 사용하는이유
wrapper 이퀄은 객체의 초기화 값 비교
object의 이퀄은 객체 주소값 비교
MVC 패턴 정리



[유효범위] 
스코프(Scope)
- 메소드 안에서 변수 선언시 해당 메소드에서만 사용가능
다른메소드에는 영향을 주지 않는다
메소드 A (변수 a)
메소드 B (변수 a)
메소드내에서만 사용가능한 변수

[다양한 유효범위]
전역변수 - 클래스에서 변수를 선언 // 모든 곳에서 가져다 사용할 수 있음
지역변수 - 메소드 내에서 변수를 초기화 // 메소드 내에서만 동작가능한 변수

[this]
메소드 내에서 지역변수(a)와 전역변수(a)를 동시에 사용해야 하는 경우
지역변수는 a로 그대로 표기하여 사용하고 전역변수의 경우 this. 구분자를 통해
전역에서 받아오는 값임을 표시해준다 (ex.this.a)

[초기화]


for문 - while의 구조를 압축한 반복실행문
 - 기본형태
 	//for(초기화; 종료조건; 증감식) {조건}
	
	
While문 - 반복문의 기본
 - 기본형태
 	
	//while(조건식) {조건;}
 - 이해
 	//조건식 영역에 입력한내용이 true값을 갖는 경우 실행할 조건을 실행시키며
	  값의 범위를 조절해주지 않으면 무한대로 출력값을 갖게됨
	  초기화를 통한 범위설정 or 조건에 맞는 값 출력시 break를 통해 출력중지
	  continue 사용시 다시 무한대로 값출력





[데이터타입]

참조타입 

1.일반적인 클래스

형태 - class 클래스이름 extends 부모클래스 {}

	객체생성 - 클래스명 변수명 = new 클래스명;

2. String 클래스

String은 "클래스"의 형태 : 기본타입과 다름
이해 : char 타입 자료형의 값들이 여러개 붙어있는 형태이다

3. Wrapper 클래스

기본타입을 참조타입 형태로 사용할 수 있다
형태 - 기본타입의 맨앞자리를 대문자로 치환 
(예외 : int의 경우 Wrapper클래스에서는 Integer로 사용)

기본타입의 경우 null 값을 사용할 수 없지만
Wrapper 클래스의 경우 null 값을 사용할 수 있다.

******* 박싱 | 언박싱 개념 더 공부하고 찾아보기 ******
