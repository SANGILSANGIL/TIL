# TIL
Today I Learned

## HTML에 관련된 질문들:

* `doctype`이 무엇을 하는 것이고, 몇 번 지정할 수 있나요?
* [표준모드(standards mode)와 쿽스모드(quirks mode)의 다른 점은 무엇인가요?](/HTML/표준모드%20standards%20mode%20와%20쿽스모드%20quirks%20mode의%20다른%20점은%20무엇인가요%3F.md)
* XHTML을 이용한 페이지의 한계점은 무엇이 있나요?
	* `application/xhtml+xml`으로 지정한 페이지에 어떠한 문제가 있나요?
* 다국어가 포함된 페이지는 어떤 방식으로 제공하나요?
* HTML5에서 XHTML문법을 사용할 수 있나요? HTML5에서 XML을 어떻게 사용하나요?
* `data-`속성은 무엇을 하는 것인가요?
* HTML4에서 콘텐츠 모델(content models)은 무엇이며, HTML5의 그것과 다른 점은 무엇인가요?
* HTML5를 오픈웹플랫폼(open web platform)으로 생각해본다면, 어떤 것들로 구성돼 있을까요?
* [쿠키(Cookies)와 세션저장소(sessionStorage)와 로컬저장소(localStorage)의 차이점을 설명해주세요](/HTML/쿠키(Cookies)와%20세션저장소(sessionStorage)와%20로컬저장소(localStorage)의%20차이점을%20설명해주세요.)
* 

## CSS 관련 질문들:

* "reset" CSS가 무엇인지, 어떻게 유용한지 설명 해주세요.
* Floats가 어떻게 동작하는지 설명해주세요.
* 클리어링(Clearing) 기술에는 어떤 것들이 있으며, 어떠한 경우에 어떻게 사용하는 것이 적절한지 설명하세요.
* CSS 스프라이트(CSS Sprites)를 설명하고, 페이지나 사이트를 어떻게 향상시키는지 설명하시오.
* IE box model과 W3C box model의 차이점을 설명하시오.
* Image Replacement를 사용해야 할 때, 선호하는 기술과 언제 사용하는지를 설명 해주세요.
* CSS 요소핵(CSS property hacks)을 조건부적으로 .css파일안에 넣으시나요 혹은 다른 방식이 있나요?
* 기능이 제약된 브라우저를 위해서 어떤 방식으로 페이지를 만드나요?
	* 어떠한 기술과 절차를 거치는지 설명하시오.
* 컨텐츠를 안보이게 하는 기술들의 차이점을 설명하시오.(그리고 스크린 리더(Screen readers)에서 접근이 가능한 방법은?)
* 그리드 시스템(Grid system)을 사용한 적이 있나요? 있다면 어떠한 것을 선호하나요?
* 미디어 쿼리(media queries)를 사용한 적이 있나요? 혹은 모바일에 맞는 layout과 CSS를 사용한 적이 있나요?
* SVG를 스타일링 하기 위한 편한 방법이 있나요?
* 인쇄를 하기 위해 웹페이지를 어떻게 최적화 하나요?
* 효율적인 CSS를 작성하기 위한 "비법(gotchas)"은 어떤 게 있나요?
* [CSS 전처리(CSS preprocessors)를 사용해보셨나요?](/CSS/CSS%20전처리%20CSS%20preprocessors를%20사용해보셨나요.md)
* 페이지에서 표준 폰트가 아닌 폰트 디자인을 사용할 때 어떤 방식으로 처리하시나요?(웹폰트를 제외하고)
* CSS Selector가 어떠한 원리로 동작하는지 설명하시오.



## Javascript에 관련된 질문들:

* 사용해 본 Javascript 라이브러리들을 말씀해주세요.
* Java와 Javascript의 다른 점은 무엇인가요?
* [`undefined`와 `undeclared` 변수는 무엇인가요?](/JS/undefined와%20undeclared%20변수는%20무엇인가요%3F.md)
* 클로져(Closure)는 무엇이며, 어떻게/왜 사용하는지 설명해주세요.
	* 클로져를 만들 때 선호하는 패턴은 무엇인가요? argyle (IIFEs에만 적용할 수 있다)
