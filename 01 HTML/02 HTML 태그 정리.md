# 02 HTML 태그 완성

**element : `<tag attribute>content</tag>`**

<br />
<br />

## 1. 태그는 Box 이거나 Item 이다.

![image](https://user-images.githubusercontent.com/100753621/163589272-f6921b0f-4eb1-42ee-a00f-beb7203855cb.png)

- Box : 눈에 보이지 않는 틀, 묶어서 스타일링할 때 사용
- Item : 사용자들에게 보여지는 것들

<br />
<br />

## 2. Item은 block과 inline 으로 구분된다.

![image](https://user-images.githubusercontent.com/100753621/163589299-86b790b7-941e-4eb4-8cb0-3663fac99500.png)

- block : 한 줄을 다 차지, `<div>`
- inline : 컨텐츠 내용만큼 차지, `<span>`

<br />
<br />

## 3. HTML 태그 예시

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

<br />

- block vs inline

  ```html
  <p>This is a sentence. That is...</p>
  <p>This is a sentence. <b>That</b> is...</p>
  <p>This is a sentence. <span>That</span> is...</p>
  <p>This is a sentence. <div>That</div> is...</p>
  ```

<br />

- a

  ```html
  <a href="https://google.com">Click</a>
  ```

<br />

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

<br />

- label and input

  ```html
  <label for="input_name">Name :</label><input id="input_name" type="text" />
  ```
