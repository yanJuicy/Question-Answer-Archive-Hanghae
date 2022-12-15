## 질문
Service 단에서 조회작업을 할 때  `@Transactional(readOnly=true)` 속성을 꼭 달아줘야 하나요? 


## 질문의도
Transacional 어노테이션을 통해 속도 향상이 거의 없다고 들었다. <br>
그리고 조회 작업은 DB에 데이터를 변경시키지 않는데 `@Transacionl` 어노테이션을 붙여주는 이유가 궁금했다. 


## 답변
`@Transactional(readOnly=true)` 어노테이션을 붙여줌으로써 해당 메소드가 DB에 데이터를 변경시키지 않는다고 명시할 수 있다. <br>
이는 실제로 협업할 때 다른 사람이 코드를 이해하기 편해진다는 장점을 가져다준다.

