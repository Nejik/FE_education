Frontend education
===================

# HTML
## Step 1
* DOCTYPE
* What is a tag?
* special meaning of some meta tags (Content-Type, keywords, etc)
* head, title, body
* block elements (div, h*, p, pre)
* inline elements (span, a, b, br, img, ...)
* del, ins
* ul, ol, li, ...
* table, th, td, thead, tbody (cellspacing, cellpadding, colspan, * rowspan)
* a (href, target), absolute or relative links
* article, aside, nav, main, header, footer, mark, section
* figure, figcaption
* video, audio
* form, input (basic types: text, checkbox, radio), select, label
* special characters (&...;)
* common element attributes (events)

Links:

1. HTML & CSS for Beginners, https://www.codecademy.com/en/tracks/htmlcss
2. Уроки по HTML и CSS, https://webref.ru/layout/learn-html-css
3. Самоучитель HTML4, http://htmlbook.ru/samhtml

## Step 2
* meta tag [1, 2]
* base tag
* input (all types)
* canvas element
* understanding of semantic nature of HTML
* HTML document as semantic document
* div vs table markup
* div slicing
* purpose of table (plain data?)
* minimal skill in PhotoShop
* where to place javascript and css files
* inlining of styles and JS code
* adding unexisting tag (document.createElement)

Links:
1. How to use HTML meta tag, https://searchenginewatch.com/sew/how-to/2067564/how-to-use-html-meta-tags
2. Meta tags, http://www.wordstream.com/meta-tags
3. Mike Robinson, Let's Talk about Semantic, http://html5doctor.com/lets-talk-about-semantics/
4. Верстка со смыслом, https://vimeo.com/25823931
5. Избегаем популярных ошибок в HTML5, https://web-standards.ru/articles/avoiding-html5-mistakes/ 
6. Table Layouts vs. Div Layouts: from Hell to... Hell, https://www.smashingmagazine.com/2009/04/from-table-hell-to-div-hell/
7. HTML Best Practices, https://github.com/hail2u/html-best-practices
8. MDN (description of API)

## Step 3
* responsive images
* SEO
  * Microdata
  * RDFa
  * JSON-LD
  * Open Graph Protocol
* Form autofill

Links:
1. Responsive Images 101, http://blog.cloudfour.com/responsive-images-101-definitions
2. Built-in Browser Support for Responsive Images, http://www.html5rocks.com/en/tutorials/responsive/picture-element
3. Microdata, https://en.wikipedia.org/wiki/Microdata_(HTML)
4. RDFa, https://en.wikipedia.org/wiki/RDFa
5. JSON-LD, https://en.wikipedia.org/wiki/JSON-LD
6. Schema.org Vocabulary Official Site, https://schema.org
7. Open Graph Protocol Official Site, http://ogp.me
8. Schema Creator, http://schema-creator.org
9. Sematic HTML for Web Content, http://sixrevisions.com/html/semantic-html-web-content
10. Упрощаем заполнение форм с помощью Autofill, http://frontender.info/checkout-faster-with-Autofill
11. Autofill: чего не знают веб-разработчики, хотя должны знать, https://habrahabr.ru/company/mailru/blog/301840/
* Make form validation fun again / Павел Ловцевич (LOVATA), https://www.youtube.com/watch?v=qd9POgbSuNM
* MDN (description of API)

## Step 4
* accessibility
* understanding of template problem
  * ejs / mustache / ...
  * loop
  * conditions
  * translation

Links:
1. ARIA, https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA
2. How to Use ARIA Effectively with HTML5, http://www.sitepoint.com/how-to-use-aria-effectively-with-html5
3. ARIA Examples, http://heydonworks.com/practical_aria_examples
4. An Overview of JavaScript Template Engines, http://www.sitepoint.com/overview-javascript-templating-engines
5. Client-Side Templating, https://www.smashingmagazine.com/2012/12/client-side-templating
6. An Overview of JavaScript Template Engines, http://www.sitepoint.com/overview-javascript-templating-engines
6. Official template sitesles

# CSS

## Step 1
* @charset, @media, @font-face, @import
* concerns of rules, properties, pseudoclasses, pseudoelements, selectors
* display property
* box model (box-sizing)
* formatting context (float, position, display, overflow*) [3]
* collapsing of margins
* floating elements (float, clear)
* positioning (position, left, top, bottom, right, width, height)
* transform property
* main properties (background*, border*, margin*, padding*, outline*, font*, line-height)
* pseudoclasses (:target, :active, :visited, :focus, :hover, :empty, :enabled, :disable)
* pseudoelements (::first-line, ::first-letter)
* !important
* priority of selectors
* rem, em, px, pt
* CSS recipes
    * vertical alignment
    * horizontal alignment
    * other

