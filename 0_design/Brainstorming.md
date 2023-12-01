# Brainstorming

컴파일 언어와 인터프리터 언어중 

인터프리터 언어로 개발 진행

## 과정 

언어 설계 

->

파서와 인터프리터 구현 <br/>
(이 단계는 Python의 CPython 인터프리터와 같이 C언어로 구현 할 것임.) 

->

IDE나 편집기 제작
(이 단계는 웹페이지에서 코드를 작성하고 실행 할 수 있는 환경을 만들것이며, 이때 WebAssembly 기술을 사용할 것임.)

* WebAssembly는 웹 어플리케이션에서 브라우저의 JavaScript 엔진 이외의 언어로도 코드를 실행할 수 있게 해주는 표준이다.
* 2번째 단계에서 만든 인터프리터를 붙이는 작업을 하는것이다.

->

표준 라이브러리 구현

->

문서 작성 

## 문법 설계

if -> 만약

for -> 반복

function -> ?

int -> 정수

float -> 소수

String -> 문자

bool -> 사실여부

true -> 사실

false -> 거짓

ex)
```
if(flag == true) {
  return true;
} else if(flag == false) {
  return false;
} else {
  return false;
}
->
만약 flag 가 사실 이라면? // 라면과 이라면 중 혼용해서 사용가능
  결과는 거짓;
또는 flag 가 거짓 이라면?
  결과는 거짓;
아니라면?
  결과는 거짓;
```

ex2)
```
int number = 0;
String text = "Test";

정수 number = 0;
문자 text = "Test";
```
