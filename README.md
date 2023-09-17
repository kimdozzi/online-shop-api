# jpa-shop
JPA를 활용한 쇼핑몰 웹 사이트 


[개선할 내용]
1. hierarchical-style layouts (계층 스타일 레이아웃) → 리팩토링 해보기
2. 회원 수정 기능 구현
3. Category - Book을 제외한 나머지 기능 구현
4. 엔티티는 핵심 비즈니스 로직만 가지고 있고, 화면을 위한 로직은 없어야 한다.(엔티티는 순수하게 유지를 해야한다.) => 화면은 폼객체나 DTO를 사용해볼 것