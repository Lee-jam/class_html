# 210922 - Html Note

- <tagname blank> 에서 blank에 속성을 추가할 수 있음.
- 속성 추가 : style, title 등 태그네임마다 알맞는 속성을 상황에 맞게 추가해 사용할 것.

### HTML display
------------
+ HTML이 어떻게 표시될지는 확신할 수 없으며 크거나 작은 화면, 크기 조정된 창은 다른 결과를 생성함.
+ HMTL을 사용하면 HTML 코드에 공백이나 줄을 추가하여 표시를 변경할 수는 없음.
+ 브라우저는 페이지가 표시될 때 추가 공백과 줄을 자동으로 제거하기 때문에 태그를 사용하여 공백 및 줄띄움을 추가해야함.
+ <!--<hr> 태그는 HTML 페이지에서 수평선을 표시함. 콘텐츠를 분리할 때 사용됨. -->
+ <!--<br> 태그는 HTML 페이지에서 enter(줄바꿈)와 같은 역할을 함.-->
+ <!--<pre> 태그는 글꼴Courier로 표시되며 공백과 줄바꿈을 모두 유지함.-->

### HTML Style
------------
+ HTML 스타일은 HTML 내부에서 정하거나 CSS 파일을 추가하여 정의함.
+ 가독성을 높이기 위해 CSS 파일을 사용하는 것을 추천함.

+ HTML - tagname style="property:value"
	+ CSS 파일 내에 정의할 때는 tagname {property(속성)와 value(값)} 만 사용함.
	+ CSS color 속성은 HTML 요소의 텍스트 색상을 정의함.
	+ CSS font-family 속성은 HTML 요소에 사용할 글꼴을 정의함.
	+ CSS background-color 속성은 HTML 요소의 배경색 설정함.
	+ CSS font-size 속성은 HTML 요소의 텍스트 크기를 정의함.
	+ CSS text-align 속성은 HTML 요소의 수평 텍스트 정렬을 정의함.
	+ CSS border 속성은 HTML 요소의 주위 테두리를 정의함.
	+ CSS padding 속성은 텍스트와 테두리 사이 공백을 정의함.
	+ CSS margin 속성은 테두리 외부의 공백을 정의함.

## What is CSS?
------------
### CSS는 Cascading Style Sheets의 준말로 웹페이지 레이아웃의 형식을 지정하는데 사용됨.

#### CSS는 3가지 방법으로 HTML 문서에 추가할 수 있음.
+ Inline - HTML 요소 내부의 Style 속성 사용 ex) <!--<h1 style="color:blue">안녕하세요</h1>-->
+ Internal - head 섹션의 style 요소 사용
+ External - link 요소를 사용하여 외부 css파일에 연결

### HTML 서식
------------
```
+ <b> - 굵은 텍스트
+ <strong> - 중요한 텍스트
+  <i> - 기울임꼴 텍스트
+ <em> - 강조된 기울임꼴 텍스트
+ <mark> - 표시된 텍스트
+ <small> - 더 작은 텍스트
+ <del> - 삭제된 텍스트
+ <ins> - 삽입된 텍스트
+ <sub> - 아래 첨자 텍스트
+ <sup> - 위 첨자 텍스트
```
### HTML 인용문 사용
------------
+ blockquote 요소는 다른 소스에서 인용문을 정의할 때 사용함.
+ q 요소는 짧은 인용문을 정의할 때 사용함.
+ abbr 요소는 줄임말, 약어에 마우스를 놓았을 때 설명을 표시함.
+ address 요소는 연락처 정보를 정의할 때 사용함.
+ cite 요소는 창작물의 제목을 정의함. /참고 사람의 이름은 작품의 제목이 아님. 일반적으로 기울임꼴로 렌더링됨.
+ bdo 요소는 양방향 재정의를 의미함.

### HTML 색상
------------
+ HTML 색상은 140개의 표준 색상이름을 지원함.
+ background-color 요소는 배경색을 설정함.
+ color 요소는 텍스트 색을 설정함.
+ border:"0px" solid "color" 요소는 테두리 색상을 설정함.
+ 색상은 RGB 값, HEX값, HSL값, RGBA값 HSLA값을 사용하여 색상을 지정할 수 있음.

### HTML 링크
------------
+ HTML에 하이퍼링크를 올려 다른 문서, 페이지로 이동할 수 있음.
+ a 요소는 하이퍼링크를 정의함.
+ target 속성을 지정하여 링크를 클릭하였을 때 새 브라우저 창이나 탭에서 연결할 지 정할 수 있음.
+ _self 속성은 기본. 클릭한 것과 동일한 창/탭에서 문서를 염.
+ _blank 속성은 새 창이나 탭에서 문서를 염.
+ _parent 속성은 부모 프레임에서 문서를 염.
+ _top 속성은 창의 전체 본문에서 문서를 염.
+ ex) <!--<a href="www.google.com" target="_black">구글 홈</a>-->
