## 질문
Jackson이 json 데이터를 처리하는 줄 알았는데, ArgumentResolver에서 들어오는 요청을 처리한다는 글을 받는데 둘의 차이점이 무엇인가?

## 질문의도
어떤점이 궁금해서 질문을 했는지 작성해주세요.
Jackson 라이브러리에서 Json을 처리해서 사용자 요청은 Jackson이 받는 줄 알았다.
하지만 찾아보니 ArgumentResolver가 사용자 요청을 받아서 처리한다는 글을 발견했다.
`@RequestBody` 요청 같은 경우 json 데이터 요청인데 Jackson과 ArgumentResolver 중에 어디서 처리하는지 궁금했다.

## 답변
Argument Resolver에서 Jackson을 이용해 json 데이터의 object 변환을 한다. 이후 Controller로 요청을 보낸다.

## 참고자료
https://hou27.tistory.com/entry/RequestBody-ModelAttribute-%EA%B7%B8%EB%A6%AC%EA%B3%A0-Argument-Resolver

