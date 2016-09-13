The Extensible Web Manifesto
============================

We—the undersigned—advocate a change to the approach that web standards committees use to create and prioritize new features. We believe that this is critical to the long-term health of the web.

Our primary goal is to tighten the feedback loop between the editors of web standards and web developers. We prefer an evolutionary model of standardization, driven by the vast army of web developers, to a top-down model of progress driven by standardization.

Browser vendors should provide new low-level capabilities that expose the possibilities of the underlying platform as closely as possible. They should seed the discussion of high-level APIs through JavaScript implementations of new features (as done in the cases of [Microsoft’s X-Tags](https://x-tag.github.io/) and [Google’s Polymer](https://www.polymer-project.org/)). This involves web developers in the process, and, by iterating outside of the browser, the platform avoids getting stuck with bad APIs.

Specifically, we offer the following design principles for an Extensible Web Platform:
* The standards process should focus on adding ***_new low-level capabilities_*** to the web platform that are secure and efficient.
* The web platform should expose low-level capabilities that ***_explain existing features_***, such as HTML and CSS, allowing authors to understand and replicate them.
* The web platform should develop, describe, and test new high-level features in JavaScript, while allowing web developers to iterate on them before they become standardized. This creates a ***_virtuous cycle_*** between standards and developers.
* The standards process should ***_prioritize efforts_*** that follow these recommendations; efforts that do not should be deprioritized and refocused.

------

By focusing on standardizing ***_new low-level capabilities_***, and building new features in terms of them, we:
* Contain new security surface area.
* Allow optimizations in browser engines to focus on the stable core, which during implementation can positively affect other APIs', leading to better performance with less implementation effort.
* Allow browser vendors and library authors to iterate on libraries that provide developer-friendly, high-level APIs.

By explaining existing and new features ***_in terms of low-level capabilities_***, we:
* Reduce the rate of growth in complexity, and therefore bugs, in implementations.
* Make it possible to polyfill more of the platform's new features.
* Require less developer education for new features. Educational materials can build off of concepts already present in the platform.

Making new features easy to understand and polyfill introduces a ***_virtuous cycle_***:
* Developers can ramp up more quickly on new APIs, providing quicker feedback to the platform while the APIs are still the most malleable.
* Mistakes in APIs can be corrected quickly by the developers who use them and library authors who serve them, providing high-fidelity, critical feedback to browser vendors and platform designers.
* Library authors can experiment with new APIs and create more ["cow paths"](https://en.wikipedia.org/wiki/Desire_path) for the platform to pave.

By ***_prioritizing efforts_*** that follow these principles, we:
* Free up the standards process (especially in the short term) to focus on features with security or performance concerns and features that can be added at only the platform level, such as new hardware.
* Allow web developers and browser-initiated libraries to take the lead in costly explorations.
* Simplify and streamline the longer-term process of standardizing new APIs, which will already have implementations and significant real-world usage.


We want web developers to write more declarative code, not less. This calls for eliminating the standards bottleneck to introducing new declarative forms, giving library and framework authors the tools to create them.


In order for the open web to compete with its walled competitors, there must be a clear path for good ideas by web developers to become part of the infrastructure of the web. We must enable web developers to build the future web.


In support of these principles,

* Brendan Eich <br>
CTO and SVP Engineering, Mozilla; Creator of JavaScript

* Yehuda Katz <br>
Member, TC39, W3C TAG; Core Team, Ember.js, Rails

* Alex Russell <br>
TC39, W3C TAG; Google Chrome Team

* Brian Kardell <br>
Chair, Extensible Web Community Group, W3C

* François REMY <br>
Co-founder, Extensible Web Community Group, W3C

* Clint Hill <br>
Co-founder, Extensible Web Community Group, W3C

* Marcos Caceres <br> 
Co-founder, Extensible Web Community Group, W3C

* Tom Dale <br>
Core Team, Ember.js

* Anne van Kesteren <br>
Editor of standards, Architecture Astronaut at Mozilla

* Sam Tobin-Hochstadt <br>
Member, TC39

* Domenic Denicola <br>
Co-Editor, Promises/A+

* Chris Eppstein <br>
Maintainer, Sass

* Dave Herman <br>
Mozilla Research and TC39

* Alan Stearns <br>
Member, CSSWG

* Rick Waldron <br>
Member, TC39

* Paul Irish <br>
Google

* Ted Han <br>
Lead Developer, DocumentCloud

* Tab Atkins <br>
Member, CSS WG; Google

-----

**Related Reading**
* [Extend the Web Forward](http://yehudakatz.com/2013/05/21/extend-the-web-forward/), by Yehuda Katz, which fleshes out more these ideas more.
* [An Extensible Approach to Browser Security Policy](http://yehudakatz.com/2013/05/24/an-extensible-approach-to-browser-security-policy/), by Yehuda Katz, which presents a practical application of these principles to the problem of designing an API for the browser's [Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/Security/CSP).
* [Dropping the F-Bomb on Web Standards](https://briankardell.wordpress.com/2013/05/17/dropping-the-f-bomb/), by Brian Kardell, a practical discussion of how ideas and language from the developer community can be integrated back into interoperable standards.
* [Bedrock](https://infrequently.org/2012/04/bedrock/), by Alex Russell, a 2012 post that explores in depth the philosophy and practice of designing the platform in an extensible ("layered") way.
