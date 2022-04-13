# 5. CSS 레이아웃 정리 display, position 완성

### 1) display

```html
<!-- Block level -->
<div class="div1">1</div>
<div class="div1">2</div>

<!-- Block level -->
<div class="div2">1</div>
<div class="div2">2</div>

<!-- Inline level -->
<span>1</span>
<span>2</span>
```

```css
div,
span {
  width: 80px;
  height: 80px;
  margin-bottom: 20px;
}

.div1 {
  background: red;
  display: inline;
}

.div2 {
  background: yellow;
  display: inline-block;
}

span {
  background: blue;
  display: block;
}
```

![image](https://user-images.githubusercontent.com/100753621/162783798-9d078243-9aad-4b0c-91c6-d9809b6064a0.png)

### 2) position

```html
<div class="container">
  <div></div>
  <div></div>
  <div class="box">position</div>
  <div></div>
</div>
```

```css
div {
  width: 80px;
  height: 80px;
  margin-bottom: 20px;
  background: blue;
}

.container {
  left: 80px;
  position: relative;
}

.box {
  background: red;
  left: 80px;
  position: relative | absolute | fixed | sticky;
}
```

- relative : 원래 있어야 하는 자리에서 상대적으로 이동하여 위치

- absolute : 가까운 위치에 있는 부모에서 위치

- fixed : 최상위 브라우저를 기준으로 위치

- sticky : 원래 있어 하는 자리에 위치하면서 스크롤릴 되어도 그대로 위치
