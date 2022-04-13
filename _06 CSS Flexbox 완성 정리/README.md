# 6. CSS Flexbox 완전 정리

![image](https://user-images.githubusercontent.com/100753621/162796906-c9b0e578-0b4b-4bc6-b8d6-135edf6923b0.png)
![image](https://user-images.githubusercontent.com/100753621/162795084-156cf3dd-4bfc-4025-94ba-7ee373b7203d.png)

### 1) container에 적용되는 속성값

- display
- flex-direction : flex-direction: row | row-reverse | column | column-reverse
  ![image](https://user-images.githubusercontent.com/100753621/162796990-b90647b8-9158-480e-b3fe-4596fa32c701.png)
- flex-wrap : nowrap | wrap | wrap-reverse
  ![image](https://user-images.githubusercontent.com/100753621/162797057-4ca80b03-9a4a-4186-920c-521a5e7f0884.png)
- justify-content(main axis) : flex-start | flex-end | center | space-between | space-around | space-evenly
  ![image](https://user-images.githubusercontent.com/100753621/162797220-99fa564e-0348-46b5-83e6-82eed6145efe.png)
- align-items(cross axis) : stretch | flex-start | flex-end | center | baseline
  ![image](https://user-images.githubusercontent.com/100753621/162795526-adcb0bea-e0c8-4b56-ace5-a47e944ad58f.png)
- align-content : flex-start | flex-end | center | space-between | space-around | space-evenly | stretch
  ![image](https://user-images.githubusercontent.com/100753621/162795643-fef1d114-dab8-4dd6-8a28-7e9d074c7903.png)

### 2) item에 적용되는 속성값

- order
  ![image](https://user-images.githubusercontent.com/100753621/162795912-926c44e6-8476-49ce-9210-801a9a939bbc.png)
- flex-grow
  ![image](https://user-images.githubusercontent.com/100753621/162797382-35da7dbb-b498-4bff-8f72-cb0e71a2b850.png)
- flex-shrink
- flex-basis
- align-self : auto | flex-start | flex-end | center | baseline | stretch
  ![image](https://user-images.githubusercontent.com/100753621/162796126-ee8cdc3e-1e9c-493b-8f72-3ada51684e3f.png)

### 3) main axis vs cross axis

- flex-direction : row
  - main axis : row
  - cross axis : column
- flex-direction : column
  - main axis : column
  - cross axis : row

### 5) 참고하면 좋은 사이트

- [flex 정리](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

- [flex 연습하기](https://flexboxfroggy.com/#ko)
  https://hangem-study.readthedocs.io/en/latest/css/flex/
