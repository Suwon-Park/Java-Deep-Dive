# 1. 자바(Java Programming Language)

## 1.1 자바란?

 자바는 썬 마이크로시스템즈(Sun Microsystems, Inc, 이하 썬)에서 개발하여 1996년 1월에 공식적으로 발표한 객체지향 프로그래밍 언어임

**#자바의 특징**

1. 운영체제에 독립적이다

→ 자바로 작성된 프로그램은 운영체제의 종류에 관계없이 실행이 가능하기 때문에, 운영체제에 따라 프로그램을 전혀 변경하지 않고도 실행이 가능하다

이러한 장점으로 인해 자바는 다양한 기종의 컴퓨터와 운영체제가 공존하는 인터넷 환경에 적합한 언어로써 인터넷의 발전과 함께 많은 사용자층을 확보할 수 있었다

1. 자바는 풍부한 클래스 라이브러리(Java API)를 통해 프로그래밍에 필요한 요소들을 기본적으로 제공하기 때문에 자바 프로그래머는 단순히 이 클래스 라이브러리만을 잘 활용해도 강력한 기능의 자바 프로그램을 작성할 수 있다

## 1.2 자바의 역사

자바의 역사는 1991년에 썬의 엔지니어들에 의해서 고안된 오크(Oak)라는 언어에서부터 시작

**#C++기반 언어 Oak 탄생**

제임스 고슬링과 아서 밴 호프와 같은 썬의 엔지니어들의 원래 목표는 가진 제품에 탑재될 소프트웨어를 만드는 것이였음

처음에는 C++을 확장해서 사용하려 했지만 C++로는 그들의 목적을 이루기에 부족하다는 것을 깨달음

그래서 C++의 장점을 도입하고 단점을 보완한 새로운 언어를 개발하기에 이르렀음

**#인터넷 등장 후 Java로 변경**

Oak는 처음에는 가전제품이나 PDA와 같은 소형기기에 사용될 목적이었으나 여러 종류의 운영체제를 사용하는 컴퓨터들이 통신하는 인터넷이 등장하자 운영체제에 독립적인 Oak가 이에 적합하다고 판단하여 Oak를 인터넷에 적합하도록 그 개발 방향을 바꾸면서 이름을 자바로 변경하였으며, 자바로 개발한 웹 브라우저인 핫 자바(Hot Java)를 발표하고 그 다음 해인 1996년 1월에 자바의 정석 버전을 발표했음

## 1.3 자바언어의 특징

 **1. 운영체제에 독립적이다**

기존의 언어는 한 운영체제에 맞게 개발된 프로그램을 다른 종류의 운영체제에 적용하기 위해서 많은 노력이 필요하였지만, 자바에서는 더 이상 그런 노력을 하지 않아도 됨

→ 자바가상머신(JVM) 덕분에 !

자바 응용프로그램은 운영체제나 하드웨어가 아닌 JVM하고만 통신하고 JVM이 자바 응용프로그램으로부터 전달받은 명령을 해당 운영체제가 이해할 수 있도록 변환하여 전달

자바로 작성된 프로그램은 운영체제에 독립적이지만 JVM은 운영체제에 종속적이어서 썬에서는 여러 운영체제에 설치할 수 있는 서로 다른 버전의 JVM 제공

그래서 자바로 작성된 프로그램은 운영체제와 하드웨어에 관계없이 실행 가능하며 이것을 한번 작성하면 어디서나 실행됨  → **Write once, run anywhere**

**2. 객체지향언어이다**

자바는 프로그래밍의 대세로 자리 잡은 객체지향 프로그래밍언어(object-oriented programming laguage) 중의 하나로 객체지향개념의 특징인 상속, 캡슐화, 다형성이 잘 적용된 순수한 객체지향언어라는 평가를 받고 있음

**3. 비교적 배우기 쉽다**

C++ → 자바의 연산자와 기본구문

스몰톡(small talk) → 객체지향관련 구문

이 들 언어의 장점은 취하면서 복잡하고 불필요한 부분은 과감히 제거하여 단순화함으로서 쉽게 배울 수 있으며, 간결하고 이해하기 쉬운 코드를 작성할 수 있도록 함

**4. 자동 메모리 관리(Garbage Collection)**

**5. 네트워크와 분산처리를 지원한다**

**6. 멀티쓰레드를 지원한다**

**7. 동적 로딩(Dynamic Loading)을 지원한다**
