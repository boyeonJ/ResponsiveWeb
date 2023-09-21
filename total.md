tag
단축키
a - href, target
h
img - src alt height title
p

선택자 종류 #id, .class a b a + b a~ b a > b

semengtic tag
div span
ul ol dl
//list-style-type: none; (ul)
//display: inline-block(li)
form
input

가상클래스
문단 정렬
font
google font
material icon
unit

backgroud
display
border
border-radius
box-sizing : border-box, content-box
//테두리 기준 안쪽 패딩, 바깥쪽 마진=>box-model(위의 border-box는 padding 관련된 부분)

---

lnline-block
flex : 자식들의 정렬에 많이 사용
inline-flex : 너비값 가짐(default 너비 만큼)

---

가운데 정렬(가로, 세로)
line-height 속성은 텍스트의 행간을 설정하는데 사용되며, text-align 속성은 텍스트의 수평 정렬을 설정하는데 사용됩니다. 두 속성은 서로 다른 목적을 가지고 있으며, 블록과 인라인 요소 모두에 적용할 수 있습니다.

---

a > display block, padding(간격)
li > display inline-block

---

이미지 배경
background-image: url(../img//visu.jpg);
background-size: cover;
background-position: center;

---

flex

flex-direction : row, row-reverse, column, column-reverse

justify-content(메인축): flext-start, flex-end, center, space-between, space-evenly, spave-arount

*justify-self: start, center, end, stretch

align-itmes(교차축): flex-start, flex-end, stretch, center

*align-self: start, end, center, stretch
