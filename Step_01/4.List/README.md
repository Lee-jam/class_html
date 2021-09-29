# 210925 HTML LIST START

### HTML List
------------
```
+ 정렬되지 않은 목록은 <ul> 태그로 시작함. ; unordered list
+ 정렬된 목록은 <ol> 태그로 시작함. ; ordered list
+ 목록의 각 항목은 <li> 태그로 시작함. ; list
+ 설명 목록도 지원하며 <dl> 태그를 사용하며 <dt> 태그는 이름을 정의하고 <dd> 태그는 각각의 용어를 설명함. ; description list
+ 목록은 중첩시킬 수 있음. 목록 내부에 목록 가능함.
```
------------
### HTML unordered List
------------
```
+ 정렬되지 않은 목록은 CSS에서 list-style-type 속성은 목록 항목 마커의 스타일을 정의하는데 사용함.
 - 다음 값 중 하나를 가질 수 있음.
  - disc : default 값
  - circle : 배경색이 없는 동그라미 스타일
  - square : 사각형 모양
  - none : 마커가 없음.
```
------------
### HTML ordered List
------------
```
+ 정렬된 목록은 type 속성으로 마커의 스타일을 정의함.
    + type="1"	default 값
    + type="A"	ABC 순서의 스타일;대문자
    + type="a"	abc 순서의 스타일;소문자
    + type="I"	로마 숫자 스타일;대문자
    + type="i"  로마 숫자 스타일;소문자
+ 기본적으로 순서가 지정된 목록은 1부터 계산을 시작함. 지정된 숫자부터 계산을 시작하려면 다음 start속성을 사용할 수 있음.
    ex) <ol start="50"> ==> 50부터 시작 50 51 52
```
------------
### HTML description List
------------
```
+ HTML <dl>요소를 사용하여 설명 목록 정의
+ HTML <dt>요소를 사용하여 설명 용어 정의
+ HTML <dd>요소를 사용하여 설명 목록에서 용어 설명
```
------------