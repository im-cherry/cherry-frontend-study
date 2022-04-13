# 2. HTML 태그 완성

> element : `<tag attribute>content</tag>`

### 1) 태그는 Box 이거나 Item 이다.

- Box
  - header
  - footer
  - nav
  - aside
  - main
  - section
  - article
  - div
  - span
  - form
- Item
  - a
  - button
  - input
  - label
  - img
  - video
  - audio
  - map
  - canvas
  - table

### 2) Item은 block 과 inline 으로 구분된다.

- block
  - 한 줄을 다 차지
- inline
  - 컨텐츠 내용만큼 차지

### 3) HTML 태그 예시

- Box vs Item

  ```html
  <!-- Box -->
  <header></header>
  <footer></footer>
  <section></section>
  <div></div>

  <!-- Item -->
  <h1>Header 1</h1>
  <button>Button</button>
  ```

  ![image](https://user-images.githubusercontent.com/100753621/162713570-91da6c5e-c115-467f-913d-75568d9cc179.png)

- block vs inline

  ```html
  <p>This is a sentence. That is...</p>
  <p>This is a sentence. <b>That</b> is...</p>
  <p>This is a sentence. <span>That</span> is...</p>
  <p>This is a sentence. <div>That</div> is...</p>
  ```

  ![image](https://user-images.githubusercontent.com/100753621/162713149-affb1944-af6a-4496-b2a5-d0e2a600fe22.png)

- a

  ```html
  <a href="https://google.com">Click</a>
  ```

  ![image](https://user-images.githubusercontent.com/100753621/162713253-de937749-dcdf-4d5d-be20-f213b43ac69b.png)

- List: ol, ul, li

  ```html
  <ol>
    <li>1</li>
    <li>2</li>
    <li>3</li>
  </ol>

  <ul>
    <li>1</li>
    <li>2</li>
    <li>3</li>
  </ul>
  ```

  ![image](https://user-images.githubusercontent.com/100753621/162713331-17bce149-da4b-44bf-a583-a68d3e32466c.png)

- label and input

  ```html
  <label for="input_name">Name : </label><input id="input_name" type="text" />
  ```

  ![image](https://user-images.githubusercontent.com/100753621/162713401-8b93506c-329d-4fd0-b07c-6f12344fb6e4.png)