* 익명함수(anonymous functions)는 주로 어떤 상황에서 사용하나요?
* "Javascript 모듈 패턴(Javascript module pattern)"이 무엇인지 설명을 해주시고, 언제 사용하는지도 말씀해주시기 바랍니다.
	* "네임스페이스(namespacing)"에 대해서 언급을 하면, 보너스 포인트가 있습니다.
	* 당신의 모듈이 네임스페이스가 없는 상황이라면?
* 당신의 코드를 어떻게 구성하는지?(모듈 패턴, Class기반 상속?)
* [호스트 객체(Host Objects)와 네이티브 객체(Native Objects)의 차이점은 무엇인가요?](/JS/호스트%20객체%20Host%20Objects와%20네이티브%20객체Native%20Objects의%20차이점은%20무엇인가요%3F.md)
* [다음 코드의 차이점은 무엇인가요?](/JS/다음%20코드의%20차이점은%20무엇인가요%3F.md)
```javascript
function Person(){} var person = Person() var person = new Person()
```
* `.call`과 `.apply`의 차이점은 무엇인가요?
* `Function.prototype.bind`을 설명 하시오
* 코드 최적화를 하는 시점은 언제인가요?
* Javascript에서 어떻게 상속을 하는지 설명할 수 있나요?
	* "누구도 할 수 없어요" 같은 재밌는 대답 시에 보너스 포인트가 있습니다.
	* 안되는 이유에 대해서 설명을 시도한다면, 더 많은 점수를 주세요.
* `document.write()`를 언제 사용하시나요?
	* 정답 : 1999년 - 초보개발자를 걸러내기 위한 시절
* UA문자열을 이용하여 기능 검출(feature detection)과 기능 추론(feature inference)의 차이점을 설명 하시오.
* [AJAX에 관해 가능한 자세히 설명하세요.](/JS/AJAX에%20관해%20가능한%20자세히%20설명하세요.md)
* [JSONP가 어떻게 동작 되는지 설명하세요.(그리고,실제 AJAX와 어떻게 다른지 설명하세요.)](JS/JSONP%EA%B0%80%20%EC%96%B4%EB%96%BB%EA%B2%8C%20%EB%8F%99%EC%9E%91%20%EB%90%98%EB%8A%94%EC%A7%80%20%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94.(%EA%B7%B8%EB%A6%AC%EA%B3%A0%2C%EC%8B%A4%EC%A0%9C%20AJAX%EC%99%80%20%EC%96%B4%EB%96%BB%EA%B2%8C%20%EB%8B%A4%EB%A5%B8%EC%A7%80%20%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94.).md)

* 기존에 Javascript 템플릿을 사용한 적이 있나요? 만약에 있다면, 어떠한 방식으로 사용했는지 말씀해주세요.
* ["호이스팅(Hoisting)"에 대해서 설명 하시오.](JS/"호이스팅(Hoisting)"에%20대해서%20설명%20하시오.md)
* FOUC가 무엇이며 FOUC를 어떻게 방지하나요?
* 이벤트 버블링(Event Bubbling)에 대해서 설명하세요.
* "속성(Attribute)"와 "요소(property)"의 차이가 무엇인가요?
* Javascript 객체를 확장하는 것이 좋지 않은 이유는 무엇인가요?
* [Document Load 이벤트와 Ready 이벤트의 차이가 무엇인가요?](/JS/Document%20Load%20이벤트와%20Ready%20이벤트의%20차이가%20무엇인가요%3F.md)
* `==`와 `===`의 차이점은 무엇인가요?
* 브라우저의 URL에서 파라메터를 얻을 수 있는 방법에 대해서 설명하세요.
* [Javascript의 "동일출처정책(the same-origin policy)"에 대해서 설명하세요.](JS/Javascript의%20"동일출처정책%20the%20same-origin%20policy"에%20대해서%20설명하세요.md)
* [이벤트 딜리게이션(Event Delegation)에 대해서 설명하세요.](/JS/이벤트%20딜리게이션%20Event%20Delegation에%20대해서%20설명하세요.md)
* Javascript의 상속패턴(inheritance patterns)에 대해서 설명하세요.
* 다음 코드를 동작하게 만드세요.
```javascript
[1,2,3,4,5].duplicator(); // [1,2,3,4,5,1,2,3,4,5]
```
* Javascript에서 메모이제이션(memoization, 중복 계산 방지)에 대한 전략을 설명해주세요.
* 삼항식(Ternary statement)을 사용하는 이유는 무엇이고, 그것을 표현하기 위한 연산자 단어는 무엇인가요?
* arity는 어떠한 함수인가요?


