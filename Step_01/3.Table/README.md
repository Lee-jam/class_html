# 210923 START HTML table

### Table intro
```
+ table 요소는 데이터를 행과 열로 정렬할 수 있음.
+ <td></td> 태그는 테이블 데이터를 나타냄 - table data
+ <tr></tr> 태그는 테이블의 행을 나타냄 - table row
+ <th></th> 태그는 테이블 헤더를 나타냄 - table head
```
### Table Borders
```
+ table, th 및 td 요소에 CSS의 border 속성을 추가함.
  + ex) table, th, td { border: 1px solid black; }
+ 이중 테두리가 생기는 것을 없애기 위해서 CSS의 border-collagpse : collapse 로 설정함.
+ 원형 테이블 테두리는 border-radius를 사용함. 값에 크기에 따라 얼마나 더 둥근지가 정해짐.
```
### Table Sizes
```
+ style 속성과 width 와 height을 함께 사용하여 행 또는 열의 크기를 지정함.
+ style ="width:00%" or style ="height:00%" 을 table 또는 th, td, tr 에 추가하여 크기를 조절할 수 있음.
```
### Table Header
```
+ 테이블 헤더는 th요소로 정의되며 각 th요소는 테이블 셀을 나타냄
+ 테이블 형태에 따라 가로 테이블, 세로 테이블 등 형태에 맞게 사용할 수 있음.
+ 테이블을 정렬할 때는 text-align 속성을 사용함.
+ 여러개의 열을 사용하는 헤더를 적용하려면 colspan 속성을 사용함.
```
### Table Padding and Spacing
```
+ 셀 패딩이란 셀 가장자리와 셀 내용 사이의 공간을 말함. 기본적으로 패딩은 0으로 설정되어있음.
+ 표 셀에 패딩을 추가하려면 CSS에 padding속성을 사용하면 됨.
+ 위 아래 좌 우에 공백을 추가하려면 top, bottom, left, right 속성을 추가하면 됨.
+ 각 셀 사이의 간격은 기본 설정 값은 2임. 변경하려면 border-space 속성을 사용하면 됨.
```
### Table colspan and rowspan
```
+ 여러 행 혹은 여러 열을 걸쳐 있는 셀을 있는 경우 사용됨.
+ 여러 열에 걸쳐있는 셀을 만드려면 colspan을 사용함.
+ 여러 행에 걸쳐있는 셀을 만드려면 rowspan을 사용함.
```
### Table styling
```
+ 행에 배경색을 추가하면 Table Zebra Stripes(얼룩말 줄무늬) 효과를 얻을 수 있음.
+ tr:nth-child(even)을 사용하면 전체 테이블의 2,4,6번째의 짝수번 행에 색을 추가함. even : 짝수를 의미함.
+ 1,3,5번째에 색을 추가하려면 (even) 대신 (odd)를 사용하면 됨. // odd : 홀수를 의미함.
+ 세로 얼룩말이 되려면 행 대신 열에 색을 입히면 됨. td:nth-child(even) or td:nth-child(odd)
+ ex) th:nth-child(even),td:nth-child(even) <== 예시처럼  세로 및 가로 줄무늬 결합도 가능하며 rgba() 색상을 통해 투명도도 설정가능함.
+ 테이블의 첫번째 두열에 스타일을 지정하려면 <colgroup> 및 <col>요소를 사용함. ex) <col span="2" style="background-color: #D6EEEE">
+ 테이블에서 첫번째 세 열 중 가장 앞 열을 스타일 지정에서 제외하려면 <colgroup> 및 <col>요소를 사용하여 스타일 없음을 선언하여야함. ex) <col span="3">
+ visibility: collapse속성을 사용하여 열을 숨길 수 있음.
```
