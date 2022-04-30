# Study_step2
Take a class youtuber webstoryboy's 'coding responsive website' lecture!

## 1. Semantic Tag (시맨틱태그)
* &lt;header&gt;
  * 하나 이상의 제목요소(h)를 가져야 함
* &lt;nav&gt;
  * 사이트의 주요 목차 및 메뉴 등을 포함
  * 일반적으로 footer 영역에는 사용하지 않음
* &lt;main&gt;
  * 문서의 핵심 / 2개 이상 존재 불가
  * header, nav, article, asdie, footer 요소의 자식으로 불가능
* &lt;section&gt;
* &lt;article&gt;
* &lt;aside&gt;
  * 부가적인 내용 ex) 사이드바
* &lt;footer&gt;
  * 제목요소(h)를 가질 수 없음
-------
## 2. media query (미디어쿼리)
* grammer
  * `@media only all and (조건문) {실행문}`
  * @media : 미디어쿼리가 시작됨을 표시
  * only : 미디어쿼리 구문 해석 시작 명령어 (생략 가능)
  * all : 미디어쿼리 해석 대상을 나타냄 (생략 가능)
  * and : 앞과 뒤의 조건을 나타냄 (생략 가능)

* 미디어쿼리 해석 대상 목록
  * all : 모든 미디어 유형에서 사용할 CSS를 정의
  * print : 인쇄 장치에서 사용할 CSS를 정의
  * screen : 컴퓨터 스크린에서 사용할 CSS를 정의
  * aural : 화면을 읽어 소리를 출력해주는 장치에서 사용할 CSS를 정의
  * tv : TV에서 사용할 CSS를 정의
  * handheld : 손에 들고 다니는 장치에서 사용할 CSS를 정의
  * projection : 프로젝트를 위해 사용할 CSS를 정의

* 중단점 (새로운 화면크기의 장치들이 나오기에 고정적인 값이 아님)
  * 데스크탑 이상 :
  * 데스크탑 :
  * 노트북 :
  * 태블릿 :
  * 모바일 :
