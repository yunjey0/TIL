# 40. @Override 어노테이션을 일관되게 사용하라.

Created: 2021년 5월 2일
Created by: Seha Jyang

- 상위 클래스의 메서드를 재정의하려는 모든메서드에 `@Override` 어노테이션을 달자.
- 예외는 한가지뿐이다. 구체 클래스에서 상의 클래스의 추상 메서드를 재정의한 경우엔 이 어노테이션을 달지 않아도 된다.(단다고 해서 나쁠건 없다)