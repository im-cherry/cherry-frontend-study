# 01 HTML 구조 분석

## 1. HTML 구조

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>JS Bin</title>
  </head>
  <body></body>
</html>
```

- `<!DOCTYPE html>` : 현재 문서는 html 문서임을 명시
- `<html>` : html 문서의 루트 요소
- `<head>` : 사용자에게 보여지는 정보가 아닌 메타 데이터 정의
- `<body>` : 사용자에게 보여지는 최상위 요소

<br/>
<br/>

## 2. 웹 사이트 구조

- header : `<header>`
- navigation bar : `<nav>`
- main content : `<main>` ⊃ `<section>`, `<article>` - 재사용 가능
- sidebar : `<aside>` - 주로 `<main>` 안에 위치
- footer : `<footer>`
- [참고 링크](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

<br/>
<br/>

## 3. 참고하기 좋은 사이트

- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) : 웹 표준과 모질라 프로젝트에 대한 개발 문서들이 담긴 모질라의 공식 웹사이트
- [Validator](https://validator.w3.org/) : W3C 웹표준 유효성 검사 도구
- [JSbin](https://jsbin.com/?html,output) : 자바스크립트, html, css 코드를 작성하고 실행 및 테스트를 수행할 수 있는 웹서비스
