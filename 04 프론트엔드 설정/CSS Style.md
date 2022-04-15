# CSS Style

## 1. CSS-IN-CSS

### 1-1) CSS-IN-CSS Ranking

- Satisfaction
  ![image](https://user-images.githubusercontent.com/100753621/163493078-7685bec1-1fe0-434e-b4aa-e7c5c16c16a7.png)

- Usage
  ![image](https://user-images.githubusercontent.com/100753621/163493120-bca21bf4-d7e4-4fa9-993e-ddca6d54f810.png)

### 1-2) CSS Preprocessor

CSS 전처리기

- 전처리기의 자신만의 특별한 문법을 가지고 CSS를 생성하도록 하는 프로그램
- 변수, 함수, 상속 등 일반적인 프로그램 개념을 사용하여 보완
- Sass, Less, PostCSS, Stylus

_전처리기 : 소스 코드를 컴파일 하기 직전에 처리하는 컴파일러의 한 부분_

### 1-3) Sass

- 전처리기
- Sass로 작성된 파일은 컴파일을 통해 CSS 문법으로 변환됨
- 예시

  ```Scss
  $primary-color: #333;

  body {
      color: $primary-color;
  }

  nav {
      ul {
          margin: 0;
          padding: 0;
      }

      a {
          display: block;
          padding: 6px 12px;
      }
  }

  @mixin theme($theme: DarkGray) {
      background: $theme;
      box-shadow: 0 0 1px rgba($theme, .25);
      color: #fff;
  }

  .info {
      @include theme;
  }

  .alert {
      @include theme($theme: DarkRed);
  }

  .success {
      @include theme($theme: DarkGreen);
  }
  ```

### 1-4) PostCSS

- 후처리기
- JS 플러그인을 사용하여 CSS를 변환하는 도구
- CSS의 Babel
- [플러그인](https://www.postcss.parts/)
  - autoprefixer : -webkit- 등의 prefix를 자동으로 넣어준다
  - stylelint : stylelint 규칙에 맞지 않는 stylesheet의 오류, 버그 등을 알려준다.
  - lost : grid system을 쉽게 작성할 수 있게 한다.
  - cssnano : 배포시, CSS 크기를 최적화한다.
  - colorguard : 미리 설정한 color set을 유지할 수 있게 돕는다.
  - cssfmt : stylelint 규칙에 맞게 포맷을 변경한다.
  - preset-env : 최신 CSS 문법을 설정한 브라우저가 이해할 수 있는 버전으로 변환한다.

**Sass와 PostCSS는 실행 시점이나 방법이 다르기 때문에 한 프로젝트에 둘 다 적용할 수 있습니다.**
**동시에 사용하는 경우, Scss로 작성된 파일이 컴파일을 통해 CSS로 변환되고, 변환된 CSS는 다시 PostCSS 플러그인(패키지)에 의해 최종 변환됩니다.**

## 2. CSS-IN-JS

### 2-1) CSS-IN-JS 란?

- 자바스크립트를 사용하여 구성 요소의 스타일을 지정한는 스타일 지정 기술
- 자바스크립트가 구문 분석되면 CSS가 생성되어 DOM에 첨부됨.
- [vanilla-extract](https://vanilla-extract.style/)
- CSS Modules
- [Windi CSS](https://windicss.org/)
- [Styled Components](https://styled-components.com/)
- [Styled JSX](https://nextjs.org/blog/styling-next-with-styled-jsx)

### 2-2) CSS-IN-JS Ranking

- Satisfaction
  ![image](https://user-images.githubusercontent.com/100753621/163512352-952781ca-cb61-44a3-ac41-a68ef340a8c4.png)

- Usage
  ![image](https://user-images.githubusercontent.com/100753621/163512395-1b256428-4ce1-4f4b-80cf-bb932957acac.png)

## 3. CSS Framework

### 3-1) CSS Framework 란?

- CSS 언어를 사용하여 보다 쉽고 표준을 준수하는 웹 디자인을 가능하게 하는 라이브러리
- [Bootstrap](https://getbootstrap.com/)
- [Materialize CSS](https://materializecss.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PureCSS](https://purecss.io/)
- [Ant Design](https://ant.design/)

### 3-2) CSS Framework Ranking

- Satisfaction
  ![image](https://user-images.githubusercontent.com/100753621/163497413-90687044-680f-417a-9f78-3e970e8d2934.png)
- Usage
  ![image](https://user-images.githubusercontent.com/100753621/163497452-5eadd7b9-f76a-4292-929b-de30a8077e8d.png)

## 4. IT 기업별 CSS Style

| 기업       | CSS-IN-CSS | CSS-IN-JS | CSS Framework |
| :--------- | :--------: | :-------: | :-----------: |
| 네이버     |            |           |               |
| 카카오     |            |           |               |
| 라인       |            |           |               |
| 쿠팡       |            |           |               |
| 배달의민족 |            |           |               |
| 당근마켓   |            |           |               |
| 토스       |            |           |               |
| 직방       |            |           |               |
| 야놀자     |            |           |               |

## Reference

- https://still-growing.tistory.com/entry/PostCSS-vs-Scss
- https://2021.stateofcss.com/en-US/
- https://s-core.co.kr/insight/view/웹-컴포넌트-스타일링-관리-css-in-js-vs-css-in-css/
