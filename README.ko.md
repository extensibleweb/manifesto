The Extensible Web Manifesto
============================

우리- [선언문 서명자](https://extensiblewebmanifesto.org/#signatories)는 지금까지 웹 표준화 단체가 새로운 기능을 추가하거나, 우선 순위를 결정하기 위해 취해 온 기존 방식을 바꿔야한다고 생각합니다. 이는 장기적으로 웹 개발 생태계를 건강하게 유지하는데 필요한 일이라고 생각하고 있기 때문입니다.

이를 위해 웹 표준을 제정하는 편집자와 웹개발자 사이에 좀 더 신속한 의사결정과정(결정하고 그에 따라 행동안이 나오고, 행동안에 따른 결과가 또 바로 결정에 반영되는 과정)이 필요합니다.
 
오늘날 대부분 신규 기능은 수 개월 혹은 매년 표준화를 진행하고 이에 따라 브라우저 벤더의 구현을 거쳐 그 이후 개발자의 피드백을 받는 방식으로 진행합니다. 우리는 개발자에 의한 자바스크립트의 새로운 기능개발을 선호하면서 브라우저와 표준화가 이를 반영하기를 선호합니다.

라이브러리를 통해 더 많은 것을 하기 위해서는 브라우저 벤더들이 기본 플랫폼이 가진 가능성을 최대한 활용하기 위한 기본 수준의(Low-level) 기능을 더 많이 제공해야합니다.

이를 토대로 JavaScript를 통해 신규 기능을 구현할 수 있는 높은 수준(High-level) API에 대한 토대를 제공해야 합니다. (사례 Mozilla X-Tags(http://www.x-tags.org/) 및 Google의 Polymer(http://www.polymer-project.org/).)

------

확장 가능한 웹 플랫폼(Extensible Web Platform)은 아래의 설계 원칙을 따르기를 제안합니다.
*웹 플랫폼에 대한 안전하고 효과적인 **새로운 기본 수준 기능** 개발에 주력 해야합니다.
* HTML이나 CSS 등의 **기존 기능을 구현**하는 기본 수준의 기능을 제공함으로써, 웹 개발자가 이해하고 재현할 수 있도록 해야합니다.
* 웹 개발자가 새로운 높은 수준의 API를 개발·표현·테스트를 JavaScript로 하고 개발자들이 표준화되기 전에 반복 테스트할 수 있도록 해야합니다. 이를 통해 표준을 만드는 사람과 개발자 사이의 **의미있는 피드백 체계**를 제공합니다.
* 향후 표준화 과정은 이러한 원칙에 따라 **우선 순위를 정리** 해야하며, 그렇게 되지 않을 경우 우선 순위를 재검토 해야합니다.

------

**신규 기본 수준 기능** 표준화와 그러한 관점의 신규 기능에 집중함으로서, 우리는

* 새로운 보안 문제가 생길 수 있는 영역의 최소화를 할 수 있습니다.
* 브라우저 엔진이 앞으로 추가 되는 API에 영향을 주는 핵심 부분 최적화에만 주력할 수 있습니다. 그러면, 작은 구현 비용으로 더 나은 성능을 얻을 수 있습니다.
* 브라우저 벤더와 라이브러리 개발자가 웹 개발자의 요구에 맞는 높은 수준의 API로 라이브러리 개발을 할 수 있습니다.

------

**기본 수준 기능 관점에서** 기존 기능과 앞으로 추가되는 새로운 기능을 설명함으로서, 우리는... 

* 구현 결과의 복잡도를 줄일 수 있고, 그에 따라 버그 발생율을 줄일 수 있습니다.
* 다양한 신규 플랫폼 새로운 기능을 더 많이 제공할 수 있습니다.
* 새로운 기능에 대한 학습 비용을 줄일 수 있습니다. 학습에 필요한 내용도 이미 플랫폼 개념을 바탕으로 쉽게 만들 수 있습니다.

------

신규 기능을 쉽게 이해시키고 **의미있는 피드백 체계**를 여러 방면에 적용함으로서, 우리는...

* 웹 개발자로 하여금 새로운 API를 더 빨리 시도할 수 있고, 표준 사양이 완료되기 전에 플랫폼 변화에 대한 피드백을 보낼 수 있습니다.
* API를 이용하는 웹 개발자와 라이브러리를 제공하는 개발자에 의해 API의 실수는 빠르게 확인되고, 이를 통해 중요한 피드백을 브라우저 벤더와 플랫폼 설계자에게 적절한 시기에 제공 할 수 있습니다.
* 라이브러리 개발자는 새로운 API를 실험하고, 이를 통해 웹 플랫폼이 나아갈 길을 제시할 수 있습니다.

------

이러한 원칙에 따라 **우선 순위를 부여**함으로써, 우리는...

* 보안 및 성능 문제와 함께 기능에 집중하는 (특히 단기적인) 표준 프로세스를 자유롭게 함으로서 새로운 하드웨어 같은 웹 플랫폼 수준에서만 추가되어야 할 기능 표준화에 주력 할 수 있습니다.
* 웹 개발자와 브라우저가 주도하는 라이브러리의 구현 비용에 대한 조사를 이끌 수 있습니다.
* 신규 API 표준화에 대한 장기적 과정을 단순화함으로서, 현실 세계에 중요하게 사용하는 기능을 표준화 할 수 있습니다.

------

우리는 웹 개발자가 더 많은 선언적인 코드를 작성하기를 원합니다. 이를 통해 표준화의 병목 현상을 제거하고, 라이브러리와 프레임 워크의 개발자들에게 팔요한 도구를 제공할 수 있습니다.

개방형 웹과 이를 둘러싼 경쟁자와 경쟁을 위해서는 웹 개발자의 좋은 아이디어를 웹 인프라 구조의 일부로 편입시킬 수 있는 확실한 수단이 필요합니다.

이러한 원칙에 우리는 찬성합니다.

선언문 서명하기(https://docs.google.com/forms/d/1fqaqAjUZR8uDo5l9p1_80-1kt0SFQNJ_fCjiZPNgj4Y/viewform)

서명자 명단(https://docs.google.com/spreadsheet/pub?key=0AtR1SNsaFeH9dGI5eWZQVGNhZWEyQUhtaUw3ZWl1dVE&single=true&gid=0&output=html)



**Brendan Eich**
CTO and SVP Engineering, Mozilla; Creator of JavaScript

**Yehuda Katz**
Member, TC39, W3C TAG; Core Team, Ember.js, Rails

**Alex Russell**
Member, TC39, W3C TAG; Google Chrome Team

**Brian Kardell**
Chair, Extensible Web Community Group, W3C

**François REMY**
Co-founder, Extensible Web Community Group, W3C

**Clint Hill**
Co-founder, Extensible Web Community Group, W3C

**Marcos Caceres**
Co-founder, Extensible Web Community Group, W3C

**Tom Dale**
Core Team, Ember.js

**Anne van Kesteren**
Editor of standards, Architecture Astronaut at Mozilla

**Sam Tobin-Hochstadt**
Member, TC39

**Domenic Denicola**
Co-Editor, Promises/A+

**Chris Eppstein**
Maintainer, Sass

**Dave Herman**
Mozilla Research and TC39

**Alan Stearns**
Member, CSSWG

**Rick Waldron**
Member, TC39; Core Team, jQuery, Bocoup

**Paul Irish**
Google

**Ted Han**
Lead Developer, DocumentCloud

**Tab Atkins**
Member, CSS WG; Google

**Dan Appelquist**
Co-Chair, W3C TAG, Open Web Advocate, Telefónica

**Isaac Schlueter**
Maintainer, Node.js

**Allen Wirfs-Brock**
Mozilla Research Fellow, TC39 Member, Editor of The ECMAScript Specification

-----

**참고 문서**
* [Extend the Web Forward](http://yehudakatz.com/2013/05/21/extend-the-web-forward/) by Yehuda Katz, 본 아이디어의 세부 사항을 설명하는 문서
* [An Extensible Approach to Browser Security Policy](http://yehudakatz.com/2013/05/24/an-extensible-approach-to-browser-security-policy/) by Yehuda Katz, 이러한 방법을 구현한 응용 프로그램으로 브라우저 Content Security Policy의 API 디자인에 대한 문제에 대한 해설
* [Dropping the F-Bomb on Web Standards](https://briankardell.wordpress.com/2013/05/17/dropping-the-f-bomb/) by Brian Kardell, 개발자 커뮤니티에서 나온 아이디어와 표준 언어를 표준에 어떻게 포함 할 것인가에 대한 실질적인 논의.
* [Bedrock](http://infrequently.org/2012/04/bedrock/) by Alex Russell, 2012년에 확장 가능한( "레이어링 된") 디자인에 기반한 플랫폼에 관한 지식과 철학 자세한 조사.
* [How the Web Should Work](http://smus.com/how-the-web-should-work/) by Boris Smus, 2002년에 미래의 다양한 적용(polyfills)을 위한 방법에 대한 제안.
