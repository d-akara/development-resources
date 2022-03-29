# Web Tech

## Testing and Code Quality

[Overview JS Testing 2019](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2019-264e19514d0a)

* [jest](https://github.com/facebook/jest) unit testing, automatic mocking, parallel execution using workers [discussion](https://news.ycombinator.com/item?id=12629743), [discussion2](https://news.ycombinator.com/item?id=13128146)
    * [VS Code Plugin](https://github.com/orta/vscode-jest) live test running in editor
* [intern](https://github.com/theintern/intern) complete JavaScript software testing system
* [cypress](https://www.cypress.io/) $ future.  innovative advanced automated testing framework
* [wallaby](https://wallabyjs.com/) $ realtime test runner with editor integration
* [AVA](https://github.com/avajs/ava) futuristic test runner
* [playwright](https://github.com/microsoft/playwright) Next evolution beyond Puppeteer
* [testcafe](https://github.com/DevExpress/testcafe) cross platform, cross browser automation without need of WebDriver
* [appium](http://appium.io/) test/automate iOS, Android, and Windows apps using the WebDriver protocol
* [codecept](http://codecept.io/) scenario acceptance testing BDD
* [stylelint](http://stylelint.io/) Enforce best practices for stylesheets
* [eslint](http://eslint.org/) Enforce best practices for JavaScript
    * [eslint-plugin-compat](https://github.com/amilajack/eslint-plugin-compat) Add browser compatibility linting
* [nyc](https://github.com/bcoe/nyc) improvements built on instanbul coverage tool
* [chai](https://github.com/chaijs/chai) BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Sinon.js](http://sinonjs.org/) Standalone test spies, stubs and mocks for JavaScript
* [WireMock](http://wiremock.org/) advanced server side mocking
* [MSW](https://github.com/mswjs/msw) Mock Service Worker API mocking library for browser and Node.js.

## Low level libraries
* [lodash](https://lodash.com/) General utility library performance focused with FP concepts
* [callbag](https://github.com/staltz/callbag-basics) Tiny and fast reactive/iterable programming library. [Callbags](https://github.com/callbag/callbag/wiki)
* [lazy](https://github.com/dtao/lazy.js) Similar to lodash, but with all lazy evaluation
* [stdlib](https://github.com/stdlib-js/stdlib) Standard library for JavaScript and Node.js
* [FPO](https://github.com/getify/fpo) Functional library using named arguments
* [Immutable](http://facebook.github.io/immutable-js/) Fast immutable collection library
* [Crio](https://github.com/planttheidea/crio) Immutable library compatible with other collection libraries
* [Collections](https://github.com/montagejs/collections) common data structures with idiomatic interfaces
* [Collect.js](https://github.com/ecrmnn/collect.js) array and object collection wrapper
* [mnemonist](https://github.com/Yomguithereal/mnemonist) JS data structures
* [Mindex](https://github.com/internalfx/mindex) Fast javascript compound index
* [Iterall](https://github.com/leebyron/iterall) Iterate over any collection
* [Iterare](https://github.com/felixfbecker/iterare) iterate over collections performing efficient transformation pipelines
* [P-Iteration](https://github.com/toniov/p-iteration) iterate over promises using array functions
* [Moize](https://github.com/planttheidea/moize) Fast memoize function
* [MobX](https://github.com/mobxjs/mobx) State management by transparently applying functional reactive programming (TFRP) [Discussion MobX Redux](https://news.ycombinator.com/item?id=11181980) - [MobX vs Redux](https://discuss.reactjs.org/t/redux-or-mobservable-what-to-choose/2453) - [Formidable article](http://formidable.com/blog/2016/06/02/why-we-chose-mobx-over-redux-for-spectacle-editor/)
    * [discussion](https://news.ycombinator.com/item?id=12629301)
* [Redux](https://github.com/reactjs/redux) State container
* [Most](https://github.com/cujojs/most/) ultra-high performance monadic reactive streams
* [optika](https://github.com/phadej/optika) optics for JavaScript.  Functional Programming
* [construct-js](https://github.com/francisrstokes/construct-js) declaritive library for creating byte level data structures
* [structurae](https://github.com/zandaqo/structurae) Fast data structures, Grid, BitField, Pool, Array
* [FastBitSet](https://github.com/lemire/FastBitSet.js) Speed-optimized BitSet implementation
* [Uint1Array](https://github.com/crislin2046/Uint1Array) bitfields in JS with TypeArray syntax
* [indexed-bitfield](https://github.com/mafintosh/indexed-bitfield) Indexed bitfield that allows you to search for bits efficiently
* [sparse-bitfield](https://github.com/mafintosh/sparse-bitfield) allocates a series of small buffers to support sparse bits without allocating a massive buffer
* [Rbush](https://github.com/mourner/rbush) high-performance JavaScript R-tree-based 2D spatial index for points and rectangles
* [SystemJS](https://github.com/systemjs/systemjs) Loader which supports all module formats and can load dynamically at runtime
* [Lozad](https://github.com/ApoorvSaxena/lozad.js) uses intersection observer to more efficiently load resources
* [transducers-js](https://github.com/cognitect-labs/transducers-js) Composable algorithmic transformations
* [transducers.js](https://github.com/jlongster/transducers.js) Composable algorithmic transformations.  [Tranducers performance](http://jlongster.com/Transducers.js-Round-2-with-Benchmarks)
* [Sequency.js](https://github.com/winterbe/sequency) Lazy object streaming pipeline for JavaScript inspired by Kotlin
* [RxJS](https://github.com/Reactive-Extensions/RxJS) Observables + Operators + Schedulers
* [JS-interpreter](https://github.com/NeilFraser/JS-Interpreter) sandboxed JavaScript interpreter in JS
* [expressions-js](https://github.com/chip-js/expressions-js/blob/master/src/expressions.js) simplified JavaScript expressions into executable functions
* [zone.js](https://github.com/angular/angular/tree/master/packages/zone.js) JavaScript concept of thread local context
* [nlp-compromise](https://github.com/nlp-compromise/nlp_compromise) NLP JavaScript library
* [core-js](https://github.com/zloirock/core-js#supported-engines) Polyfills of ES6+ for older JavaScript engines.
* [cuid](https://github.com/ericelliott/cuid) Collision-resistant ids optimized for horizontal scaling and performance
* [ulid](https://github.com/ulid/javascript) Universally Unique Lexicographically Sortable Identifier
* [stamp-it](https://github.com/stampit-org/stampit/) Composable object factories
* [MixWith](https://github.com/justinfagnani/mixwith.js) Composable classes with [mixins](http://justinfagnani.com/2015/12/21/real-mixins-with-javascript-classes/)
* [DOMPurify](https://github.com/cure53/DOMPurify) XSS sanitizer for HTML, MathML and SVG
* [stacktrace.js](https://www.stacktracejs.com/) Generate, parse, and enhance JavaScript stack traces in all web browsers
* [hash-it](https://github.com/planttheidea/hash-it) Create hash for any JS object
* [deePool](https://github.com/getify/deePool) JS object pool
* [VocaJS](https://vocajs.com/) JS String library
* [broadcast-channel](https://github.com/pubkey/broadcast-channel) broadcast channel for New Browsers, Old Browsers, WebWorkers and NodeJs
* [Swivel](https://github.com/bevacqua/swivel) Communication channels across pages using service worker
* [across-tables](https://github.com/wingify/across-tabs) Communcation across cross origin pages
* [Postal](https://github.com/postaljs/postal.js) message bus library
* [post-robot](https://github.com/krakenjs/post-robot) Posting across domains in browser pages
* [post-me](https://github.com/alesgenova/post-me/) Communicate with web Workers and other Windows using a simple Promise based API
* [Automerge](https://github.com/automerge/automerge) JSON-like data structure that can be modified concurrently and merged again automatically.
* [html-differ](https://github.com/markedjs/html-differ) library to diff html changes
* [htmldiff](https://github.com/idesis-gmbh/htmldiff.js) library to diff html changes
* [jsDiff](https://github.com/kpdecker/jsdiff) text diff library
* [paste.js](https://github.com/layerssss/paste.js) cross browser image pasting from clipboard
* [pampy.js](https://github.com/santinic/pampy.js) Pattern matching
* [fast-copy](https://github.com/planttheidea/fast-copy) A blazing fast deep object copier
* [file-type](https://github.com/sindresorhus/file-type#supported-file-types) detect file type

### Networking
* [simple-peer](https://github.com/feross/simple-peer) WebRTC video/voice and data channels
* [axios](https://github.com/mzabriskie/axios) Promise based HTTP client for the browser and node.js
* [robust-websocket](https://github.com/appuri/robust-websocket) reconnecting websockets

### Asynchronous and Threading
* [threads.js](https://github.com/andywer/threads.js) Make web workers & worker threads as simple as a function call
* [Async](https://github.com/caolan/async) Async utilities for node and the browser
* [Promise-worker](https://github.com/nolanlawson/promise-worker) Communicate with a Web Worker using Promises
* [Operative](https://github.com/padolsey/operative) run code inline within a web worker
* [thaw.js](http://robertleeplummerjr.github.io/thaw.js/) synthetic asynchronous processing
* [posterus](https://github.com/Mitranim/posterus) Composable async primitives (futures) with true cancelation, control over scheduling, and coroutines
* [Task.js](https://github.com/icodeforlove/task.js/) Distribute across workers for Node and Web
* [greenlet](https://github.com/developit/greenlet) run async function in a web worker
* [workerize](https://github.com/developit/workerize) run a module in a web worker
* [comlink](https://github.com/GoogleChromeLabs/comlink) auto proxy to web worker

### Parsing and Serialization
* [struct-fu](https://github.com/natevw/struct-fu) Convert between JSON objects and binary buffer data according to a given field layout/structure declaration.  Can handle bitfields.
* [struct](https://github.com/xdenser/node-struct) Creates a proxy view into a buffer based on a struct definition.  No bitwise data
* [corrode](https://github.com/screeny05/corrode) library for reading binary data
* [lave](https://github.com/jed/lave) Stringify serialize any JS object
* [devalue](https://github.com/Rich-Harris/devalue) serialize JSON with XSS safe escapes
* [oboe.js](https://github.com/jimhigson/oboe.js) Streaming approach to JSON.  Similar to SAX
* [Arquero](https://github.com/uwdata/arquero) library for query processing and transformation of array-backed data tables
* [PapaParse](https://github.com/mholt/PapaParse) CSV parser, streaming, worker thread
* [Transit-js](https://github.com/cognitect/transit-js) Fast serialization superset of JSON
* [SJS](https://github.com/lucagez/slow-json-stringify) Fast JSON stringify using schema
* [jsan](https://github.com/kolodny/jsan) handles circular references with JSON
* [flatted](https://github.com/WebReflection/flatted#flatted) handle circular JSON
* [MessagePack](https://msgpack.org/index.html) cross platform fast, small binary data serialization. Good drop in replacement for JSON. [review article](https://yuhui-lin.github.io/blog/2017/08/01/serialization)
* [FlatBuffers](https://github.com/google/flatbuffers) cross platform fast serialization for networking and storage.  [review article](https://yuhui-lin.github.io/blog/2017/08/01/serialization)
* [chevrotain](https://github.com/SAP/chevrotain) Fast parser DSL, no code generation.  Performance [comparison](https://sap.github.io/chevrotain/performance/)
* [PEG.js](http://pegjs.org/) Parser generator based on parsing expression grammar
* [nearly.js](https://nearley.js.org/) can handle any grammar you can define in BNF (and more!) using [Nearly](https://en.wikipedia.org/wiki/Earley_parser) algorithm
* [Arcsecond](https://github.com/francisrstokes/arcsecond) Fantasy Land compliant javascript Parser Combinator library largely inspired by Haskell's Parsec.  [Introduction](https://hackernoon.com/arcsecond-parsing-in-javascript-made-easy-af1894bdcec9)
* [Ohm](https://github.com/cdglabs/ohm) library and language for building parsers, interpreters, compilers, etc. [Intro article](https://www.pubnub.com/blog/2016-08-30-javascript-parser-ohm-makes-creating-a-programming-language-easy/)
* [Cheerio](https://cheerio.js.org/) server side HTML and XML fast parser.  Uses CSS Selector paradigm like jQuery. [htmlparser2](https://github.com/fb55/htmlparser2) as parsing engine
* [jsdom](https://github.com/jsdom/jsdom) HTML/XML parser and browser API's. Uses [parse5](https://github.com/inikulin/parse5) for HTML and [saxes](https://github.com/lddubeau/saxes) for XML 
* [xmldom](https://github.com/jindw/xmldom) JS XML DOM and internal parser.  
* [xpath](https://github.com/goto100/xpath) XPath 1.0 works with jsdom, xmldom, slimdom
* [fotoxpath](https://github.com/FontoXML/fontoxpath) XPath 3.1 works with jsdom, xmldom, slimdom
* [saxes](https://github.com/lddubeau/saxes) XML parser enforces well formed XML.  [slimdom-sax-parser](https://github.com/wvbe/slimdom-sax-parser) provides a DOM built using saxes
* [htmlparser2](https://github.com/fb55/htmlparser2) very fast streaming HTML/XML NodeJS parser, but non-strict
* [domino](https://github.com/fgnass/domino) W3C DOM Level 4 HTML parser
* [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) Validate XML, Parse XML to JS/JSON and vise versa.  Uses regex as parser.
* [js-yaml](https://github.com/nodeca/js-yaml) JS YAML parser/serializer

### Data Search and Validate
* [JMESPath](http://jmespath.org/) query language for JSON
* [JSONata](https://github.com/jsonata-js/jsonata) JSON query and transformation language
* [is.js](https://github.com/arasatasaygin/is.js) Data type and data format testing functions
* [Validate.js](http://validatejs.org/) declaritive validation of JavaScript objects
* [SuperStruct](https://github.com/ianstormtaylor/superstruct) composable JavaScript validation
* [Luxon](https://github.com/moment/luxon) A modern browser version of Moment
* [date-fns](https://date-fns.org/) large collection of date functions
* [xtype.js](http://xtype.js.org/overview) data validation for JavaScript
* [VerbalExpressions](https://github.com/VerbalExpressions/JSVerbalExpressions) Regular expressions in plain english
* [XRegExp](https://github.com/slevithan/xregexp) Extended regular expression support
* [Rex](https://github.com/areknawo/rex) Regex verbose API
* [super-expressive](https://github.com/francisrstokes/super-expressive) build regular expressions in almost natural language
* [ElasticLunr](http://elasticlunr.com/) Lightweight full-text search engine in Javascript for browser search and offline search
* [fuzzysort](https://github.com/farzher/fuzzysort) sublime like pattern matching
* [fuse](https://github.com/krisk/fuse/) Lightweight fuzzy-search
* [flexsearch](https://github.com/nextapps-de/flexsearch) fastest and most memory efficient full text search library

### Analytics, AI Learning
* [brain.js](https://github.com/BrainJS/brain.js) library of Neural Networks written in JavaScript.

## Persistence
* [LokiJS](https://github.com/techfort/LokiJS) A fast, in-memory document-oriented datastore for node.js, browser and cordova
* [RethinkDB](http://rethinkdb.com/) realtime web pushes JSON to your apps [status?](https://news.ycombinator.com/item?id=12649414)
* [localForage](https://localforage.github.io/localForage/) Local storage library for browsers IndexDB and WebSQL
* [Dexie](http://dexie.org/) Local storage IndexDB wrapper library
* [ClickHouse](https://clickhouse.yandex/) Extremely fast columnar DB [discussion](https://news.ycombinator.com/item?id=11908254)
* [MonetDB](https://www.monetdb.org/blog/monetdb-embraces-nodejs) columnar DB with native NodeJS support [discussion](https://news.ycombinator.com/item?id=11896105)
* [RXDB](https://github.com/pubkey/rxdb) Reactive Offline-first Database with Sync, Schema, Mongo-Query, Encryption, LevelDown
* [knex.js](https://knexjs.org/) SQL query builder for Postgres, MSSQL, MySQL, MariaDB, SQLite3, Oracle, and Amazon Redshift. [DB2](https://github.com/henryjw/knex-db2)
* [remoteStorage.js](https://github.com/remotestorage/remotestorage.js) library for storing user data locally in the browser, as well as connecting to remoteStorage servers such as dropBox and Google Drive
* [gun](https://github.com/amark/gun) realtime, decentralized, offline-first, mutable graph database engine
* [ipfs](https://github.com/ipfs/js-ipfs) JavaScript implementation of the IPFS protocol
* [prisma](https://www.prisma.io/) toolkit for PostgreSQL, MySQL, SQL Server, and SQLite.  Very positive [opinions](https://news.ycombinator.com/item?id=26887724)

## Application Framework
[Flux, Redux, Behavior-Event-State-Tree, Model-View-Update, Model-View-Intent, Nested Dialogues](http://staltz.com/unidirectional-user-interface-architectures.html)

* [Remix](https://github.com/remix-run/remix) full stack web framework that lets you focus on the user interface
* [Meteor](https://github.com/meteor/meteor) Fast application development
* [Cycle.js](http://cycle.js.org/) Functional reactive framework built around RxJS.  Very small codebase.  [Differences Cycle, React, Elm](https://www.reddit.com/r/javascript/comments/3zr6i0/conversation_whats_the_core_differences_between), [CycleJS Talk, good overview of functional and reactive concepts](https://www.youtube.com/watch?v=31URmaeNHSs)
* [Apollo](http://www.apollostack.com/) manages the flow of data between clients and backends. Based on [GraphQL](https://css-tricks.com/declarative-data-fetching-graphql/)
    * [discussion positive](https://news.ycombinator.com/item?id=12629350)
    * [discussion of concerns](https://twitter.com/tomdale/status/786954892342681600)
* [Relay](https://facebook.github.io/relay/) manages the flow of data between clients and backends. Based on GraphQL
    * [discussion and resource references for both Relay and Apollo](https://news.ycombinator.com/item?id=12703125)
* [JSON API](http://jsonapi.org/implementations/#client-libraries-javascript) Alternative to REST and GraphQL.  Need to further assess implementations
* [workbox](https://workboxjs.org/) JavaScript Libraries for Progressive Web Apps
    

## View libraries
[Performance comparison](https://krausest.github.io/js-framework-benchmark/index.html)
* [React](https://github.com/facebook/react) Virtual DOM with one-way reactive data flow. [Composition best practice](https://discuss.reactjs.org/t/best-practices-for-extending-subclassing-components/1820) - [mixins and HOC](https://facebook.github.io/react/blog/2016/07/13/mixins-considered-harmful.html) - [React with no configuration](https://facebook.github.io/react/blog/2016/07/22/create-apps-with-no-configuration.html) [HN Discussion](https://news.ycombinator.com/item?id=12144371) - [Pure functional React](https://twitter.com/bahmutov/status/760321846529097728) - [React Enlightenment](http://www.reactenlightenment.com/)
    * [Hooks and Streams](https://james-forbes.com/#!/posts/hooks-and-streams) article
    * [React compose](https://github.com/acdlite/recompose/) utilities and high-order components
    * [React Virtualized](https://bvaughn.github.io/react-virtualized/) view components which render only within viewport
    * [Electrode](http://www.electrode.io/) platform for building universal React/Node.js applications
    * [BluePrint](http://blueprintjs.com/) common components for building web applications
* [Vuejs](https://github.com/vuejs/vue) Data-reactive components using plain JS objects [Vue React Performance Comparison](https://engineering.footballradar.com/a-fairer-vue-of-react-comparing-react-to-vue-for-dynamic-tabular-data-part-2/)
    * [discussion1](https://news.ycombinator.com/item?id=12614681), [discussion2](https://news.ycombinator.com/item?id=12757946)
    * [Quasar](  http://quasar-framework.org/) cross platform UI library
* [Inferno](https://github.com/trueadm/inferno) extremely fast virtual dom, React like API and design.  As of 2016/05/26 this may be the fastest vdom implementation.  [HN discussion](https://news.ycombinator.com/item?id=11837082) [HN discussion on Mobile compared with React, Vue, Mithril, Cycle...](https://news.ycombinator.com/item?id=12133695)
* [FastDOM](https://github.com/wilsonpage/fastdom) Eliminates layout thrashing by batching DOM measurement and mutation tasks
* [Incremental-dom](https://github.com/google/incremental-dom) An in-place DOM diffing library vs virtual dom
* [sinuous](https://github.com/luwes/sinuous) Light, fast, reactive UI library
* [htm](https://github.com/developit/htm) SX alternative using standard tagged templates, with compiler support
* [lit-html](https://github.com/Polymer/lit-html) An efficient, expressive, extensible HTML templating library for JavaScript
* [zoid](https://github.com/krakenjs/zoid) cross domain components.  See additional cross domain libraries under [krakenjs](https://github.com/krakenjs)
* [mikado](https://github.com/nextapps-de/mikado) webs fastest template library for building user interfaces
* [solidjs](https://github.com/solidjs/solid) declarative, efficient, and flexible JavaScript library for building user interfaces

## UI
Great [article](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660) for reference when choosing a CSS libary
* [Dragula](https://github.com/bevacqua/dragula) Drag and drop library
* [Draggable](https://github.com/Shopify/draggable) Drag and drop library from Shopify
* [Muuri](https://haltu.github.io/muuri/) Drag Drop Filter and Sort Grid
* [dropzone](https://github.com/enyo/dropzone/) Drag and drop for file uploads
* [quill](https://github.com/quilljs/quill/) Rich text editor
* [medium editor](https://github.com/yabwe/medium-editor) ContentEditable API editor
* [Slate](https://github.com/ianstormtaylor/slate) Customizable rich text editor. [discussion](https://news.ycombinator.com/item?id=18457325)
* [Segment](https://github.com/lmgonzalves/segment) small library animate SVG path strokes
* [Emotion](https://github.com/emotion-js/emotion) Next Generation CSS in JS. [Article](https://medium.com/@tkh44/emotion-ad1c45c6d28b)
* [nano-css](https://github.com/streamich/nano-css) CSS in JS.  0.5kb performant modular library. 5th generation
* [fela](https://github.com/robinweser/fela) high-performant and framework-agnostic toolbelt to handle state-driven css in JavaScript.
* [StyleTron](http://styletron.js.org/) CSS-in-JS engine built from the ground up for high-performance
* [Bulma](http://bulma.io/) CSS designed with flexbox
* [Tachyons](https://github.com/tachyons-css/tachyons/) Functional css for humans [review](https://www.reddit.com/r/reactjs/comments/a6qhbr/checked_21_react_ui_kits_briefly_im_done/)
* [Tailwind](https://github.com/tailwindcss/tailwindcss) A utility-first CSS framework for rapid UI development.
* [Spectre](https://github.com/picturepan2/spectre)  Lightweight, Responsive and Modern CSS Framework
* [Push](https://github.com/Nickersoft/push.js) cross browser desktop notifications
* [Cleave](https://github.com/nosir/cleave.js) UI enforced field validations and formatted input
* [Clusterize](http://clusterize.js.org/) Tiny plugin to display large data sets easily
* [Smart Table Scroll](https://github.com/cmpolis/smart-table-scroll) Build 1MM row tables with native scroll bars by reusing and yielding nodes
* [palx](https://github.com/jxnblk/palx) color theme generator
* [tinykeys](https://github.com/jamiebuilds/tinykeys) key bindings

## Graphic libraries
[State of web animation, May 2016](https://css-tricks.com/comparison-animation-technologies/)
* [WebAnimations API](https://github.com/web-animations/web-animations-js) Polyfill for upcoming standard [Web Animations API](https://www.sitepoint.com/bringing-pages-to-life-web-animations-api/)
* [VivaGraphJS](https://github.com/anvaka/VivaGraphJS) fastest graph drawing javascript library 
* [StageXL](https://github.com/bp74/StageXL) StageXL is a fast and universal 2D rendering engine for HTML5
* [three.js](https://github.com/mrdoob/three.js/) 3D Library. Canvas, SVG, CSS3D, WebGL
* [TWGL](http://twgljs.org/) Tiny WebGL helper library
* [OSG.JS](http://osgjs.org/) OpenSceneGraph WebGL
* [Pixi.js](http://www.pixijs.com/) 2d webGL renderer canvas fallback
* [regl](https://github.com/mikolalysenko/regl) Functional WebGL
* [phenomenon](https://github.com/vaneenige/phenomenon) A fast 2kB low-level WebGL API
* [gl-matrix](https://github.com/toji/gl-matrix) Matrix and Vector library for High Performance WebGL
* [react-three-fiber](https://github.com/pmndrs/react-three-fiber) React and threejs
* [Konva](http://konvajs.github.io/) 2d canvas drawing animation library
* [Paper.js](http://paperjs.org/about/) Vector graphics on canvas
* [SVG.js](https://github.com/wout/svg.js) library for manipulating and animating SVG
* [Anime.js](https://github.com/juliangarnier/anime) animation library
* [Popmotion](https://github.com/popmotion/popmotion) animiation library using functional API
* [Kute.js](http://thednp.github.io/kute.js/index.html) impressive performance animation library
* [AnimXYZ](https://github.com/ingram-projects/animxyz) composable CSS animation library
* [mojs](https://github.com/legomushroom/mojs) motion graphics library.  [Workflow](https://vimeo.com/185587462) with editing tools.
* [Aframe](https://github.com/aframevr/aframe/) 3D Web VR
* [Matter.js](https://github.com/liabru/matter-js) 2D rigid body physics engine for the web
* [Opentype.js](http://opentype.js.org/) Draw opentype and truetype fonts on canvas
* [Jimp](https://github.com/oliver-moran/jimp) Image manipulation library
* [Chroma.js](https://github.com/gka/chroma.js) Color manipulation library. [Article](https://swizec.com/blog/make-things-pretty-chroma-js/swizec/8233)

## Visualization
* [D3](https://github.com/mrdoob/three.js/) Library for document manipulation based on data
* [dc.js](https://dc-js.github.io/dc.js/) interactive cross filtering on top of D3
* [nvd3](https://nvd3-community.github.io/nvd3/) charts built on top of D3
* [Vis.js](http://visjs.org/index.html) library with DataSet, Timeline, Network, Graph2d and Graph3d visualization types
* [Chart.js](https://github.com/chartjs/Chart.js) animated charts using canvas
* [Billboard.js](https://github.com/naver/billboard.js) re-usable, easy interface JavaScript chart library, based on D3 v4+
* [Recharts](http://recharts.org/) React component charts
* [jointJS](https://github.com/clientIO/joint) diagramming library, SVG, interactive editing, path routing
* [Dagre](https://github.com/cpettitt/dagre/wiki) directed graph layout library. use view as D3, jointJS, cytoscape
* [cola.js](http://marvl.infotech.monash.edu/webcola/) contraint based layout library.
* [MathBox](https://gitgud.io/unconed/mathbox) Presentation-quality WebGL math graphing
* [OpenLayers](http://openlayers.org/) high-performance, feature-packed library for all your mapping needs
* [pdfmake](https://github.com/bpampuch/pdfmake) client/server PDF JS library
* [pts](https://github.com/williamngan/pts) library for visualization and creative-coding

## Multi Media
* [video.js](https://github.com/videojs/video.js) JS Browser video player
* [plyr](https://github.com/selz/plyr) JS Browser video audio player
* [howler.js](https://github.com/goldfire/howler.js/tree/2.0) Audio playback library.  Web Audio, HTML 5 fallback
* [tone.js](https://github.com/Tonejs/Tone.js) Audio framework for making interactive music
* [timbre.js](http://mohayonao.github.io/timbre.js/) Objective sound programming
* [tonal.js](https://github.com/danigb/tonal) Funtional music theory library
* [flocking](https://github.com/colinbdclark/Flocking) audio synthesizer library
* [jsfx](https://github.com/loov/jsfx) JavaScript sound effect generator
* [standardized audio context](https://github.com/chrisguttandin/standardized-audio-context/) cross-browser implementation of the AudioContext
* [openmusic.gallery](https://github.com/mikehelland/openmusic.gallery) Music making, remixing, and collaborating tools for the web
* [essentia.js](https://github.com/MTG/essentia.js) music/audio signal analysis and processing for both real-time and offline use-cases

## NodeJS
* [Electron](http://electron.atom.io/) Web technologies as desktop applications [Essential Electron](http://jlord.us/essential-electron/)
* [NW.js](http://nwjs.io/) Web technologies as desktop applications
* [nodegui](https://github.com/nodegui/nodegui) Native GUI using QT for Linux, OSX, Windows
* [pkg](https://github.com/zeit/pkg) Node.js project into an executable 
* [Hackathon Starter](https://github.com/sahat/hackathon-starter) Starter skeleton framework for server application
* [got](https://github.com/sindresorhus/got) Simplified HTTP requests
* [undici](https://github.com/nodejs/undici) replacement for nodeJS core http
* [uWebSockets](https://github.com/uNetworking/uWebSockets.js) Highly scalable WebSocket server library
* [deepstream.io](https://deepstream.io/) a fast, secure and scalable websocket & tcp server for mobile, web & iot
* [socket.io](https://github.com/socketio/socket.io/) Realtime application framework
* [fastify](https://www.fastify.io/) Fastify is a web framework with the least overhead and a powerful plugin architecture
* [restify](https://github.com/restify/node-restify) framework for server REST APIs
* [FFI](https://github.com/node-ffi/node-ffi) Foreign function interface.  Call c functions from node
* [piscina](https://github.com/piscinajs/piscina) the node.js worker pool
* [klyng](https://github.com/Mostafa-Samir/klyng) Distributed computing
* [EMS](https://github.com/syntheticsemantics/ems) Shared memory parellelism for node
* [micro.js](https://github.com/zeit/micro) Micro services library
* [feathers](http://feathersjs.com/) minimalist real-time framework for rapid prototype development
* [Nodal](http://www.nodaljs.com/) API services on node
* [loopback](http://loopback.io/) Server API Framework.  
    * [IBM API Connect](https://developer.ibm.com/apiconnect/) UI management and API authoring on top of loopback 
* [Incheon](http://incheon.gg/) Node game server
* [Vorpal](http://vorpal.js.org/) CLI command line framework
* [Caporal](https://github.com/mattallty/Caporal.js) CLI command line framework
* [Enquirer](https://github.com/enquirer/enquirer) Stylish, intuitive and user-friendly prompts
* [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) A collection of common interactive command line user interfaces
* [Commander.js](https://github.com/tj/commander.js) node.js command-line interfaces made easy
* [Gluegun](https://github.com/infinitered/gluegun) CLI Builder
* [Yargs](https://github.com/yargs/yargs) Advanced CLI argument parser
* [shell.js](https://github.com/shelljs/shelljs) Unix commands available for cross platform NodeJS
* [event-stream](https://github.com/dominictarr/event-stream) EventStream is like functional programming meets IO
* [fs-jetpack](https://github.com/szwacz/fs-jetpack) better filesystem API
* [fdir](https://github.com/thecodrr/fdir) fast file glob
* [watchr](https://github.com/bevry/watchr) Better file system watching for Node.js
* [systeminformation](https://github.com/sebhildebrandt/systeminformation) hardware system information

## Platform
* [JavaPoly.js](https://www.javapoly.com/) JVM in the browser
* [doppio](https://github.com/plasma-umass/doppio) JVM in the browser
* [Serverless](https://github.com/serverless/serverless) AWS Lambda architecture
* [Elasticsearch](https://www.elastic.co/products/elasticsearch) distributed real-time search and analytics capabilities
* [Cheerp](http://leaningtech.com/cheerp/) C++ to JavaScript compiler
* [NeutralinoJS](https://neutralino.js.org/) Develop web apps with native os functions
* [Carlo](https://github.com/GoogleChromeLabs/carlo) Web rendering surface for Node applications
* [Tauri](https://github.com/tauri-apps/tauri) Framework agnostic toolchain for building highly secure native apps that have tiny binaries and are very fast
* [low.js](https://www.lowjs.org/) Node.js with far lower system requirements for microcontroller boards based on the ESP32-WROVER module

## Mobile
* [NativeScript](https://www.nativescript.org/) Native mobile apps in JavaScript with low level access to system API's
* [React Native](https://facebook.github.io/react-native/) Native UI's built on React
    * [Exponent](https://getexponent.com/) Improved React Native
* [UpUp](https://github.com/TalAter/UpUp/) Mobile first library for offline
* [ZingTouch](https://github.com/zingchart/zingtouch) Gesture library
* [Leaflet](http://leafletjs.com/2016/09/27/leaflet-1.0-final.html) mobile-friendly interactive maps

## WASM Web Assembly
* [assemblyscript](https://github.com/AssemblyScript/assemblyscript) Limited TypeScript to WASM compiler
* [wasmer](https://github.com/wasmerio/wasmer) High-Performance WebAssembly JIT interpreter

## Future
* [Neon](https://github.com/rustbridge/neon) Rust abstraction layer for native Node.js modules
* [Gpujs](https://github.com/gpujs/gpu.js) GPU Accelerated JavaScript
* [lume](https://github.com/lume/lume) Performance focused web rendering engine
* [DGraph](https://github.com/dgraph-io/dgraph/) Scalable, Distributed, Low Latency Graph Database
* [lighthouse](https://github.com/GoogleChrome/lighthouse) progressive web app diagnostics
* [HyperTerm](https://github.com/zeit/hyperterm) modern terminal. Electron based
* [Terminus](https://eugeny.github.io/terminus/) modern terminal. Electron based
* [Tesseract.js](http://tesseract.projectnaptha.com/) JS OCR
* [skia-canvas](https://github.com/samizdatco/skia-canvas) Browser Canvas for Node.js
* [BlueSky](https://blueskycommunity.net/) Decentralized web projects

## Tools
* [Frida](https://github.com/frida/frida) Debugging through injecting JavaScript into native apps
* [verso](https://gitlab.com/p8n/verso) Low level debugging cross platform
* [gdbgui](https://github.com/cs01/gdbgui) browser-based frontend to gdb (gnu debugger)
* [UIforETW](https://github.com/google/UIforETW) Low level performance tracing on Windows
* [ndb](https://github.com/GoogleChromeLabs/ndb) ndb is an improved debugging experience for Node.js, enabled by Chrome DevTools
* [reveal.js](https://github.com/hakimel/reveal.js) Interactive presentation framework
* [impress.js](https://github.com/impress/impress.js) presentation framework based on the power of CSS3 transforms and transitions
* [npm-check](https://github.com/dylang/npm-check) Check for outdated, incorrect or unused dependencies
* [cheerp](http://leaningtech.com/cheerp/) C++ compiler to JavaScript
* [gitsome](https://github.com/donnemartin/gitsome) Enhanced command line Git
* [OpenRefine](http://openrefine.org/) exploring and manipulating messy data
* [Huginn](https://github.com/cantino/huginn) Build agents that act on your behalf
* [PMD](https://pmd.github.io/) source code analyzer
* [licecap](http://www.cockos.com/licecap/) record animated gif windows/osx
* [rollup.js](http://rollupjs.org) next generation module bundler.  tree-shaking
* [Webpack](https://webpack.github.io/) Very configurable supporting large scale development
* [Fuse-Box](https://github.com/fuse-box/fuse-box) blazing fast js bundler/loader with a comprehensive API 
* [Broswerify](http://browserify.org/) Easiest to setup and use module builder
* [GitKraken](https://www.gitkraken.com/) cross platform graphical Git management
* [robotN](https://github.com/vcaesar/robotn) Node interface to robotGo cross platform automation library
* [nut-js](https://github.com/nut-tree/nut.js) Node Desktop automation library in typescript
* [n8n](https://github.com/n8n-io/n8n) workflow automation visual composition
* [Webpack Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) bundle content as convenient interactive zoomable treemap
* [Marky](https://github.com/nolanlawson/marky) High performance timer for performance analysis
* [Pencil](https://github.com/evolus/pencil) UI prototype sketch tool
* [apify-js](https://github.com/apifytech/apify-js) web scrapper for high scale using puppeteer
* [sharp](https://github.com/lovell/sharp) high performance image scaling. fastest module to resize JPEG, PNG, WebP and TIFF images
* [tad](https://github.com/antonycourtney/tad) CSV data viewer
* [mkcert](https://github.com/FiloSottile/mkcert) make locally trusted development certificates
* [jscodeshift](https://github.com/facebook/jscodeshift) JavaScript codemod toolkit
* [gh-pages](https://github.com/tschaub/gh-pages) publish files to a 'gh-pages' branch
* [volta](https://github.com/volta-cli/volta) toolchain manager for NodeJS development
* [unplugin](https://github.com/unjs/unplugin) universal interace for build tool plugins