Links:
1. Texbook, http://htmlbook.ru/samcss
2. Уроки по HTML и CSS, https://webref.ru/layout/learn-html-css
3. Reference, http://htmlbook.ru/css
4. FAQ, http://htmlbook.ru/faq
5. Understanding Block Formatting Contexts in CSS, http://www.sitepoint.com/understanding-block-formatting-contexts-in-css
6. Centering in CSS: A Complete Guide, https://css-tricks.com/centering-css-complete-guide

## Step 2

* meta tag (viewport) [1]
* pseudoclasses (:first-of-type, :last-child, :first-child, :nth-*, :read-only, :required)
* transition / CSS animation
* content property (::after, ::before)
* media queries [4]
* SVG fonts
* SVG icons
* caching of fonts in local storage [5]
* mobile first approach (media query min... or max...) [6]
* responsive CSS [7]
* cross browser: [8, 9]
  * prefixing
  * normalize.css
  * reset.css
* CSS recipes [10]
* CSS best practices [11, 12]
  * naming
  * structure
  * file separation
  * maintenance
  * reusability
  * #id?
* familiarity with at least one of CSS methodologies: SMACSS, BEM, OOCSS, MCSS
* performance
  * box-shadow
  * border-radius
  * filter
  * transparency
  * transform

Links:
1. Using the Viewport Meta Tag to Control Layout on Mobile Browsers, https://developer.mozilla.org/en/docs/Mozilla/Mobile/Viewport_meta_tag
1. Textbook, http://htmlbook.ru/samcss
1. Reference, http://htmlbook.ru/css
1. Using media queries, https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries
1. Preventing the Perfomance Hit from Custom Fonts, https://css-tricks.com/preventing-the-performance-hit-from-custom-fonts
1. Creating a Mobile-First Responsive Web Design, http://www.html5rocks.com/en/mobile/responsivedesign
1. Web Fundamentals - Design and UI, https://developers.google.com/web/fundamentals/design-and-ui
1. 5 Most Common Browser Compatability Issues, https://www.browseemall.com/Blog/index.php/2014/04/24/5-most-common-browser-compatibility-issues
1. 5 CSS Tricks to Avoid Cross Browser Issues, https://surefirewebservices.com/5-css-tricks-to-avoid-cross-browser-issues
1. Basic CSS recipes, http://htmlbook.ru/faq
1. Советы по использованию media query, https://habrahabr.ru/post/198292
1. CSS: The Good Parts, https://ponyfoo.com/articles/css-the-good-parts
1. Writing Efficient CSS Selectors, http://csswizardry.com/2011/09/writing-efficient-css-selectors
1. Efficiently Rendering CSS, https://css-tricks.com/efficiently-rendering-css
1. Atomic OOBEMITSCSS, http://www.sitepoint.com/atomic-oobemitscss
1. SMACSS, https://smacss.com
1. BEM, https://ru.bem.info
1. OOCSS, https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss
1. MCSS, http://operatino.github.io/MCSS/en

## Step 3
* email HTML
* flex [1]
* advanced knowledge of one of CSS methodologies [2 - 5]
* responsive patterns / resources [6, 7]
* purpose of style guide [8]
* familiarity with different style guides (GitHub) [8, 9]
* performance
  * transform proprety to trigger GPU
  * unused rules (clean CSS)
  * nested selectors / too long selector
  * reduce loading while scrolling (pointer-events)

Links:
1. По-настоящему адаптивные письма, https://habrahabr.ru/post/262427
2. A Complete Guide to Flexbox, https://css-tricks.com/snippets/css/a-guide-to-flexbox
3. Практическое применение FlexBox, https://habrahabr.ru/post/242545/
4. SMACSS, https://smacss.com
5. BEM, https://ru.bem.info
5. OOCSS, https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss
6. MCSS, http://operatino.github.io/MCSS/en
7. Responsive Patterns, http://bradfrost.github.io/this-is-responsive/patterns.html
8. Responsive Resources, http://bradfrost.github.io/this-is-responsive/resources.html
9. Style guide articles, http://styleguides.io/articles.html
10. GitHub style guide, http://primercss.io

