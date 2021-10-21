#공유주소

### github

https://github.com/edu-ministori/addinedu_10_js

### codesandbox

https://codesandbox.io/s/crazy-violet-v777c?file=/README.md

# Javascript

## JS Introduction

https://www.w3schools.com/js/js_intro.asp

- Javascript 웹페이지 개발을 목적으로 하는 언어

- Front End 개발 영역에서는 HTML, CSS를 제어하고, 효과를 적용하는 기능 구현에 사용

## JS 작성방식

- External, Internal, Inline 방식
- HTML 파일에서 Javscript file 코드를 적용하는 Element의 위치
  - HTML 파일이 모두 로딩(렌더링)이 된 이후에 Javascrpt가 적용
    (HTML Element보다 아래에 위치)
  - head 태그 쪽 상단에 script를 분리해서 위치시키기 위한 방식
    - internal 방식(javascript 코드를 직접 작성하는 방식)으로는 적용 불가능
    - Extenal 방식: script 태그에 defer attibute를 사용
      - 상단에 위치하더라도 defer attribute를 사용하면, HTML Element가 모두 로딩된 이후에 javascript코드를 실행합니다.

## Javascript 언어를 공부하는 방법(순서)

> 언어적 관점
>
> - 프로그래밍 언어 문법
> - 일반적 알고리즘
>
> 활용적 관점
>
> - 활용 목적 : 웹 개발, 소프트웨어 개발, 게임 개발 / 사용 소프트웨어 목적

```
웹 Front End 개발 : Javascript
1) 언어적 관점 : Javascrpt 문법
2) 활용적 관점 : 브라우저, HTML, CSS 연관 관계 => 서비스개발

게임 개발 : 유니티/언리얼엔진 게임엔진 소프트웨어 => c#/c++
1) 언어적 관점 : C#/C++ 문법
2) 활용적 관점 : 게임엔진 소프트웨어 적용, 게임프로그래밍 최적화

```

## Javascrpit(ECMAScript) Version

- ESS
- ES6

## ES6에서 추가된 내용

- 변수 개념 확장
- class 개념 추가
- 함수 사용 하는 방식 확장
- 프레임워크/라이브러리(Reactjs), nodejs 사용됨

## Javascript 공부 내용

### 문법

- 변수(데이터) / 연산자
- 명령문(구문)
- 함수
- 배열/객체/class
- 추가 문법

### 활용

- 이벤트
- HTML, CSS 관계(제어)

### Javascript 문법

### JS Variables(변수)

https://www.w3schools.com/js/js_variables.asp

> 변수
>
> - 변하는 수
> - 수(값:데이터)가 저장되는 공간

```
변수정의(선언)키워드(예약어) 변수이름을 = 초기값;

var a = 0; (문자로 먼저시작해야함, 대소문자구분해야함)
```

> var
>
> - 변수 선언
> - 변수 값 변경 가능

```
Naming
- 동일한 이름 여러번 사용될 수 없음
- 여러단어를 사용해서 네이밍을 할 때 단어와 단어를 구분 : 가독성

snake case : car_person_name  - File/Folder
kebab case : car-person-name  - HTML id, class
camel case : carPersonName    - javascript 변수, 함수
pascal case : CarOersonName   - javascrript Class
```

### JS

https://www.w3schools.com/js/js_let.asp
https://www.w3schools.com/js/js_const.asp

- ES6에서 추가된 변수 선언 키워드

```
let a = 0;
const word = 'abc';
```

> let
>
> - 변수 선언
> - 변수 값 변경 가능

> const
>
> - 변수 선언
> - 변수 값 변경 불가능
> - 변수 값 초기화 불가능
> - 복잡한 데이터를 간단한 변수이름으로 대체 사용하기 위한 경우

### Data Types

- 숫자, 문자, 객체

> 숫자
>
> - 숫자 데이터 : 정수, 실수

> 문자
>
> - 문자 데이터 : 글자(character), 문자열(string)

> 불리언(논리데이터)
>
> - 참(true), 거짓(false)의 두가지 결과값

> 객체
>
> - 데이터 집합

> Javascript 데이터 타입을 구분하지 않음
>
> - 변수 선언시 데티어 타입을 구분하지 않음
> - 데이터 상세 타입을 구분하지 않음

- js

```
var a =1; // var - 값을 변경할 수 있는 변수 선언
```

- java

```
int a = 1; int - 정수형태의 값을 변경할 수 있는 변수 선언
short b = 1; short - 2byte 크기의 정수 형태의 값을 변경할 수 있는 변수
float c = 0.1; float - 실수 형태의 값을 변경할 수 있는 변수
string d = "hello"; string - 문자 형태 변수
```

### JS operator(연산자)

> 할당 연산자 : =

> 산술 연산자

```
-, +, /, *

% : 나머지 계산
Ex) 5 % 3 =2

+ 연산자 활용
5 + 5 = 10
5 + "a" = 5a(연결연산)
```

