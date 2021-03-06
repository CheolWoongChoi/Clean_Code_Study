## 0장, 들어가면서

- 서론

  - 이 책은 "Clean Code"에 대해 합리적인 원칙을 세우기 위한 "기초 지식"을 제공한다.
  - 보이스카우트 원칙?

- 장인정신

  - 코딩은 장인정신이 필요하다. 이론 + 실전
  - 이론
  - 실전

- 책 구성
  - 첫번째 파트 : 이론, 패턴
  - 두번째 파트 : 여러 사례 연구 (난이도 높음)
  - 세번째 파트 : 결론

## 1장, 깨끗한 코드

- 나쁜 코드?

  - 남이 짜놓은 or 내가 짠 쓰레기 코드
    - 앞으로의 고생길을 만들어준다...
    - 생산성 Down
  - 르블랑의 법칙
    - 코드를 리팩토링할 기회는 잘 오지 않는다.

- 보이스카우트 규칙

  - "캠프장은 처음 왔을 때보다 더 깨끗하게 해놓고 떠나라"
  - 이것을 코드에 적용하기

- SOLID 원칙

  - 객체지향 설계의 핵심원칙

- 코딩도 예술의 세계!

- Question
  - 남이 짠 코드 때문에 고생한 경험이 있는가?
    - 많다...

## 2장. 의미있는 이름

### 의도를 분명하게 밝혀라

- 변수, 함수, 클래스
- 이들의 1) 존재 이유는? 2) 수행 기능은? 3) 사용 방법은?

### 그릇된 정보를 피하라

- "예약어"로 이름 짓지 말기
- 비슷한 이름 사용주의
- 유사한 개념은 유사한 표기법 사용

### 의미 있게 구분하라

- 연속된 숫자 X
- 불용어(noise word, 의미 없는 단어) 추가 X

### 발음하기 쉬운 이름을 사용해라

- 코드를 작성하는 시간보다 읽을 시간이 더 많다
- 발음하기 쉬운 이름이 더 이해하기 쉽다

### 검색하기 쉬운 이름을 사용하라

- 이름 길이는 범위 크기에 비례해야 한다
  - 말이 어렵네... 무슨 말일까?
  - 여러 곳에서 사용하는 코드는 검색하기 쉬운 이름이 바람직하다
  - 이름이 길면 길수록, 오히려 더 눈에 띄고, 검색하기 더 쉬워진다.

### 인코딩을 피하라

- 멤버 변수 접두어
- 인터페이스 클래스와 구현 클래스

  - 인터페이스명 : IShapeFactory VS ShapeFactory
  - 구현클래스명 : ShapeFactoryImp, CShapeFactory

- 인터페이스 이름 앞에 I 등을 붙이는 관례가 있는 데, 저자는 비추천
  - 회사, 개인마다 케바케

### 자신의 기억력을 자랑하지 마라

- 명료한 단어를 사용하기

### 클래스 이름

- 명사 또는 명사구
- 자주 쓰이는 단어 사용하지 않기
  - Manager, Processor, Data, Info

### 메서드 이름

- 동사 또는 동사구

### 기발한 이름은 피하라

- 구어체, 속어, 특정분야 용어 등...
- 즉, 자기만 알만한 용어 삼가

### 한 개념에 한 단어를 사용

- 일관성 있게 네이밍
- fetch / retrieve / get
  - 이 세 개가 모두 같은 의미라면 하나로 통일하기

### 의미 있는 맥락을 사용해라