## Step 4
* purpose of CSS pre / post processors
* less / SASS / postcss
  * definition of nested rules
  * mixins
  * extension
  * variables (scope)
  * number / string operations
  * default functions to work with numbers, strings, colors
  * variable selector / property names
  * string templating
  * merging of property values
  * refer to parent selector
  * compile tool
  * default functions (be familiar to all functions)
  * parameter mixins
  * conditional mixins
  * custom functions / functional expressions
  * loops / conditions
  * best practices
* advantages / disadvantages of CSS frameworks (bootstrap / foundation / materialui)
  * grid system (fixed and fluid grids)
  * typography
  * tables
  * forms
  * buttons
  * images
  * helpers
  * responsive utilities
  * glyphs
  * components
    * tabs
    * labels
    * groups
    * pagination
    * popup
    * accordion
    * breadcrumb

Links:
1. Less reference, http://lesscss.org/features (only relevant topics)
2. SASS Reference http://sass-lang.com/documentation/file.SASS_REFERENCE.html (only relevant topics)
3. PostCSS, http://postcss.org
4. Official Bootstrap documentation, http://getbootstrap.com/css
5. Official Foundation documentation, http://foundation.zurb.com/sites/docs
6. Material ui, http://www.material-ui.com/
7. Discussing the Pros and Cons of Using a CSS Framework, http://speckyboy.com/2011/03/14/discussing-the-pros-and-cons-of-using-a-css-framework
8. The Pros and Cons of CSS Framework, http://vanseodesign.com/css/css-frameworks-pros-cons

# JS

## Step 1
* keywords - control statements - logical operators (== vs ===, && and ||)
* types
* scope
* array (basic methods)
* string (basic methods)
* functions (variable context, arguments, order of definition, variants of declaration, nesting, apply and call functions, scope)
* basic understanding of closure concern (function with variables)
* understanding of callback concern
* basic understanding of new and this keywords
* basic methods of Object
* RegExp
* Date, Number, Boolean, String functions
* primitive vs object nature of basic types
* typeof
* setTimeout, setInterval
* comments

Links:

1. JavaScript Course, https://www.codecademy.com/learn/javascript
2. JavaScript Course in Russian, https://learn.javascript.ru (until closure theme)
4. Cody Lindley, JavaScript Englightenment, http://www.javascriptenlightenment.com
5. Eloquent JavaScript, http://eloquentjavascript.net/ (until "Modules")
6. MDN, https://developer.mozilla.org (for description of API) 

## Step 2
* array (functional methods)
* prototype chain (prototypical inheritance)
* instanceof, in
* plain objects, object as dictionary
* promises (chain of promises)
* advanced understanding of closure ([[scope]], lexical and variable environments)
* closure pitfalls (memory leaks)
* high order function concept
* Function.bind
* Object.defineProperty (defineProperties)
* try...catch
* understanding of code quality
* patterns [4]: 
* general patterns
  * literals and constructors patterns
  * function patterns
  * object creation patterns
* debugging

Links:
1. https://learn.javascript.ru (starting from closures)
2. Douglas Crockford, JavaScript: The Good Parts
3. MDN, https://developer.mozilla.org (for description of API)
4. JavaScript Patterns Collection, http://shichuan.github.io/javascript-patterns (for patterns description

## Step 3

* OOP class system
* difference between prototypical inheritance and OOP approach
* inheritance vs delegation
* functional approaches (immutability, pure functions, function composition)
* patterns [3, 4 (optional)]
* code reuse patterns
* design patterns
* performance
* engine performance issues [2]
* performance of functional approach
* managing hell [5]

Links:
1. Michael Fogus, Functional JavaScript, parts 1 - 8
2. Addy Osmani, Writing fast Memory Efficient JavaScript, https://www.smashingmagazine.com/2012/11/writing-fast-memory-efficient-javascript
3. JavaScript Patterns Collection, http://shichuan.github.io/javascript-patterns
4. (optional) Addy Osmani, Learning JavaScript Design Patterns, https://addyosmani.com/resources/essentialjsdesignpatterns/book/index.html
5. Marc Harter, Managing Node.js Hell with Promises, Generators and Other Approaches, https://strongloop.com/strongblog/node-js-callback-hell-promises-generators
6. (optional) Nicholas C. Zakas, High Performance JavaScript

## Step 4

* understanding when it is convenient to use prototypical inheritance
* alternatives for OOP and prototypical inheritance approaches
* advantages / disadvantages of OOP approach
* advantages / disadvantages of functional approach
* plain module
* understanding of following concerns
  * UMD
  * AMD
    * definition and usage of module
    * configuration of loader
    * plugins
    * web-based
  * common.js
    * definition and usage of module
    * build tool