###back-end
* [socket](/back_end/socket.md)
* [nginx](/back_end/nginx.md)
* 최적의 서버 구성도
* 채팅에서의 세션 유지 방법은?
* [http status code](/back_end/http%20status%20code.md)
* [db 테이블에 pk가 두개 이상인 경우](/back_end/db%20pk가%20두개%20있는%20경우.md)
* [db 엔진](/back_end/db엔진.md)
* [Auto_Increment를 맹신하지 말자](/back_end/innodb의%20%20auto%20increment%20는%20맹신하지%20말자.md)
* [pk가 int가 아닌 경우](/back_end/pk가%20int가%20아닌%20경우.md)
* [db 인덱스 트리 ](/back_end/db%20인덱스%20트리.md)

###php

* php 기본 구조
* zend
* php의 가비지 컬렉션
* php 버전별 서능 비교
* php 문제점
* include와 require의 차이점
* 네임스페이스
* phalcon vs laravel vs CI
* python
* python 가비지 컬렉션
* 

## 일반적인 질문:

* Twitter,Facebook 혹은 Me2day등의 SNS를 사용하시나요?
	* 사용한다면, 누구를 팔로우 하고 있나요?
* GitHub을 사용하시나요?
	* 사용한다면, 어떤 프로젝트를 Watch 혹은 Fork하시나요?
* 자주 보는 Blog가 있습니까?
* 버전 관리 시스템은 어떤 것들을 사용해보셨습니까?
* 선호하는 개발 환경은 무엇입니까? (운영체제, 에디터, 브라우저, 도구 등등)
* 당신이 웹 페이지를 만들 때의 과정을 설명 해주실 수 있을까요?
* 점진적 향상법(progressive enhancement)과 우아한 성능저하법(graceful degradation)의 차이를 설명하실 수 있습니까?
	* "누구도 성공하지 못합니다" 라고 말하면 보너스 포인트를 주세요.
	* 각 특색을 설명을 한다면, 더 높은 보너스 포인트를 주세요.
* "시멘틱 HTML(Semantic HTML)"이 무엇을 뜻하는지 설명해주세요.
* "최소화(minification)"가 무엇을 하는 것입니까?
* 여러 도메인을 이용하여 서버 사이트 데이터를 제공하는 것이 더 나은 이유는 무엇인가요?
	* [브라우저가 한 번에 1개의 도메인에서 다운로드 받는 리소스는 몇 개 인가요?](/default/브라우저가%20한%20번에%201개의%20도메인에서%20다운로드%20받는%20리소스는%20몇%20개%20인가요%3F)
* 만약에 디자인을 표현하기 위해 8개의 다른 Stylesheet를 가지고 있다면, 사이트에서는 어떻게 통합하실 건가요?
	* 파일의 연결법을 찾아내세요.
	* Build system을 이용한 결합없이, `@import`를 사용하면 점수를 깎으세요.
* 당신이 프로젝트에 합류했습니다. 근데 그들은 Tab을 이용하고, 당신은 Sapce를 사용했습니다. 어떻게 하실건가요?
	* `:retab!` 명령어를 아는지 확인
* 간단한 Slideshow 페이지를 만들어보세요.
	* Javascript를 사용하지 않고 만들었다면, 보너스 점수가 있습니다.
