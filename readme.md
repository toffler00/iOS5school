# 객체지향형 프로그래밍 특징


**1. 추상화**  
공통의 속성이나 기능을 묶어 이름을 붙이는 것으로객체 지향적 관점에서 클래스를 정의한다.  따라서 추상화라는 개념은 '각 객체에서 공통된 속성과 행위를 추출하는 것'을 의미한다. 예를 들어 수학, 과학, 사회 가 있다고 하면  이것 들을 객체로 보고 공통된 속성으로 과목이라는 클래스로 정의한다. 추상화는 객체들간의 핵심적인 특징들을 중심으로 묶어 다른 객체들과 구분을 짓는다. 하지만 추상화는 문제 영역과 관점에 의해 달라 질 수 있어서 여러 추상화 모델이 생길 수 있다.

**2. 캡슐화**  
실제로 구현되는 부분을 외부에 드러나지 않도록 캡슐로 감싸 이용방법만을 알려주는것으로 데이터 구조와 데이터를 다루는 방법들을 결합 시켜 묶는 것을 캡슐화라고 한다. 여기서 캡슐화를 할 때에는 객체가 맡은 역할을 수행하기 위한 것이어야 한다. 객체안에 다른 역할을 하는 변수나 함수를 피해야한다.

**3. 은닉화**
은닉이란 내부 데이터, 내부 연산을 외부에서 접근하지 못하도록 은닉(hiding) 혹은 격리(isolation)시키는 것이라 한다. 은닉화는 변수, 메소드 등의 중요사항이 밖으로 드러나지 않게 하여 사용자가 보거나 수정할 수 없게 한다. 사용자의 입장에서는 사용하는데 불필요한 정보를 최소화하여 사용의 편의를 높일 수 있는 중요한 부분이다.

**4. 상속성**
상위 클래스의 특징을 하위 클래스가 물려받는 것. 객체지향의 장점으로 상속이란 개념이 절차지향과 확연한 차이점이라 할 수 있다. 상속성으로 인한 장점은 상위 클래스의 특징을 나타내는 코드의 재사용으로 인해 코드사용이 줄어든다. 또한 상위 클래스가 갖고 있는 메소드를 물려받아 하위 클래스의 특징에 맞게 데이터와 메소드를 추가함으로써 범용성있게 사용할 수 있다.

**5. 다형성**  
상위 클래스에서 물려받은 함수를 하위 클래스 내에서 오버라이딩 되어 사용되는 것. 여러 웹사전에서의 다형성의 일반적인 의미는 '다양한 형태로 나타날 수 있는 능력'이라고 한다. 또 다른 의미로는    '여러 클래스들이 동일한 이름의 오퍼레이션을 서비스하도록 하는 것'이라고 한다. 이러한 다형성은 실제의 코드에서는 '하나의 클래스 내부에 같은 이름의 오퍼레이션을 여럿 정의하거나, 상위 클래스의 오퍼레이션을 하위 클래스에서 다시 정의함'으로써 구현한다.




