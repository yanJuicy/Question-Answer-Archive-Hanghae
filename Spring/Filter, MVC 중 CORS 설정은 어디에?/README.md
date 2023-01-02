## 질문
Spring Security 설정에서 CORS 설정을 하면 Spring MVC 설정 파일에서 CORS 설정을 따로 안해줘도 되나요?

## 질문의도
Spring Secuirty가 MVC 전에 실행되니까 Secuirty에서 CORS 관련해서 미리 설정하면 MVC는 할 필요가 없나요?
아니면 둘 다 설정해야 하나요?

## 답변
보통 Filter에서 다 한다.
Filter에서 검사하지 않는 url 중에 CORS가 발생하면 MVC에서 설정해준다.

