```css
.container {
  place-items: <align-items> <justify-items>;
}
```

align-items와 justify-items의 단축 속성입니다.
하나의 값만 입력하면 두 속성에 모두 적용됩니다.

```css
.container {
  place-items: start stretch;
}
/*위와 같은 속성*/
.container {
  align-items: start;
  justify-items: stretch;
}


.container {
  place-items: center;
}
/*위와 같은 속성*/
.container {
  align-items: center;
  justify-items: center;
}
```

