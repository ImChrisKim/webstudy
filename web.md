# 시험 문제 연습

## html

### 제공된 힌트들

- 이미지 태그 : img src = "이미지 경로" alt = "이미지에 대한 텍스트 설명"
  - src : 이미지에 대한 경로
  - alt : 이미지가 표시되지 않는 경우 메세지 대신 출력

- p 태그 : 문단을 나눈다.

- 절대경로와 상대경로의 차이 및 특징
  - 절대 경로 : 처음부터 목적지까지 절대적인 경로
  - 상대 경로 : ./ -> 현재 위치 ../ 현재 위치에서 상위 디렉토리

- input type의 종류 : <input type:"text" value="", placeholder="">
  - text : 텍스트 표시
  - password : text가 암호화
  - radio : 한가지만 선택할 수 있는 버튼
  - checkbox : 다중 선택 가능한 버튼
  - submit : [제출] 버튼생성 (value 지정시 value 버튼 생성)
  - button : [value] 버튼생성

- semantic tag
  - 시멘틱태그 => 의미론적웹. SEO 상승
  - header : 헤드라인
  - nav : 메뉴 목차
  - main : 메인 컨텐츠를 정의 (페이지당 하나)
    - section : 독립적인 섹션을 정의
  - article : 독립적인 구성 요소
  - aside : 사이드바

- HTML
  - 마크업 언어

- UI UX
  - UX
    - 유저 경험
    - 이용 후 반응을 생각하면서 설계
  - UI
    - 인터페이스 시각화
  
- flex
  - 메인축을 기반으로 정렬

### 힌트가 아닌 것들

- input의 종류 : <input type:"text" value="", placeholder="">
  - type : input 태그에 대한 타입을 명시
    - ex ) text, password, button, checkbox, radio
  - value : 기본값을 작성할 때 사용
  - placeholder : 무엇을 입력해야 할지에 대한 명시

- select tag : option중에 선택, 전송 하기 위한 태그





## css

### 제공된 힌트들

- 적용방법 3가지 (태그)
  - style : style .class=""
  - link : line href="" rel =""
  - inline div style=""

- 선택자의 종류 (class , id, tag etc)
  - 전체 선택자 : *
  - 유형 선택자 : 태그명 사용 (div 등)
  - class 선택자 : .은 class를 나타낸다
  - id 선택자 : #은 id를 나타낸다.
  
- 글자 색
  - color : red;

- 가운데 정렬 법 text content etc
  - text-aligh : cetner

- div 원으로 만드는 방법 
  - width : 넓이
  - height : 높이
  - border-radius : 꼭지점 부분을 둥글게 (50%로 하면 원)

- display - block inline 차이점
  - inline
    - 줄 바꿈 없음
    - 높이, 넓이, 간격 등 지정이 불가능
    - span태그, a 태그
  - block
    - 줄 바꿈이 가능
    - 간격 등 지정이 가능
    - div태그, p태그, h1태그

- 어떤태그가 block, inline 인지

- position 에 대해서
  - fix : 페이지가 바뀌어도 움직이지 않음
  - relative : 현재 위치 기준으로 움직임
  - absolute : 부모 class 기준으로 움직임

- z-index

### 힌트가 아닌 것들

- font 관련 CSS
  - color : red 색상
  - font-size : 30px 크기
  - font-weight : bold 두께

- border : 테두리를 그릴 수 있는 css
  - ex) border : 1px solid red

- inline-block :
  - 줄 바꿈 없음
  - 간격 등 지정이 가능
  - select, button 등

## Java Script

### 제공된 힌트들

- java는 JS와 관련이 있냐?
  - 없다

- js type
  - 원시 자료형 타입
    - number
    - string
    - Boolean
    - null
    - unidentified
  - 참조 자료형 타입
    - Array
    - Object
    - Function

- var let const
  - var : 함수 레벨 스코프, 변수 선언
  - let : 블록 레벨 스코프, 변수 선언, 객체 변경 가능
  - const : 블록 레벨 스코프, 변수 선언, 객체 변경 가능

- const 배열, 객체 변경가능한가? 
  - 배열은 불가능
  - 객체는 가능

- object에 접근하는 방법
  - Object['a']
  - Object.a

- dom가져오기 query selector
  - document.queryselector("가지고 오고 싶은거")

- addEventLissener
  - a.addEventLissner('이벤트이름','핸들러이름')
  - 이벤트 리스너에 콜백 함수를 등록한다.



- textContent

- createelement
  - Element Node를 생성
    - let btn = createElement('button')
  - Text Node를 생성한다.
    - let txt = createTextNode("gogo")
  - 객체 밑으로 자식 노드를 추가
    - btn.append(txt);
  - Node의 속성을 부여한다. (BTS라는 id를 추가)
    - btn.setAttribute("id","BTS")


- classlist
  - classList.add
    - class의 속성값을 추가한다.
  - classList.remove
    - class의 속성값을 제거한다.
  - classList.toggle
    - class속성값이 없다면 추가
    - class속성값이 있다면 제거
  - classList.contains
    - class가 추가되었는지 확인
  - classList.replace
    - 속성값을 새로운 속성값으로 교체

- cdn
  - 빠르게 서버를 이용할 수 있도록 caching 서버를 두어 가장 가까운 서버에 접속할 수 있도록 하는 서비스

- bootstrap 까는 거임 (링크거는거 자체가)

- Node.js
  - JS 의 런타임이다. 즉, JS 로 만든 발명품
  
- null vs undefined
  - null : 값이 비어있다고 명시
  - unidentified : 아무 값도 할당받지 않은 상태
  
- bootstrap 사용 시 장점이 뭘까?
  - 홈페이지를 빠르게 만들 수 있다.
  - 반응형 웹을 쉽게 만들 수 있다.
  
- min.js 
  - 엔터, 띄어쓰기 등 모든 용량 줄인 파일

### 힌트가 아닌 정보들

- Javascript 문법
  - let : 변수할당
  - const : 변수할당 but 재 할당 불가
  - 스코프 : 함수 내에서 선언된 변수는 함수 내에서만 유효

- 출력하기
  - console.log(txt)
- prompt로 입력 받기
  - var txt = __prompt__("입력하시오)
- alert로 출력하기
  - alert(typeof txt)

- Number vs String 형 변환이 자유롭다.
- 파이썬처럼 + 연산자로 문자열 붙이기 가능
- 나머지는 C언어와 유사하다 (조건문 등)
