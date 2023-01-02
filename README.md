# Question-Answer-Archive-Hanghae
항해 질의응답 저장소

## What is this?
- 항해중 기술 매니저님과 질의응답한 내용을 모아두는 저장소입니다.
- Issues에 있는 [질의 응답 템플릿](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/issues/2)을 사용해서 내용을 채운 후 PR을 보내주시기 바랍니다.
- 레포지토리에 관련해서 질문은 Issue로 남겨주시길 바랍니다.

## Contributors
<a href="https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yanJuicy/Question-Answer-Archive-Hanghae" />
</a>


## How to Contriubute
1. 내용을 작성하신 뒤 다음과 같이 파일을 만들어 PR을 보내주세요.
    - 기술스택(Spring, Node, React, Java, DB, Web, ...)/[질문 제목]/README.md
    - 기술스택은 영어로 작성해주시고 첫 글자는 대문자로 작성해주세요.
    - `ex) Spring/SpringBoot와 Spring 차이/README.md`
    - 커밋 메시지 작성 가이드는 다음과 같습니다.
      - 날짜(년-월-일) [언어] 질문 제목 [create/update]
      - `ex) 2022-12-12 [Spring] 인증, 인가의 차이가 무엇인가? [create]`
      - 같은 파일을 변경할 때는 커밋 메시지 끝 부분을 `create -> update`로 바꿔주시기 바랍니다.

2. README.md 파일에 index를 추가한 후 PR을 보내주세요.
    - README 파일에 index 추가 커밋 메시지는 다음과 같이 작성해주세요.
    - 날짜(년-월-일) [기술스택] 질문 제목 [index]
    - `ex) 2022-12-12 [Spring] 인증, 인가의 차이가 무엇인가? [index]`


## Index
- Spring
  - [Jackson, ArgumentResolver의 차이](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/Jackson%EA%B3%BC%20ArgumentReolver%EC%9D%98%20%EC%B0%A8%EC%9D%B4)
  - [응답 Dto에 Object와 Generice 중 어떤게 좋은가](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/%EC%9D%91%EB%8B%B5%20Dto%EC%97%90%20Object%EC%99%80%20Generice%20%EC%A4%91%20%EC%96%B4%EB%96%A4%EA%B2%8C%20%EC%A2%8B%EC%9D%80%EA%B0%80)
  - [JSON 직렬화 순환참조 해결](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/JSON%20%EC%A7%81%EB%A0%AC%ED%99%94%20%EC%B0%B8%EC%A1%B0%EC%88%9C%ED%99%98%20%ED%95%B4%EA%B2%B0)
  - [프론트랑 같이 협업할 때 SSR을 같이 사용하는 경우가 있나요?](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/%ED%94%84%EB%A1%A0%ED%8A%B8%EB%9E%91%20%ED%98%91%EC%97%85%20%ED%95%A0%EB%95%8C%EB%8F%84%20SSR%EC%9D%84%20%EC%93%B0%EB%8A%94%EA%B0%80%3F)
  - [`@Transactional(readOnly=true)` 속성을 꼭 사용해야하나](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/Transactional(readOnly%3Dtrue)%20%EC%86%8D%EC%84%B1%EC%9D%84%20%EA%BC%AD%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%82%98)
  - [Custom 익셉션을 최대한 나누는게 좋은가?](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/Custom%20%EC%9D%B5%EC%85%89%EC%85%98%EC%9D%84%20%EC%B5%9C%EB%8C%80%ED%95%9C%20%EB%82%98%EB%88%84%EB%8A%94%EA%B2%8C%20%EC%A2%8B%EC%9D%80%EA%B0%80%3F)
  - [Filter, MVC 중 CORS 설정은 어디에?](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Spring/Filter%2C%20MVC%20%EC%A4%91%20CORS%20%EC%84%A4%EC%A0%95%EC%9D%80%20%EC%96%B4%EB%94%94%EC%97%90%3F)


- Java
  - [Object 클래스를 extends 하는 시점](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/blob/main/Java/Object%20%ED%81%B4%EB%9E%98%EC%8A%A4%20extends%20%EC%8B%9C%EC%A0%90/README.md)
  - [Junit 공부법](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/Java/Junit%20%EA%B3%B5%EB%B6%80%EB%B2%95)
  
  
- DB
  - [Repeatable Read에서 Phantom Read를 해결하는 방법](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/DB/Repeatable%20Read%EC%97%90%EC%84%9C%20Phantom%20Read%EB%A5%BC%20%ED%95%B4%EA%B2%B0%ED%95%98%EB%8A%94%20%EB%B0%A9%EB%B2%95)
  - [CAP 이론의 3가지 특성](https://github.com/yanJuicy/Question-Answer-Archive-Hanghae/tree/main/DB/CAP%20%EC%9D%B4%EB%A1%A0%EC%9D%98%203%EA%B0%80%EC%A7%80%20%ED%8A%B9%EC%84%B1)
