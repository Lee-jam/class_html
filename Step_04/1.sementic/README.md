# 211010 Sementic Web Study

### What are Sementic Elements
------------
+ W3C에 따르면 **"시맨틱 웹을 사용하면 애플리케이션, 기업 및 커뮤니티에서 데이터를 공유하고 재사용할 수 있습니다."**
+ 시맨틱 요소란 의미론적 요소는 브라우저와 개발자 모두에게 의미를 명확하게 설명을함.
  + 의미없는 요소의 예: `<div>` 및 `<span>` - 에 내용에 대해서 알려주지 않음.
  + 의미 요소의 예 : `<form>`,`<table>` 및 `<article>`- 에 내용를 명확하게 정의함.
------------

### Sementic Elements in HTML
------------
+ 많은 웹 사이트에는 탐색, 머리글 및 바닥글을 나타내는 `<div id = "nav"> <class="header"> <div id = "footer>` 와 같은 HTML 코드가 포함되어 있음.
+ HTML에서 웹 페이지의 다른 부분을 정의하는데 사용할 수 있는 몇 가지 의미론적 요소가 있음.
  + `<article>`
  + `<aside>`
  + `<details>`
  + `<figcaption>`
  + `<figure>`
  + `<footer>`
  + `<header>`
  + `<main>`
  + `<mark>`
  + `<nav>`
  + `<section>`
  + `<summary>`
  + `<time>`
------------

### HTML <section> Elements
------------
+ `<section>` 요소는 문서의 섹션을 정의함.
  + W3C의 HTML 문서에 따르면 **"섹션은 일반적으로 제목이 있는 주제별 콘텐츠 그룹입니다."**
+ `<section>` 요소를 사용할 수 있는 위치의 예 :
  + Chapters
  + Introduction
  + News items
  + Contact information
+ 웹 페이지는 일반적으로 소개, 콘텐츠 및 연락처 정보를 위한 섹션으로 분할될 수 있음.
------------

### HTML <article> Elements
------------
+ `<article>` 요소는 독립적인 컨텐츠를 명시함.
+ article은 그 자체로 의미가 있어야 하며 웹 사이트의 나머지 부분과 독립적으로 배포할 수 있어야함.
+ `<article>` 요소를 사용할 수 있는 위치의 예 :
  + 포럼 게시물
  + 블로그 게시물
  + 사용자 의견
  + 제품 카드
  + 신문 기사
------------

### Nesting <article> in <section> or Vice Versa?
------------
+ `<article>` 요소는 독립적인 내용을 독립적으로 명시함.
+ `<section>` 요소는 문서의 섹션을 정의함.
+ 정의를 사용하여 해당 요소를 중첩하는 방법을 결정하는가? No.
+ 그래서 우리는 섹션 요소에 결합할 수 있는 article 요소, 그리고 article요소에 결합할 수 있는 섹션 요소를 찾을 것이다.
------------

### HTML <header> Element
------------
+ `<header>` 요소는 소개 내용이나 탐색 링크의 집합에 대한 컨테이너를 나타냄.
+ `<header>` 요소는 일반적으로 아래의 것들을 포함함.
  + 하나 이상의 제목요소`(<h1> - <h6>)`
  + 로고 또는 아이콘
  + 저작권 정보
+ **참고:**`<header>` 하나의 HTML 문서에 여러 요소가 있을 수 있으나 `<header>`내에 `<footer>`,`<address>`또는 다른 `<header>` 요소는 배치할 수 없음.
------------

### HTML <footer> Element
------------
+ `<footer>`요소는 문서나 구역의 바닥글을 정의함.
+ `<footer>`요소는 일반적으로 아래의 것들을 포함함.
  + 저자 정보
  + 저작권 정보
  + 연락처 정보
  + 사이트맵
  + 맨 위 링크로 돌아가기
  + 관련된 문서
+ `<footer>`하나의 문서에 여러 요소가 있을 수 있음.
------------

### HTML <nav> Element
------------
+ `<nav>`요소는 탐색 링크의 집합을 정의함.
+ 문서의 모든 링크가 `<nav>`요소 내부에 있어야 하는 것은 아님. 
+ `<nav>`요소는 탐색 링크의 주요 블록을 위한 것.
+ 장애가 있는 사용자를 위한 화면 판독기와 같은 브라우저는 이 요소를 사용하여 이 콘텐츠의 초기 렌더링을 생략할지 여부를 결정할 수 있음.
------------

### HTML <aside> Element
------------
+ `<aside>` 요소는 저장되는 내용을 제외하고 어떤 컨텐츠를 정의함.
+ `<aside>` 컨텐츠는 간접적으로 주위의 내용과 관련되어야함.
------------

### HTML <Figure> 및 <figcaption> Element
------------
+ `<figure>`등 그림, 도표, 사진, 코드 목록과 같은 태그를 저정 자체에 포함 된 내용, `<figcaption>` 태그는 `<figure>`요소에 대한 캡션을 정의함
+ `<figcation>` 요소는 `<figure>` 요소의 처음이나 마지막이 될수 있음.
+ `<img>` 요소는 실제 이미지/그림을 정의함.
------------