## Responsive CSS Units

### CSS 문법

selector: 어떤 요소를 선택할지 <br/>
property: 어떤 속성을 꾸밀지 <br/>
values: 그에 해당하는 값 <br/>

```css
.box {
  width: 200px; 
  height: 150px;
}
```

### 절대값, 상대값

#### 절대값
- `cm, mm, Q, in, pc, pt, px`, 여기서는 `px` 이 가장 많이 쓰임.
`px`: 모니터 화면에서 나타낼 수 있는 가장 단위 (컨테이너 사이즈가 변경되어도 고정값을 가져용.)

#### 상대값
- `vw, vh, %, em, rem` 애네가 제일 많이 쓰이니까 애네만 일단 익히자...

`em`: 현재 지정된 폰트 사이즈 단위. 부모 요소의 상대적으로 크기가 결정됨. (`1em == 16px`)

`rem`: root 에 지정된 폰트 사이즈에 따라 크기가 결정됩니다.

`percent`: 부모 요소의 상대적으로 크기가 결정됩니다.

`vw`: 브라우저의 너비에 따라 달라짐.