# Pattern

### 개요

![(1)](/assets/flyweight/main.PNG)

- 데이터를 공유 사용하여 메모리를 절약할 수 있는 패턴

- 일반적으로 공통으로 사용되는 객체는 새로 생성해서 사용하지 않고 공유를 통해 효율적으로 자원을 활용한다.

- Factory를 이용해 이미 가지고 있는 객체에 대한 요청이 들어왔을 때는 관리하고 있던 객체를 던져주고, 가지고 있지 않은 것을 요청하면 새로 객체를 만들어 관리 리스트에 추가하고 던져준다.
<br/>

- **Parameter Factory와 비교**
  - 공통점
    - 요청이 들어오면 객체를 리턴해 준다
  - 차이점
    - Parameter Factory는 언제나 객체를 new 하여 리턴하는 반면에  
      Flyweight의 Factory는 검색을 통해 Reuse(재사용)를 한다는 점이다.
  - 이러한 특성 때문에 공유하는 값이 조금이라도 달라지면 사용이 불가능하다.

### 내용

![(1)](/assets/flyweight/1.jpg)
![(2)](/assets/flyweight/2.jpg)
![(3)](/assets/flyweight/3.jpg)
![(4)](/assets/flyweight/4.jpg)
![(5)](/assets/flyweight/5.jpg)
![(6)](/assets/flyweight/6.jpg)
![(7)](/assets/flyweight/7.jpg)
![(8)](/assets/flyweight/8.jpg)
![(9)](/assets/flyweight/9.jpg)
![(10)](/assets/flyweight/10.jpg)
![(11)](/assets/flyweight/11.jpg)
