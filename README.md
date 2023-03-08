# Java-Deep-Dive

# Java Garbage Collection

**#들어가기 전 알아야 할 개념**

stop-the-world : GC를 실행하기 위해 JVM이 애플리케이션 실행을 멈추는 것

→ stop- the-world 가 발생하면 GC를 실행하는 쓰레드를 제외한 나머지 쓰레드는 모든 작업을 멈춤

GC 작업을 완료한 이후에야 중단했던 작업을 다시 시작함

어떤 GC 알고리즘을 사용하더라도 stop-the-world는 발생함

대개의 경우 GC튜닝이란 이 stop-the-world 시간을 줄이는 것

**#GC 등장 배경**

Java는 프로그램 코드에서 메모리를 명시적으로 지정하여 해제하지 않음

가끔 명시적으로 해제하려고 해당 객체 null로 지정, System.gc() 메서드를 호출하는 개발자가 있음

null로 지정하는 것은 큰 문제가 안되지만 System.gc() 메서드를 호출하는 것은 시스템의 성능에 매우 큰 영향을 끼치므로 System.gc() 메서드는 절대로 사용하면 안됨
