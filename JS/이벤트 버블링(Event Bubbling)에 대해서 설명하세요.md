#이벤트 버블링(Event Bubbling)에 대해서 설명하세요.


이벤트 버블링 이란
이벤트가 발생한 엘리먼트에 핸들러가 할당되었는지 확인하고 할당되었다면 핸들러를 호출한다.
그 이후 해당 엘리먼트의 부모부터 시작하여 DOM 트리의 루트까지 하나하나 올라가며 동일한 이벤트 타입의 핸들러가 할당되어 있는지
확인하고, 할당되어 있다면 이를 실행한다.
이 이벤트 핸들링이 마치 샴페일 플루투의 거품처럼 위로 퍼진다 하여 이벤트 버블링(Bubbling)이라 한다.


이 이벤트 버블링을 명확하게 이해하는데엔 DOM 레벨 2의 이벤트 흐름을 살펴보는 것이 도움이 된다.
그 흐름을 그려보면 다음과 같다.

![http://cfile9.uf.tistory.com/original/031E0240519346A407A1FD](http://cfile9.uf.tistory.com/original/031E0240519346A407A1FD)

##해결책
- 해당 DOM에만 이벤트가 발생하도록 꼭 찝어준다 (보통 전체 혹은 DOM이름으로 이벤트를 걸었기 때문이다. - $(div).on..과 같이 )
- stopPropagation();함수로 한번만 실행시킬수 있다. (정말 안될때 사용)
