# iOSInterviewquestions
iOS개발자들에게 필요한 자료들을 정리하고 있는 중입니다.

면접때 받은 질문이나 공부한내용들

수정해야할 내용이나 추가해야할 내용은 언제든지 PR날려주세요!

모두의 힘을 모아봅시다 👯‍♀️👯‍♂️
감사합니다:)

# Required
아래 내용들은 최대한 많이 공부해놓는것이 좋습니다 📝

## iOS
- Bounds 와 Frame 의 차이점을 설명하시오.

  > **⚠️ Bounds는 뷰자기 자신의 좌표계이다. 이 좌표를 수정하게 되면 자신 아래에 있는 서브뷰들이 영향을 받는다.**
  >
  > **⚠️ Frame은 자신의 슈퍼뷰에서 자신의 좌표를 나타내는 좌표계이다.**

- 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명하시오.

- 앱이 foreground에 있을 때와 background에 있을 때 어떤 제약사항이 있고, 상태 변화에 따라 다른 동작을 처리하기 위한 델리게이트 메서드들을 설명하시오.

- scene delegate에 대해 설명하시오.

- 앱이 In-Active 상태가 되는 시나리오를 설명하시오.

- NSOperationQueue 와 GCD Queue 의 차이점을 설명하시오.

- GCD API 동작 방식과 필요성에 대해 설명하시오.

- 자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오.

- iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가?

- Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오.

- Delegate란 무언인가 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오.

- NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오.

- UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가?

- TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오.

- 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오.

- App Bundle의 구조와 역할에 대해 설명하시오.

- View 객체에 대해 설명하시오.

  > **⚠️ 앱에서 처리한 모델, 데이터를 화면의 컨텐츠로 표현하는 객체**
  >
  > **⚠️ 사용자와의 상호작용하는 객체**

- UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오.

- UIWindow 객체의 역할은 무엇인가?

- UINavigationController 의 역할이 무엇인지 설명하시오.

- 모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가?

- 앱이 시작할 때 main.c 에 있는 UIApplicationMain 함수에 의해서 생성되는 객체는 무엇인가?

- UIApplication 객체의 컨트롤러 역할은 어디에 구현해야 하는가?

- 앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별학 객체를 무엇이라고 하는가?

- 앱 화면의 콘텐츠를 표시하는 로직과 관리를 담당하는 객체를 무엇이라고 하는가?

- Swift의 클로저와 Objective-C의 블록은 어떤 차이가 있는가?

- App의 Not running, Inactive, Active, Background, Suspended에 대해 설명하시오.

- App thinning에 대해서 설명하시오.

- Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오.

## Autolayout
- 오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지)
- hugging, resistance에 대해서 설명하시오.
- Intrinsic Size에 대해서 설명하시오.
- 스토리보드를 이용했을때의 장단점을 설명하시오.
- Safearea에 대해서 설명하시오.
- Left Constraint 와 Leading Constraint 의 차이점을 설명하시오.

## Swift
- Optional 이란 무엇인지 설명하시오.

  > **⚠️  데이터의 부재의 가능성을 표현한다**
  > 
  > **⚠️  스위프트에서는 옵셔널이 존재하기에 옵셔널이 아닌 타입은 데이터가 존재할 것을 더 보장할 수 있다.**


- Fast Enumration 이란 무엇인지 설명하시오. 


- Struct 가 무엇이고 어떻게 사용하는지 설명하시오.


- instance 메서드와 class 메서드의 차이점을 설명하시오.

  > **⚠️ 인스턴스 메소드는 class/struct가 초기화되어 해당 인스턴스를 통해 접근 가능한 메소드이다.**
  > - *그러므로 해당 메소드에서 상태를 변경하면 해당 인스턴스만 상태가 변경된다.*
  >
  > **⚠️ Class 메소드의 경우 타입에 의존하므로 타입을 명시함으로써 메소드에 접근가능하다.**
  >
  > - *그러므로 해당 메소드에서 상태를 변경하게되면 해당 타입 그 자체의 상태가 변경된다.*

- Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오.

- Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오.

- KVO 동작 방식에 대해 설명하시오.

- Delegates와 Notification 방식의 차이점에 대해 설명하시오.

- 멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오.

- MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오.

- 프로토콜이란 무엇인지 설명하시오.

  > **⚠️  프로토콜은 객체간의 소통에서 필요한 관련있는 기능들의 명세의 집합이다.**
  >
  > **⚠️  프로토콜을 준수하는 순간 해당 기능들의 구현을 강제하기한다.**
  >
  > - *그렇기 떄문에 해당 프로토콜을 준수한다면, 그 객체가 해당 기능들을 수행할수 있음을 보장할 수 있다.*

  <br>

- Hashable이 무엇이고, Equatable을 왜 상속해야 하는지 설명하시오.

<br>

