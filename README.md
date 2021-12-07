# kotlin-minesweeper

## 기능 요구사항

### 지뢰 찾기를 변형한 프로그램을 구현한다.

- [X] 지뢰찾기는 보드, 지뢰, 벽으로 구성된다
- [X] 0 이상 높이를 입력받을 수 있다.
- [X] 0 이상 너비를 입력받을 수 있다
- [X] 0 이상 보드 너비 이하의 지뢰 개수를 입력받을 수 있다.
- [X] 보드에 지뢰가 존재하지않으면 예외를 던진다.
- [X] 블록을 생성하여 리턴한다
- [X] 각 사각형에 표시될 숫자는 자신을 제외한 주변 8개 사각형에 포함된 지뢰의 개수
- [X] 지뢰가 없는 인접한 칸이 모두 열리게 된다.

## 실행 결과

```
높이를 입력하세요.
10

너비를 입력하세요.
10

지뢰는 몇 개인가요?
10

지뢰찾기 게임 시작
open: 1, 1
0 1 C C C C C C C C
0 1 C C C C C C C C
0 1 C C C C C C C C
1 1 C C C C C C C C
C C C C C C C C C C
C C C C C C C C C C
C C C C C C C C C C
C C C C C C C C C C
C C C C C C C C C C
C C C C C C C C C C

open: 4, 1
Lose Game.
```

## 프로그래밍 요구 사항

- 객체 지향 5원칙을 지키면서 프로그래밍한다. 객체지향 5원칙(SOLID)

- SRP (단일책임의 원칙: Single Responsibility Principle): 작성된 클래스는 하나의 기능만 가지며 클래스가 제공하는 모든 서비스는 그 하나의 책임(변화의 축: axis of
  change)을 수행하는 데 집중되어 있어야 한다
- OCP (개방폐쇄의 원칙: Open Close Principle): 소프트웨어의 구성요소(컴포넌트, 클래스, 모듈, 함수)는 확장에는 열려있고, 변경에는 닫혀있어야 한다.
- LSP (리스코브 치환의 원칙: The Liskov Substitution Principle): 서브 타입은 언제나 기반 타입으로 교체할 수 있어야 한다. 즉, 서브 타입은 언제나 기반 타입과 호환될 수 있어야
  한다.
- ISP (인터페이스 분리의 원칙: Interface Segregation Principle): 한 클래스는 자신이 사용하지 않는 인터페이스는 구현하지 말아야 한다.
- DIP (의존성역전의 원칙: Dependency Inversion Principle): 구조적 디자인에서 발생하던 하위 레벨 모듈의 변경이 상위 레벨 모듈의 변경을 요구하는 위계관계를 끊는 의미의 역전 원칙이다.
