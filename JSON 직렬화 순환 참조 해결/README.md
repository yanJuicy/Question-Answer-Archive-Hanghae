양방향 연관관계를 가진 Entity를 클라이언트에 반환하려는 과정에서 StackOverFlow 를 만났다.
어떻게 처리할 수 있을까?
#### Comment Entity
![image](https://user-images.githubusercontent.com/91590391/207320009-73e56730-3749-466a-a4ec-0c6475a6fa4a.png)

#### Post Entity
![image](https://user-images.githubusercontent.com/91590391/207319931-b835b3e9-9f4d-4f7d-91f4-02d1edc5d76f.png)

#### 위와 같은 경우 순환 참조 예시
![image](https://user-images.githubusercontent.com/91590391/207319606-6a3e1b1e-0564-40af-88e4-a291a3598ca4.png)

Comment 엔티티를 JSON 형태로 직렬화하는 과정에서, Comment 엔티티가 참조하고 있는 Post 엔티티를 조회하게 된다.
Post 엔티티를 조회하는 과정에서, Post 엔티티가 참조하고 있는 Comment 엔티티를 조회한다.
이렇게 위 과정이 끊임없이 반복되며 두 Entity는 계속 서로를 참조하다 결국 StackOverflowError 를 발생시키게 된다.

양방향 관계에서 참조 순환 문제를 맞닥뜨리는 것은 자연스러운 일이다.
일반적으로는 해당 문제를 일으키는 객체의 Dto 생성하여 핸들링준다.

@JsonIgnore 어노테이션을 활용하는 방법도 있는데 그렇게 추천하지는 않는다.


https://data-make.tistory.com/727
