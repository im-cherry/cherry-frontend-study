# 7. 웹 개발을 위한 유용한 팁

### 1) vscode extension

- Material Theme
- Material Icon Theme
- Prettier - Code Formatter
- Bracket Pair Colorizer
- indent-rainbow
- CSS Peek
- HTML CSS Support
- Live Server
- Markdown Preview
- HTML to CSS autocompletion

### 2) Emmet

- html 양식 작성 : `!`

  ```html
  <!-- ! -->
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Document</title>
    </head>
    <body></body>
  </html>
  ```

- div 태그 작성 : `.class` `#id`

  ```html
  <!-- .hello -->
  <div class="hello"></div>

  <!-- #bye -->
  <div id="bye"></div>
  ```

- 부모, 자식, 형제 노드 : `>` `+` `*`

  ```html
  <!-- div>ul>li -->
  <div>
    <ul>
      <li></li>
    </ul>
  </div>

  <!-- div>ul+ol -->
  <div>
    <ul></ul>
    <ol></ol>
  </div>

  <!-- ul>li*3 -->
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
  ```

- 그룹화 하기 : `()`

  ```html
  <!-- div>(header>ul>li*2>a)+footer>p-->
  <header>
    <ul>
      <li><a href=""></a></li>
      <li><a href=""></a></li>
    </ul>
  </header>
  <footer>
    <p></p>
  </footer>
  ```

- 텍스트 입력하기 : `{}`

  ```html
  <!-- p{hello}-->
  <p>hello</p>
  ```

- 자동 번호 넣기 : `$`

  ```html
  <!-- p.paragraph${}*3 -->
  <p class="paragraph1"></p>
  <p class="paragraph2"></p>
  <p class="paragraph3"></p>

  <!-- p.paragraph${item $}*3 -->
  <p class="paragraph1">item 1</p>
  <p class="paragraph2">item 2</p>
  <p class="paragraph3">item 3</p>
  ```

- 더미용 텍스트 생성 : `lorem`

  ```html
  <!-- p>lorem -->
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto odio, autem
    at repudiandae sapiente soluta quos, voluptates obcaecati facilis distinctio
    ad nostrum tempore, laudantium reprehenderit. Atque quos saepe error
    facilis?
  </p>

  <!-- p>lorem4 -->
  <p>Lorem ipsum dolor sit.</p>
  ```

### 3) 디자인 사이트

- [pinterest](https://www.pinterest.se/ideas/)
- [dribble](https://dribbble.com/)
- [color tool](https://material.io/resources/color/#!/?view.left=0&view.right=0)
- [my color](https://mycolor.space/)
- [gradient](https://cssgradient.io/)
- [shape divider](https://www.shapedivider.app/)
- [design svg](https://haikei.app/)
- [color background](https://coolbackgrounds.io/)