- mutating 키워드에 대해 설명하시오.

  > **⚠️ 값타입의 프로퍼티를 변경하는 메소드에 작성해야하는 키워드입니다.**
  >
  > **⚠️  `mutating` 키워드가 붙은 메소드는 사실 프로퍼티를 바꾸는 것이 새로운 값 타입을 생성해서 대치시키는 과정이므로, 이를 컴파일러에게 명시해주는 키워드입니다.**

  <br>

- 탈출 클로저에 대하여 설명하시오.

  > **⚠️  클로저는 스위프트에서 참조 타입이며, 클로저를 함수의 인자로 전달할 수 있다.**
  >
  > **클로저를 전달받은 함수가 끝나고 제어흐름을 반환하기 전에 클로저를 호출한다면 문제가 되지 않지만, 제어흐름을 반환하고 그 이후 호출되는 클로저들이 있다. `DispatchQueue.async` 와 같은 예제가 있다. 이 경우 클로저가 메모리에 유지될 지 불투명하다.**
  >
  > **⚠️ 이런 경우 메모리에서 클로저를 해제되지 않게 `@escaping`을 키워드를 붙여서, 메모리에 남아 있게 할 수 있다.**

  <br>

- Extension에 대해 설명하시오.

  > **⚠️ 기존 (값,참조)타입들을 수평적으로 확장하는 형태입니다.** 
  > 
  > **⚠️ 기존타입에 사용자 정의메소드, 계산프로퍼티등을 추가하는 확장이 가능합니다.**
  > 
  > **⚠️ 프로토콜의 인터페이스 메소드를 기본구현할 수 있습니다.**
  > 
  > **⚠️ 관련된 코드블럭들을 분리하여 관리할 수 있습니다.**

- Class/ struct/ enum 차이점과 사용하는 나의 기준에 대해 설명하시오.

- 접근 제어자의 종류엔 어떤게 있는지 설명하시오

  	>✅ **open**  -  모든 수준의 접근이 열려 있다.
    >
    >✅ **pubilc** - 해당 모듈에서만 상속을 통한 타입확장이 가능하다.
    >
    >✅ **internal** - 해당 모듈에서만 접근이 가능하다. , Default 접근제한자이다.
    >
    >✅ **fileprivate** - 해당 파일에서만 접근이 가능하다.
    >
    >✅ **private** - 접근을 제한한다.

- defer란 무엇인지 설명하시오.

  > **✅ 제어권을 현재 스코프에서 다른 스코프로 전달할 때, 호출되는 지연 블록**
  > 
  > **✅ 자원 반납과 같은 후처리 부분을 지연블록에서 처리한다.**
  > 
  > **✅ 에러가 발생해도 지연블록을 호출되므로 후처리에 적합하다.**

- defer가 호출되는 순서는 어떻게 되고, defer가 호출되지 않는 경우를 설명하시오.

  > **✅ 선언된 순서와 역순으로 호출된다**
  > 
  > **✅ 만약 defer 블록에 도달하기도 전에 reture 된다면 그 이전에 명시된 defer 구문만이 호출된다**
  
- 생성자(designated/convenience/required)의 차이점과 특징을 설명하시오.

   >✅ **designated init 은 모든 멤버변수가 초기화하는 지정이니셜라이저**
   >
   >- *만약 하위타입의 init이라면 `super.init` 을 호출해야한다.*
   >- 만약 super클래스가 존재한다면, **확장된 프로퍼티를 초기화후 `super.init`을 호출**해야한다.
   >
   >✅ **convenience init 은 내부에서 designated init을 호출해야한다.**
   >
   >- *이니셜라이저 위임으로, `self.init`이 호출을 하기 이전에는 self에 접근 할 수 없으므로, designated init의 super와는 반대로 먼저 self.init을 호출해야한다.*
   >
   >**✅ required init은 해당 타입의 서브클래스들에게 특정 init의 구현을 강제하는 이니셜라이저이다.**

   >**모든 초기화는 아래의 단계를 거친다.**
   >
   >1. *Designated init 이 호출된다 - convenience init 을 통한 간접호출도 포함된다*
   >2. *초기화된 self.prop 을 수정할 기회가 주어진다.*

- 프로토콜 지향 프로그래밍에 대해서 설명하시오.

## ARC
- ARC란 무엇인지 설명하시오.

  >**✅ Swift에서는 메모리관리를 참조카운트를 통해서 하는데, 이것을 자동으로 계산해주는 메모리관리 방법이다.**

- Retain Count 방식에 대해 설명하시오.

  > **✅ 해당 객체를 다른 곳에서 참조하게 되면 retain count 가 증가하고, 참조를 마치게 되면 retain count를 감소시킨다.** 
  >
  > ✅ **객체의 retain count 가 0 이라면 해당 객체에 접근할 수 없기때문에, 더 이상 사용되지 않을 것이라고 판단해서 메모리에서 해제합니다.**

- Strong 과 Weak 참조 방식에 대해 설명하시오.

  > **✅  Strong 은 객체를 참조하며, 참조카운트를 1 증가시킨다. 그러므로 객체가 메모리에서 해제되지 않음을 보장할 수 있다.**
  >
  > **✅  Weak은 참조를 하되, 참조 카운트는 증가시키지 않아서, nil 로 바뀔 수 있는 가능성을 가지고 있다. 그래서 Optional과 var 을 사용한다.**