Links:
1. Michal Fogus, Functional JavaScript, part 9 - till the end
2. Functional Programming in JavaScript, http://owenyang0.github.io/2015/04/12/functional-programming-in-javascript/
3. Mastering the Module Pattern, https://toddmotto.com/mastering-the-module-pattern
4. Writing Modular JavaScript, https://addyosmani.com/writing-modular-js

# Browser
* window object, document, navigator, location [1]
* DOM manipulation methods [2, 6, 7]
* querySelector / querySelectorAll [2, 6, 7]
* add / remove event listener [3, 6, 7]
* event structure (source, target) [6, 7]
* event bubbling and capturing [3]
* event types (mouse, keyboard, input, whell, scroll, touch) [4]
* creation of event (createEvent, initEvent) [6, 7]
* XmlHttpRequest [5]
* console API [6]
* getComputedStyle() [6]

* feature detection vs sniffing [10, 11]
* document fragment [12]
* File / FileList / FileReader [13]
* xhr2 / fetch API [14]
* FormData [14]
* WebStorage API [15, 16]
* cookie API
* history API [17, 18]
* hash (hash change event, influence on routing, change of hash) [19]
* technique of routing based on hash / history API [19]
* requestAnimationFrame [20]
* setTimeout, setInterval [21]
* Data URL (create, free) [22, 23]
* promises (browser-specific) [24]
* script loading options (sync, async, defer) [25]
* purpose of polyfill [26]
* nature [27]
  * main loop
  * non blocking actions
  * unloading of main loop (setTimeout)
* purpose of some headers [28]
  * Content-Type
  * Origin
  * Cookie
  * Set-Cookie
  * User-Agent
  * Accept-Language
  * Referer
* Worker API [30]
  * unloading of main loop (background jobs, transferrable)
* cross-browser issues (caniuse.com, MDN)
* performance problems 31
  * DOM manipulation
  * XHR calls
  * many JS/CSS files
  * responsiveness of actions (slow action handling)
* purpose of some headers [32]
  * ETag
  * Last-Modified
  * Cache
  * Cache-Control
  * Expires
* technique of inlining images [33]
* PageSpeed [34]
* optimizing of critical path [35, 36]
* nature [37]
  * browser render cycle
  * reflow
  * when browser loads a page (in advance)
  * caching (how does browser do this?)
  * browser internals
  * triggering of GPU for UI rendering (pros/cons)

Links:
1. JavaScript Course in Russian, https://learn.javascript.ru (Document, Events, Interfaces)
2. MDN - Window, https://developer.mozilla.org/en-US/docs/Web/API/Window
3. Eloquent JavaScript, http://eloquentjavascript.net/ (from "JavaScript and the Browser" to "Node.js")
4. You might not need jQuery, http://youmightnotneedjquery.com
5. Event Capturing and Bubbling in JavaScript, https://www.kirupa.com/html5/event_capturing_bubbling_javascript.htm
6. MDN - event reference, https://developer.mozilla.org/en-US/docs/Web/Events
7. XmlHttpRequest, http://www.w3schools.com/xml/dom_http.asp
8. MDN (description of API)
9. W3 Schools, http://www.w3schools.com
10. Browser and Feature Detection, http://www.htmlgoodies.com/html5/client/browser-and-feature-detection-make-your-website-look-great-everywhere..html#fbid=PizJ6eQpj1n
11. How to Detect Features instead of Browsers, http://www.htmlgoodies.com/html5/client/browser-and-feature-detection-make-your-website-look-great-everywhere..html#fbid=PizJ6eQpj1n
12. DOM Document Fragments, http://ejohn.org/blog/dom-documentfragments
13. Reading Files in JavaScript using File APIs, http://www.html5rocks.com/en/tutorials/file/dndfiles
14. New Tricks in XmlHttpRequest2, http://www.html5rocks.com/en/tutorials/file/xhr2
15. Using the WebStorage API, https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API
16. HTML5 Web Storage, http://www.sitepoint.com/html5-web-storage
17. Using the HTML5 History API, https://css-tricks.com/using-the-html5-history-api
18. Manipulating the Browser History, https://developer.mozilla.org/en-US/docs/Web/API/History_API
19. Must Know URL Hash Techniques for AJAX applications, http://blog.mgm-tp.com/2011/10/must-know-url-hashtechniques-for-ajax-applications
20. Using requestAnimationFrame, https://css-tricks.com/using-requestanimationframe
21. Understanding timers: setTimeout  and setInterval, http://javascript.info/tutorial/settimeout-setinterval
22. Data URIs, https://css-tricks.com/data-uris
23. Using Object URLs, https://developer.mozilla.org/en-US/docs/Using_files_from_web_applications#Example_Using_object_URLs_to_display_images
24. JavaScript Promises, http://www.html5rocks.com/en/tutorials/es6/promises
25. Async Attribute and Scripts at the bottom, https://css-tricks.com/async-attribute-scripts-bottom
26. Polyfill, https://en.wikipedia.org/wiki/Polyfill
27. How Browsers Work, http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/
28. List of HTTP header fields, https://en.wikipedia.org/wiki/List_of_HTTP_header_fields
29. MDN (description of API)
30. The Basics of Web Workers, http://www.html5rocks.com/en/tutorials/workers/basics/
31. Top 10 Client-Side Performance Problems in Web 2.0, http://apmblog.dynatrace.com/2010/08/25/top-10-client-side-performance-problems-in-web-2-0/
32. List of HTTP header fields, https://en.wikipedia.org/wiki/List_of_HTTP_header_fields
33. Inline Images with Data URLs, http://www.websiteoptimization.com/speed/tweak/inline-images/
34. Make the Web Faster, https://developers.google.com/speed/
35. Optimize the Critical Rendering Path, http://www.sitepoint.com/optimizing-critical-rendering-path/
36. Critical Rendering Path, https://developers.google.com/web/fundamentals/performance/critical-rendering-path/
37. Ускоряем загрузку ресурсов для сайта, https://ymatuhin.ru/front-end/html5-link-prefetch
38. How Browsers Work, http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/
39. MDN (description of API)