> 비교 연산자
>
> - 결과값 : 참(true)/거짓(false) 불리언 데이터

```
== : 같다(크기)
=== : 같다(크기, 타입)
!= : 같지않다(크기)
!== : 같지않다(크기, 타입)
> : 크다
< : 작다
>= : 크거나 같다
<= : 작거나 같다
```

> 논리 연산자
>
> - 결과값 : true/false

```
&& : AND
||(시프트+\키) : OR (| - pipe)
! : NOT

 a > 5 && a < 10 : a는 5보다 크고 10보다 작다
 a < 5 || a > 10 : a는 5보다 적거나 10도나 크다
 !(a < 5) : a가 5보다 작지 않다
```

> 산술 연산 + 할당 연산

```
let a = 0;
a = a +1;
=> 반복실행 a의 변화 : 0 => 1 => 2 => 3 => 4 ...

변수 += 값; 값만큼 일정한 증가 연산
a += 3;

a = a + 1;
a += 1;
a++; (증가연산)

a = a - 1;
a -= 1;
a--; (감소연산)
```

### JS Condition

- condition : 조건문 / 분기문

> if : 조건문 / 분기문 (분기문으로 기억하자)
>
> - 식의 결과 값이 참이면 실행문 실행

```
if(condition){
  실행문
}

condition : 결과값이 boolean 데이터인 식

if(a>10){} : a>10 => true/false

if(a+1){} a+1 => 음수, 0, 양수 : 0(false) / 정수(true)

if(a){} a => ture/false | 0(false) / 정수(true)

if(ture){}

if(condition1){
  실행문1
} else if(condition2){
  실행문2
} else if(condition3){
  실행문3

else if : 필요시 사용, 여러번 반복 사용 가능
else : 필요시 사용, 마지막에 한번 사용 가능
```

### JS switch

> switch : 분기문

```
switch(experssion){}

expression : 표현식, 결과값이 일반 데이터(숫자, 문자, 불리언)

switch(a+1){
 case 결과값1:
  실행문1;
  break;
 case 결과값2:
  실행문2;
  break;
 default:
  실행문3;
}
```

### For loop(반복문)

https://www.w3schools.com/js/js_loop_for.asp

- For 반복문 : 반복 횟수를 정해서 반복 실행

```
for(statement1; statement2; statement3){}

statement1 : for 반복문 실행전 최초 1번 실행 구문
statement2 : 코드 블럭을 실행하기 위한 조건식(비교식) 구문
statement3 : 코드 블럭 실행 후 매번 반복 실행되는 구문

=> 3개의 statement는 반복횟수를 결정하는데 연관되는 구문

for(let i=0; i<10; i++){
  console.log("반복실행");
}

0) let i=0 구문 실행 => i=0

1) i<3 비교식 실행 => true
2) 코드블럭 실행(1)
3) i++ 실행 => i=1

1') i<3 => true
2') 코드블럭 실행(2)
3') i++ 실행 => i=2

1'') i<3 => true
2'') 코드블럭 실행(3)
3'') i++ 실행 => i=3

1''') i<3 => false
반복 실행 종료
```

### break / continue

- break

  - 루프 구문 바깥으로 빠져나가는 키워드(구문)

- continue
  - 해당 회차 실행을 건너뛰기하는 키워드(구문)

### while loop

- condition이 true인 동안 반복 실행하는 구문

```
while(codition){
  // 코드블럭
}
```

```
while 사용 예 : 로그인

** while(true){} => 무한 루프

while(true){

  //로그인 시도
  if(입력한아이디 === 저장된아이디 && 입력한비밀번호 === 지정된비밀번호){
    // 로그인 성공
    break;
}
```

### JS Function

https://www.w3schools.com/js/js_arrow_function.asp

> 함수
>
> - 여러 실행코드를 하나로 패키징하는 역할
> - 특정 기능을 할 수 있는 코드 블럭 단위로 패키징
> - 특정 기능을 재사용하기 위해서 함수 사용

> - 매개변수
>   - 함수에 넣어주는 재료
>   - 함수에 여러가지 매개변수 값을 넣어줌으로써 다양한 결과를 얻을 수 있음

> - return(반환값)
>   - 함수에 처리한 결과값
>   - 함수를 호출한 쪽으로 결과값을 되돌려줌

```
1.함수선언
function 함수이름([매개변수]){
  // 실행 코드 블럭

  [리턴값]
}

2.함수호출(실행)
함수이름();


** [] : 생략가능
```

### JS Araay(배열)

- 개수가 많은 데이터를 대표되는 하나의 변수 이름으로 저장할 때 사용하는 데이터 타입

```
배열 선언

let cars = ['volvo', 'bmw', 'ssab'];

cars[0] = 'volvo';
cars[1] = 'bmw';
cars[2] = 'ssab';

배열 변경
cars[0] = 'hyudai';
```