- Unowned 와 weak 의 차이점에 대해 설명하시오.

  > ✅  **Weak 참조는 참조하는 인스턴스가 더 짧은 생명주기를 가질 때 사용한다.  nil 가능성을 내포하고 있다.  참조가 0 이 되면 Zeroing 이라는 작업을 통해 dangling pointer 가 아닌 nil 을 할당한다.**
  >
  > **✅ unowned는 참조하는 인스턴스가 현재 인스턴스의 생명주기보다 길거나 같을 때 사용한다.** 

- ARC 대신 Manual Reference Count 방식으로 구현할 때 꼭 사용해야 하는 메서드들을 쓰고 역할을 설명하시오.

- retain 과 assign 의 차이점을 설명하시오.

- 순환 참조에 대하여 설명하시오.

- 강한 순환 참조 (Strong Reference Cycle) 는 어떤 경우에 발생하는지 설명하시오.

- 특정 객체를 autorelease 하기 위해 필요한 사항과 과정을 설명하시오.

- Autorelease Pool을 사용해야 하는 상황을 두 가지 이상 예로 들어 설명하시오. 

- 다음 코드를 실행하면 어떤 일이 발생할까 추측해서 설명하시오.
  Ball *ball = [[[[Ball alloc] init] autorelease] autorelease];

## Functional Programming
- 함수형 프로그래밍이 무엇인지 설명하시오.
- 고차 함수가 무엇인지 설명하시오.
- Swift Standard Library의 map, filter, reduce, compactMap, flatMap에 대하여 설명하시오.

# Optional
아래부터는 추가로 공부를 하면 좋을 내용들입니다.

Objective-c나 rx는 회사, 팀마다 사용하는곳이 차이가있고 신입이나 주니어기준으로 필수라고 여겨지지않기에 옵셔널에 추가하였습니다.

## Objective-C
- Mutable 객체과 Immutable 객체는 어떤것이 있는지 예를 들고, 차이점을 설명하시오.
- dynamic과 property 의미와 차이를 설명하시오.
- @property로 선언한 NSString* title 의 getter/setter 메서드를 구현해보시오.
- @property에서 atomic과 nonatomic 차이점을 설명하고, 어떤것이 안전한지, 어느것이 기본인지 설명하시오.
- @property로 선언한다는 것의 의미를 설명하고, .h에 넣을 경우와 .m에 넣을 경우 차이점을 설명하시오.
- -performSelector:withObject:afterDelay: 메시지를 보내면 인자값의 객체는 retain되는가? 그 이유를 함께 설명하시오.
- Objective-C 에서 캡슐화된 데이터를 접근하기 위한 방법들을 설명하시오.
- unnamed category 방식에 대해 설명하시오.
- Category 확장과 Subclass 확장의 차이점을 설명하시오.
- Category 방식에 대해 설명하시오.
- Objective-C 에서 Protocol 이란 무엇인지 설명하시오.
- Objective-C++ 방식이 무엇인지 설명하고, 어떤 경우 사용해야 하는지 설명하시오.
- method swizzling이 무엇이고, 어떨 때 사용하는지 설명하시오.

## Advanced
- NSCoder 클래스는 어떤 상황에서 어떻게 써야 하는지 설명하시오.
- Responder Chain 구조에 대해 설명하고, First Responder 역할에 대해 설명하시오.
- NSObject부터 UIButton 까지 상속 과정의 계층과 역할을 설명하시오.
- shallow copy와 deep copy의 차이점을 설명하시오.
- Push Notification 방식에 대해 설명하시오.
- Foundation 과 Core Foundation 프레임워크의 차이점을 설명하시오.
- NSURLConnection 에서 사용하는 Delegate 메서드들에 대해 설명하시오.
- Synchronous 방식과 Asynchronous 방식으로 URL Connection을 처리할 경우의 장단점을 비교하시오.
- Plist 파일 구조와 Plist 파일에 저장된 데이터를 다루기 적합한 클래스를 설명하시오.
- Core Data와 Sqlite 같은 데이터 베이스의 차이점을 설명하시오.
- JSON 데이터를 처리하는 방식과 파서, 객체 변환 방식에 대해 설명하시오.
- XML Parser를 사용하려면 어떻게 해야 하는지 설명하시오.
- 웹 서버와 HTTP 연결을 사용해서 데이터를 주거나 받으려면 사용해야 하는 클래스와 동작을 설명하시오.
- DOM 방식과 SAX 방식 XML Parser의 차이점을 설명하고 iOS XML Parser는 어떤 방식인지 설명하시오.
- In-App Purchase Product type 을 설명하시오.

## Architecture
- 의존성 주입에 대하여 설명하시오.

## Rx
- Reactive Programming이 무엇인지 설명하시오.
- RxSwift에서 Hot Observable과 Cold Observable의 차이를 설명하시오.