# Workflow

* Developer Tools
* node.js
  * node.js module system (common.js, import, export)
  * node.js module resolvement
  * node_modules
  * versioning
  * package.json
    * name
    * version
    * dependencies
    * devDependencies
    * scripts
    * private
  * npm
    * npm init
    * npm install <arguments> (--save, --save-dev, -g, <module name>)
    * npm uninstall
    * npm link
    * npm update
    * npm outdated
    * npm ls
    * npm run
    * npm test
    * npm start
* gulp build system
  * gulp cli
  * Gulpfile.js
  * streaming description
  * gulp.task
  * async tasks
  * gulp.src and gulp.dest
  * pipe
  * compound tasks (aliasing)
  * watching
  * integration of 3rd party gulp plugins


Links:
1. JS Debugging, http://www.w3schools.com/js/js_debugging.asp
1. Editing Styles and the DOM, https://developer.chrome.com/devtools/docs/dom-and-styles
1. Inspect and Edit Page and Styles, https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles
1. Developer tools gif tips, https://umaar.com/dev-tips/
1. Debugging JavaScript, https://developer.chrome.com/devtools/docs/javascript-debugging
1. Dev Tools: Debug, https://developers.google.com/web/tools/chrome-devtools/debug
1. Dev Tools: Resources, https://developers.google.com/web/tools/chrome-devtools/iterate/manage-data/?hl=en
1. Command Line API Reference, https://developer.chrome.com/devtools/docs/commandline-api
1. How to use Chrome Dev Tools Like a Pro, https://medium.com/jotform-form-builder/how-to-use-chrome-devtools-like-a-pro-b9bd414870e3
1. Talk: Tooling the Webapp Development Stack, http://www.paulirish.com/2012/talk-tooling-the-webapp-development-stack
1. Dev Tools Shortcuts, https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/shortcuts
1. Dev Tools: Device Mode, https://developers.google.com/web/tools/chrome-devtools/iterate/device-mode
1. Dev Tools: Profile, https://developers.google.com/web/tools/chrome-devtools/profile (without Fix Memory Problems theme)
1. Dev Tools: Security, https://developers.google.com/web/tools/chrome-devtools/security
2. Node.js, https://nodejs.org/dist/latest-v8.x/docs/api/
2. Node.js Tutorial, http://www.tutorialspoint.com/nodejs
2. npm: package.json, https://docs.npmjs.com/files/package.json
2. npm: getting started, https://docs.npmjs.com/getting-started/what-is-npm
2. Debugging node.js application, https://github.com/node-inspector/node-inspector
3. Gulp: Getting Started, https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md
3. Gulp: API, https://github.com/gulpjs/gulp/blob/master/docs/API.md
4. Gulp: CLI, https://github.com/gulpjs/gulp-cli