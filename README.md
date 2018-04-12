# 프로그래밍 하다 막힌 부분 기록해두기 (2018.4.12~




*****

1 문제 빨리 해결하는 팁

-객체 클래스는 VO, DTO처럼 생각하자

-객체 클래스라면 생성, 소멸도 생각하자


<h2>자료구조</h2>

1 처음 메서드가 어디부터 시작하는지 파악하면 좀 덜 막막함

2 원리에 대한 배경지식이 있으면 코딩이 쉬워지고, 이해력 증가

ex) 스택, 큐는 쉽게했는데, LinkedList 구현에서 막힌 이유- LinkedList의 작동원리에 대해 깊게 고민 안 해서

3 노드는 객체 

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
<h2>정의를 명확히 구체적으로 하는 것이 중요</h2>

4.13 

<h4>1 처음 연결리스트에 대한 정의</h4>

연결리스트는 넥스트 노드와 데이터만 포함한 노드의 연결로 구성된다

-> 이 정의의 한계 : 노드 클래스와 LinkedList 클래스 생성 및 객체 선언까지만 연상 가능

-> 결과: 구현이 막막해짐



<h4>2 추가 연결리스트에 대한 정의-넥스트 노드와 데이터와 노드의 연결에 대해 구체화</h4>

넥스트 노드(노드에 포함된 객체)

->언제 생성되는가 (평소 안 접해서 생각을 바로 못함 )

->노드는 자신의 넥스트 노드를 언제 주입받는가?

->언제 소멸되는가 (평소 안 접해서 생각을 바로 못함 )


데이터(노드에 포함된 데이터)

->몇 번째 노드에 주입되는가

