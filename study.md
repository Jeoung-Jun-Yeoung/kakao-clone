# Nomad coder kakao-clone study

### 2021/12/17

HTML은 브라우저에게 웹사이트의 컨텐츠가 어떻게 구성되어 있는지 설명.

구성을 설명한다? -> 어떤 구조로 되어 있는지 알려준다.

즉, 설계도라고 볼 수 있다.

css는 html과 같이 사용한다. css는 브라우저에게 웹사이트가 어떻게 보여주어야 하는지 알려준다.

What is content ? Html

How represent content(html)? Css

### 요약

Html is mark up language, markup is content

Css is the how do like look content! (Design, style)

Javascrip is interactive

### 2021/12/19

브라우저는 컨텐츠를 보여주려고 한다.

HTML코드를 작성하는 법. HTML의 목적인 브라우저에게 구조를 알려주는것. 이때 어디서부터 어디까지 어떤 내용인지 표시. 이때 어디의 역할을 하는것이 tag <>다.

example: <food>김치</food> 주의! 실제로 food 태그는 없다. 이해를 돕기 위한것.

모든 의미는 tag단위로 구분된다.

연습 : h1,h2 tag use

브라우저는 작성된 태그에 따라 내용을 보여준다.

### 2021/12/20

<li> tag 연습.

<ol> order <ul> nonorder <li> item

<a> tag 는 앵커. 다른웹사이트로 가고 싶을때 사용하는 태그. 이때 <a>는 태그에 부가정보를 주어야 한다.

부가정보는 attribute(속성)이라고 한다.

속성이 있는 태그와 없는 태그가 나뉜다. 이때 속성이 없는 태그는 속성을 주어도 아무런 영향이 없다. 웹브라우저가 알아듣지 못하기 때문이다.

<a> tag attribute
href - 원하는 url링크
target - 기본이 self, 창이 뜨는 위치조절

tag중에는 스스로 닫느 self closing tag가 있다.

가장 대표적인것은 <img> 이미지는 택스트 내용이 들어가지 않기 때문에 닫아줄 필요가 없다!
attribute인 src자체가 컨텐츠 이기 떄문이다.
<img>는 src에 온라인 말고, local주소도 줄 수 있다. 경로를 통해 준다.

---s

<html>태그의 규칙 - 해당 s태그는 안에 있는 모든 태그가 html코드임을 명시한다.
<body> - 브라우저에 보여질 컨텐츠들을 담는 태그들을 모은다.
<head> - setting 담당.s 페이지에 관한 환경을 설정. 헤드 태그에 속한 태그들은 보여지지 않는다. 브라우저의 화면상에 보여질 내용들은 전부 <body>에 있어야 한다.

---

<meta> - 부가적인 정보. content, name 두가지 attribute를 가진다.
<link> - tap에 아이콘을 넣을 수 있다.
보이지 않는 태그들로 어떻게 보여지게 할 수 있는지. head태그로 설정한다.
<meta property og:image, og:title ,, 등등> - 공유될때 보여지는 태그들이다.

### 2021/12/21

tag검색시 mdn을 넣어서 검색해라. 그래야 mozilla에서 제공하는 문서를 볼 수 있다.

참고 : https://developer.mozilla.org/ko/docs/Web/HTML/Element

tag를 외울 필요없이 예제를 보고 따라해보기!

<p>태그의 다양한 속성들 사용해봄
<audio>사용해보기.

### 2021/12/23

휴식!!
