## 질문 
다음과 같이 응답 dto를 만들 때 object를 통해 api 마다 다른 ResponseDto를 받아서 쓰려고 했다.
Generice으로도 이 방법이 가능한 것 같은데 objcet, generice 중에 어떤게 좋은가?

```java
@Getter
public class ResponseDto  {

		private String msg;
    private int statusCode;
    private Object data;

    public ResponseDto(ResponseMessage responseMessage, Object data) {
        this.msg = responseMessage.getMsg();
        this.statusCode = responseMessage.getStatus();
				this.data = data;
    }

}
```

## 답변
Generice을 권장하고 있다.
다음과 같이 쓰면 좋을 것 같다.

```java
@Getter
public class GenericResponseDto<T> {

    private String msg;
    private int statusCode;
	  private T data;

    public GenericResponseDto(ResponseMessage responseMessage, T data) {
        this.msg = responseMessage.getMsg();
        this.statusCode = responseMessage.getStatus();
      this.data = data;
    }

}

```
