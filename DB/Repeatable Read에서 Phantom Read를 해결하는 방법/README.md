## 질문
트랜잭션 격리수준 Repeatable Read 이하에서 발생할 수 있는 Phantom Read를 해결하는 방법은 무엇인가?


## 질문의도
트랜잭션 격리 수준을 Serializable로 바꾸는 것 말고도 lock 같은 방법으로 해결할 수 있는 방법이 있는지 궁금했다.


## 답변
lock으로는 해결할 수 없고 격리 수준을 Serializable로 바꾸서 해결한다.


## 참고자료

https://joont92.github.io/db/%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98-%EA%B2%A9%EB%A6%AC-%EC%88%98%EC%A4%80-isolation-level/
