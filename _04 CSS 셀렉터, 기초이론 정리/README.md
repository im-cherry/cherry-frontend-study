# 4. CSS 셀렉터, 기초 이론 정리

### 1) CSS

- Cascading Style Sheet

### 2) 선택자

- Universal : `*`
- type : `tag`
- ID : `#id`
- Class : `.class`
- State : `:`
- Attribute : `[]`

### 3) 선택자 예시

```html
<ol>
  <li id="special">First</li>
  <li>Second</li>
</ol>

<button>Button</button>

<div class="red"></div>

<a href="naver.com">Naver</a>
<a href="google.com">Google</a>
<a>Empty</a>
```

```css
* {
  color: green;
}

li {
  color: blue;
}

#special {
  color: pink;
}

.red {
  width: 100px;
  height: 100px;
  background: yellow;
}

button:hover {
  color: red;
  background: beige;
}

a[href] {
  color: purple;
}

a[href="naver.com"] {
  color: coral;
}

a:not([href]) {
  color: black;
}
```

![image](https://user-images.githubusercontent.com/100753621/162782217-b6efbd0e-2a50-470a-add0-37454f548d6a.png)

### 4) 참고하면 좋은 사이트

- [셀렉터 정의](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [셀렉터 예시](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [css 속성](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference)
- [셀렉터 게임 공부](https://flukeout.github.io/)
