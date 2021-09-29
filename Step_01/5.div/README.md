# 210928 HTML Block and Inline Elements and class, id

### Block-level Elements
------------
```
+ 블럭 수준 요소는 항상 새 줄에서 시작함.
+ 블럭 수준 요소는 항상 사용 가능한 전체 너비를 차지함.
+ 블럭 수준 요소는 위쪽 여백과 아래쪽 여백은 있지만 인라인 요소에는 없음.
Here are the block-level elements in HTML:
<address> <article> <aside> <blockquote> <canvas>
<dd> <div> <dl> <dt> <fieldset> <figcaption> <figure>
<footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> 
<noscript> <ol> <p> <pre> <section> <table> <tfoot> <ul> <video>
```
------------

### Inline Elements
------------
```
+ 인라인 요소는 새 줄에서 시작하지 않음.
+ 인라인 요소는 필요한 만큼만 너비를 차지함.
+ Here are the inline elements in HTML:
<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code> <dfn> <em>
<i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <script>
<select> <small> <span> <strong> <sub> <sup> <textarea> <time> <tt> <var>
```
------------

### <div> 요소
------------
```
+ <div> 요소는 종종 다른 HTML 요소에 대한 컨테이너로 사용함.
+ <div> 요소에 속성은 style, class, id 를 일반적으로 사용함.
+ CSS 와 함께 사용할 때 <div> 요소는 콘텐츠 블록의 스타일로 지정하여 사용할 수 있음.
```
------------

### <span> 요소
------------
```
+ <span> 요소는 텍스트, 또는 문서의 일부의 부분을 표시하는 데 사용함.
+ <span> 요소에 속성은 style, class, id 를 일반적으로 사용함.
+ CSS 와 함께 사용할 때 <span> 요소는 텍스트 부분의 스타일을 지정할 수 있음.
```
------------

### Class Attribute
------------
```
+ Class 속성은 HTML 요소에 대한 클래스를 지정함.
+ 여러 종류의 HTML 요소는 같은 이름의 Class 속성을 가질 수 있음.
+ Class 속성은 종종 스타일 시트 클래스 이름에 포인트로 사용함.
+ 특정 클래스 이름을 가진 요소에 액세스하고 조작하기 위해 JavaScript에서 사용할 수도 있음.
+ 클래스를 생성하려면 마침표(.) 문자(ex;.class)를 작성하고 그 뒤에 클래스 이름을 사용함. 그런 다음 중괄호 {} 안에 CSS 속성을 정의함.(ex;.class {})
+ HTML 요소는 한개의 클라스가 아닌 여러 클라스에 속할 수 있음. 여러 클래스를 정의하려면 클래스 이름을 공백으로 구분함(예: <div class="city main">).
  - 요소는 지정된 모든 클래스에 따라 스타일이 지정함
+ 다른 HTML 요소가 같은 클래스에 속할 수 있음.
+ 클라스 이름은 대소문자로 구분할 수 있음.
+ 상황에 따라 JavaScript에서 특정 요소에 대한 특정 작업을 수행하는데 사용할 수 있음. ex) getElementsByClassName() 메소드를 사용함.
```
------------

### Id Attribute
------------
```
+ HTML id속성은 HTML 요소의 고유 ID를 지정하는 데 사용함.
+ HTML 문서에는 동일한 ID를 가진 요소가 두 개 이상 있을 수 없음.
+ id 속성은 스타일 시트에서 특정 스타일 선언에 포인트로 사용됨. 또한 JavaScript에서 특정 ID를 가진 요소에 액세스하고 조작하는 데 사용됨.
+ id의 구문은 해시 문자(#)와 id 이름(ex;#id)을 차례로 작성함. 그런 다음 중괄호 {} 안에 CSS 속성을 정의함.(ex;#id {})
+ 클래스 이름은 여러 HTML 요소에서 사용할 수 있지만 ID 이름은 페이지 내에서 하나의 HTML 요소에서만 사용해야함.
+ id속성은 특정 요소에 대한 몇 가지 작업을 수행하는 자바 스크립트로도 사용할 수 있음.
+ JavaScript는 다음 getElementById()메소드를 사용하여 특정 ID를 가진 요소에 액세스할 수 있음. 
```
------------

### ID 및 링크가 있는 HTML 책갈피
------------
```
+ 웹페이지의 특정 부분으로 이동할 수 있도록 하는 데 사용됨. 페이지가 매우 긴 경우 유용함.
+ 책갈피처럼 사용하려면 책갈피를 만든 다음 링크를 추가해야함.
+ 그다음 클릭하면 그 위치로 이동함.
```
------------