* 당신의 코드의 성능을 테스트하기 위해서 사용하는 도구가 무엇입니까?
* 올해 당신이 익히고 싶은 기술이 있다면, 그것은 무엇입니까?
* [페이지 로딩 시간을 줄이는 3가지 방법은?](/default/페이지%20로딩%20시간을%20줄이는%203가지%20방법은%3F.md)
* 표준의 중요함을 설명하세요.
* 

### 하드웨어
* [빅 엔디안 vs 리틀 엔디안](/hardware/빅%20엔디안%20vs%20리틀%20엔디안.md)
* [CPU 구조](/hardware/cpu%20구조.md)
* 프리페치 큐의 성능 향상을 방해하는 요소들
* 파이프 라이닝 - 여러 명령어 수행 중첩
* [슈퍼스칼라 오퍼레이션](hardware/슈퍼스칼라%20오퍼레이션.md)
* [레지스터 이름 바꾸기](/hardware/레지스터%20이름%20바꾸기.md)
* [하이퍼 스레드](/hardware/하이퍼%20스레드.md)
* [캐쉬 구조와 접근](/hardware/캐쉬%20구조와%20접근.md)
* [메모리를 고려한 소프트웨어 작성](/hardware/메모리를%20고려한%20소프트웨어%20작성.md)
* [실행중 메모리의 구성 방식](/hardware/실행중%20메모리의%20구성%20방식.md)
* 컴파일러 번역과정
* 컴파일러 파싱
* 컴파일러 최적화 과정
* 공통 컴파일러 최적화화
* 어플리케이션 내부 단편화
* 실행시 메모리 구성
* [변수](/hardware/변수.md)
* [활성테이블과 함수 스택](/hardware/활성테이블과%20함수%20스택.md)
* [지역 / 전역 변수 차이](/hardware/%20지역%20전역%20변수%20차이.md)
* [동적변수](/hardware/동적변수.md)
* [레지스터변수](/hardware/레지스터변수.md)
* [메모리에서 변수 표현](/hardware/메모리에서%20변수%20표현.md)
* [다차원 배열의 원소 접근](/hardware/다차원%20배열의%20원소%20접근.md)
* [배열 접근 효율 높이기](/hardware/배열%20접근%20효율%20높이기.md)
* [반복 연산 회피](/hardware/반복%20연산%20회피.md)
* [메모리 할당](/hardware/메모리%20할당.md)
* [가상 메소드 테이블](/가상%20메소드%20테이블.md)
* [클래스 상속과 메모리](/hardware/클래스%20상속과%20메모리.md)
* [함수와 프로시저 호출](/hardware/함수와%20프로시저%20호출.md)
* [반환 주소 저장](/hardware/반환%20주소%20저장.md)
* [전역변수 사용시 주의할 점](/hardware/전역변수%20사용시%20주의할%20점.md) 
* 


### Q&A
* [http status code](/master/back_end/http%20status%20code.md)
* 인터페이스란?
* [애자일](/q%26a/애자일.md)
* [칸반](/q&a/칸반.md)
* 오버라이딩 vs 오버로딩
* oop의 자신의 의견
* 클래스 세분화 방법
* 리펙토링 방법
* 가비지 컬렉션
* 리스트 구현
* 리스트 장단점
* 간단한 채팅 프로그램구현
* git 사용 및 단점
* 프레임워크 /  라이블러리
- 아이덴티티 vs 이퀄리티 (https://www.youtube.com/watch?v=9eQvMygux6g)
- 추상화 / 캡슐화 / 상속 / 다양성에 대해서 and  둘중 어느게 더 중요한지 ( oop에 대해서 얼마나 생각하는지 )
- [oop 5대 원칙](/q%26a/%20oop%205대%20원칙.md)
* 재귀함수
* 정규표현식
* 웹브라우저 작동 방식
* string ' or "
* [물어볼 질문들](/q&a/물어볼%20질문들.md)
* 
* 
* 
