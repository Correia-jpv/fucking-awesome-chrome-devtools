# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Contents

- [Learning](#learning)
- [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [Applications](#applications)
- [DevTools Extensions](#devtools-extensions)
- [Alumni](#alumni)

---

## Learning
- 🌎 [Dev Tips](umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- 🌎 [DevTools Tips](devtoolstips.org/) - Collection of illustrated tips as mini tutorials.
- 🌎 [Can I DevTools?](www.canidev.tools/) - Various workflows, documented. Also a weekly tips & tricks 🌎 [newsletter](canidevtools.substack.com/).
- 🌎 [Web cheatcodes](codepo8.github.io/web-cheatcodes/) - Browser developer tools for non-developers.
- 🌎 [Dear Console](codepo8.github.io/dearconsole) - A collection of snippets to use in the browser console.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Chrome Secret Menus](https://github.com/sparkyrider/chrome-secret-menus)) - Comprehensive guide to internal pages and diagnostic tools in Chrome.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Front-end Debugging Tools Handbook](https://github.com/lala-hakobyan/front-end-debugging-handbook)) - Practical guide to mastering front-end debugging tools, from Chrome DevTools and framework extensions to AI-enhanced IDE debugging.

---

## DevTools tooling and ecosystem

### Object formatting
- <b><code>&nbsp;&nbsp;&nbsp;671⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [immutable-devtools](https://github.com/andrewdavey/immutable-devtools)) - Custom formatter for Immutable-js values.

### Network Inspection
- <b><code>&nbsp;&nbsp;4562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [betwixt](https://github.com/kdzwinel/betwixt)) - System level network proxy, providing inspection via Network panel.

### CPU profile
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [call-trace](https://github.com/brendankenny/call-trace)) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [cpuprofilify](https://github.com/thlorenz/cpuprofilify)) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
- 🌎 [Wishbone Python framework](wishbone.readthedocs.io/en/latest/misc/profiling.html) - Profiling data can export as `.cpuprofile`.

### Multimedia
- <b><code>&nbsp;&nbsp;&nbsp;401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [snapline](https://github.com/pmdartus/snapline)) - Converts timeline screenshots to gif.

### Timeline, Tracing & Profiling
- 🌎 [DevTools Timeline Viewer](chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/)) - Breakpoint debugging in VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;816⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools)) - Elements panel inside VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [ChromeREPL](https://github.com/acarabott/ChromeREPL)) - Within Sublime Text, use the Chrome console.
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - JavaScript Breakpoint debugging right in Sublime Text.
- 🌎 [WebStorm/JetBrains Chrome Extension](www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- <b><code>&nbsp;&nbsp;1478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol)) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types.
- 🌎 [DevTools Protocol API Docs](chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki)) - Many useful recipes.
- <b><code>&nbsp;&nbsp;&nbsp;249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy)) - Tool for debugging clients using devtools protocol.

### The big two automation libraries
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Puppeteer](https://github.com/GoogleChrome/puppeteer/)) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol. See also <b><code>&nbsp;&nbsp;2551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [awesome-puppeteer](https://github.com/transitive-bullshit/awesome-puppeteer)).
- <b><code>&nbsp;87667⭐</code></b> <b><code>&nbsp;&nbsp;5601🍴</code></b> [Playwright](https://github.com/microsoft/playwright)) - Library to automate Chromium, Firefox and WebKit with a single API. Available for Node.js, Python, .Net, Java. See also <b><code>&nbsp;&nbsp;1441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [awesome-playwright](https://github.com/mxschmitt/awesome-playwright)).

### Libraries for driving the protocol (or a layer above)

- JavaScript/Node.js: <b><code>&nbsp;&nbsp;4522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;325🍴</code></b> [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface))
- TypeScript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [chrome-debugging-client](https://github.com/TracerBench/chrome-debugging-client))
- TypeScript/Node.js: 🌎 [noice-json-rpc](www.npmjs.com/package/noice-json-rpc) - A proxy-based implementation to expose the CDP as its API.
- TypeScript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Taiko](https://github.com/getgauge/taiko/))
- TypeScript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Lumen](https://github.com/omxyz/lumen)) - Vision-first browser agent with self-healing deterministic replay over CDP.
- Rust: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/))
- Java: <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client))
- Java: <b><code>&nbsp;&nbsp;&nbsp;806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [jvppeteer](https://github.com/fanyong920/jvppeteer))  - Headless Chrome For Java 
- Python: <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol)) - Pure-Python, sans-IO wrappers. See also the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol))
- Python: <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [chromewhip](https://github.com/chuckus/chromewhip)) - drop-in replacement for the `splash` service
- Python: <b><code>&nbsp;&nbsp;3939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [pyppeteer](https://github.com/pyppeteer/pyppeteer)) - Puppeteer port
- Python: <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [ChromeController](https://github.com/fake-name/ChromeController)) - high-level browser mgmt
- Go: <b><code>&nbsp;12997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;868🍴</code></b> [chromedp](https://github.com/chromedp/chromedp)) - High-level actions and tasks for driving browsers
- Go: <b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [cdp](https://github.com/mafredri/cdp))
- Go: <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [gcd](https://github.com/wirepair/gcd))
- Go: <b><code>&nbsp;&nbsp;&nbsp;400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [godet](https://github.com/raff/godet))
- Go: <b><code>&nbsp;&nbsp;6887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [Rod](https://github.com/go-rod/rod))
- C#/.NET: <b><code>&nbsp;&nbsp;3881⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;484🍴</code></b> [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp)) - Puppeteer port
- C#/dotnet: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools)) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
- C#/.NET: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [dotnet-chrome-protocol](https://github.com/seclerp/dotnet-chrome-protocol)) - A runtime library and schema code generation tools for Chrome DevTools Protocol support in C#/.NET.
- Ruby: <b><code>&nbsp;&nbsp;2002⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Ferrum](https://github.com/route/ferrum)) - high-level API to control Chrome in Ruby
- Ruby: <b><code>&nbsp;&nbsp;1368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Cuprite](https://github.com/machinio/cuprite)) - Capybara driver
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin)) - reactive (rxjava 2.x), low-level client library in Kotlin
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin)) - A coroutine-based client library, providing low-level CDP primitives and high-level extensions.
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools)) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [cuic](https://github.com/milankinen/cuic)) - Providing a high-level API for UI test automation over the DevTools Protocol.
- PHP: <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol)) - A PHP client library for the protocol.
- PHP: <b><code>&nbsp;&nbsp;1335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [PuPHPeteer](https://github.com/rialto-php/puphpeteer)) - PHP bridge to node Puppeteer


### Browser Adapters
- <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [devtools-remote-debugger](https://github.com/Nice-PLQ/devtools-remote-debugger)) - Use devtools against a webpage; a CDP agent implemeted in client-side JS.
- 🌎 [Inspect](inspect.dev/) - Use devtools against iOS and Android, easily. Browser and Webviews. **(closed source)**


## Using DevTools frontend with other platforms

#### Android
- <b><code>&nbsp;12679⭐</code></b> <b><code>&nbsp;&nbsp;1117🍴</code></b> [Facebook Stetho](https://github.com/facebook/stetho)) - Native Android debugging with Chrome DevTools.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger)) - Debugging JavaScript running in <b><code>&nbsp;&nbsp;2634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;388🍴</code></b> [J2V8](https://github.com/eclipsesource/J2V8)) with Chrome DevTools.

#### ClojureScript
- <b><code>&nbsp;&nbsp;&nbsp;774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Dirac](https://github.com/binaryage/dirac)) - Debugging of ClojsureScript.

#### iOS
- <b><code>&nbsp;&nbsp;5853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;584🍴</code></b> [PonyDebugger](https://github.com/square/PonyDebugger)) - Remote network and data debugging iOS apps with Chrome DevTools.

#### Node.js
- <b><code>&nbsp;10901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [ndb](https://github.com/GoogleChromeLabs/ndb)) - An improved Node.js debugging experience with the DevTools Frontend.
- 🌎 [Debugging Node.js with Chrome DevTools](medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
- <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [thetool](https://github.com/sfninja/thetool)) - CPU, memory, coverage, type profiling with Node.
- 🌎 [chrome-devtools-frontend](www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.

#### Ruby
- <b><code>&nbsp;&nbsp;1263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [ruby/debug](https://github.com/ruby/debug)) - Debugging functionality for Ruby.

---

## Applications

### Browsers
- <b><code>&nbsp;&nbsp;3829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [BrowserBox](https://github.com/BrowserBox/BrowserBox)) - Embed Chrome in a web page, largely powered by DevTools and supporting multiuser browsing, remote DevTools, audio, and documents like `.docx`, `.pdf`, and more.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Puppetromium](https://github.com/dosyago/puppetromium)) - A proof-of-concept web browser built with Puppeteer, written in Node.js, HTML and CSS, with 0% client-side JavaScript.

### Web Archivers and Indexers
- <b><code>&nbsp;&nbsp;3898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [dn](https://github.com/dosyago/dn)) - Archive and index pages you browse for offline viewing and search, implemented using the `Fetch` domain's interceptions, and works with any Chromium-based browser.
  
---

## DevTools Extensions

### Workflow
- 🌎 [Clockwork](chromewebstore.google.com/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- 🌎 [RailsPanel](chromewebstore.google.com/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- 🌎 [React Developer Tools](chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- 🌎 [Ember.js Inspector](chromewebstore.google.com/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect Ember.js objects in your application.
- <b><code>&nbsp;24749⭐</code></b> <b><code>&nbsp;&nbsp;4145🍴</code></b> [Vue.js Developer Tools](https://github.com/vuejs/vue-devtools)) - Inspect Vue.js components and manipulate their data.
- 🌎 [Angular DevTools](chromewebstore.google.com/detail/angular-devtools/ienfalfjdbdpebioblfackkekamfmbnh) - Debugging and Profiling for Angular applications.
- 🌎 [Backbone Debugger](chromewebstore.google.com/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- 🌎 [Redux Devtools](chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Insight](https://github.com/3Dparallax/insight/)) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [BEM devtools](https://github.com/escaton/bem-chrome-devtools)) - Inspect BEM entities expressed in `i-bem` framework.
- 🌎 [Web Component DevTools](chromewebstore.google.com/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify and observe Web Components on page.

### Themes
- 🌎 [Material UI Theme](chromewebstore.google.com/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - Provides various Material Design inspired themes.

### Performance
- <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [sloth](https://github.com/denar90/sloth)) - Chrome extension allows to enable and save CPU and network throttling for selected tabs.
- <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [TracerBench](https://github.com/TracerBench/tracerbench)) - A controlled performance benchmarking tool for web applications, providing clear, actionable and usable insights into performance deltas.

### Automation
- <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Puppeteer IDE](https://github.com/gajananpp/puppeteer-ide-extension)) - Standalone Puppeteer playground in browser's developer tools.
- <b><code>&nbsp;&nbsp;&nbsp;360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [k6 browser](https://github.com/grafana/xk6-browser)) - Browser automation and end-to-end web testing tool that interacts with browsers and collects frontend performance metrics.

## Alumni
Old projects, likely not maintained any longer… But still cool.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway)) - Allows you to connect a client to multiple browsers at once.  
   - Multiuser DevTools: <b><code>&nbsp;&nbsp;&nbsp;701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [DevTools Remote](https://github.com/auchenberg/devtools-remote)) - Remotely debug someone else's browser.
- <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [DevTools Backend](https://github.com/christian-bromann/devtools-backend)) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
- Python CDP driver: <b><code>&nbsp;&nbsp;&nbsp;646⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [pychrome](https://github.com/fate0/pychrome)) - low level CDP transport handler
- <b><code>&nbsp;&nbsp;6159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;477🍴</code></b> [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy)) - Exposes Mobile Safari & UIWebView instances via the CDP.
  - <b><code>&nbsp;&nbsp;2738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter)) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP.
- <b><code>&nbsp;&nbsp;&nbsp;572⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter)) - Protocol adaptor for Microsoft IE 11 to CDP.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [go-debugger-devtools](https://github.com/allada/go-debugger-devtools))

## Source
<b><code>&nbsp;&nbsp;6979⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools))