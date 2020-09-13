# Netflix Clone App For Study

Flutter기반 Netflix 디자인 및 일부 기능을 Clone한 App입니다.

## Goal

- Clone Coding을 통한 다양한 Widget Handling 경험
- StatefulWidget vs StatelessWidget 차이
- Widget Lifecycle 학습
- Firebase의 Firestore 연동

## Demo

[![IMAGE ALT TEXT](https://i9.ytimg.com/vi/Y_EC_MFUNQ4/mq3.jpg?sqp=CIzO-PoF&rs=AOn4CLBRaPU7BMPATipZewYLVl6n8Dw7Og)](https://youtu.be/Y_EC_MFUNQ4)

youtube link: https://youtu.be/Y_EC_MFUNQ4

## Issue

1. 내가 찜한 목록이 Detail화면에서 update 되는경우도 있고 아닌 경우도 있는 이슈
- StatefulWidget간 like 필드를 관리하고 view로 표현하기 때문에 다르게 보이는 것
- 해결: Provider 적용하여 해결해 볼 것

2. 비즈니스 로직과 View 로직이 분리되어있지 않음
- 테스트 코드 짜기 힘들고, 로직 파악의 어려움이 존재
- 해결: BLOC 패턴, Provider 패턴, Clean Architecture를 적용하여 테스트 코드를 작성할 수 있는 수준으로 코드 개선할 것

## Reference

인프런 무료 강좌를 통해 Clone App을 완성하였습니다.
