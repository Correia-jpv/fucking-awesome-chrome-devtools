# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Contents

- [Learning](#learning)
- [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [DevTools Extensions](#devtools-extensions)

---

## Learning
- 🌎 [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- <b><code>&nbsp;&nbsp;1751⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [DevTools Snippets](https://github.com/bahmutov/code-snippets) - Collection of snippets.

### Multiuser DevTools
- <b><code>&nbsp;&nbsp;&nbsp;656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [DevTools Remote](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser.

---

## DevTools tooling and ecosystem

### Object formatting
- <b><code>&nbsp;&nbsp;&nbsp;642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values.

### Network Inspection
- <b><code>&nbsp;&nbsp;4330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [betwixt](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel.
- 🌎 [Weer](https://weerdbg.com/) - A HTTP protocol debugger **(closed source)**

### CPU profile
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
- <b><code>&nbsp;&nbsp;&nbsp;159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [cpuprofilify](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
- 🌎 [Wishbone python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) - Profiling data can export as `.cpuprofile`.

### Multimedia
- <b><code>&nbsp;&nbsp;&nbsp;389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [snapline](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif.

### Timeline, Tracing & Profiling
- 🌎 [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - Breakpoint debugging in VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;503⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) - Elements panel inside VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [ChromeREPL](https://github.com/acarabott/ChromeREPL) - Within Sublime Text, use the Chrome console.
- 🌎 [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - JavaScript Breakpoint debugging right in Sublime Text.
- 🌎 [WebStorm/JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- <b><code>&nbsp;&nbsp;&nbsp;731⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types.
- 🌎 [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes.
- <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - Tool for debugging clients using devtools protocol.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once.
- <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [RemoteDebug](https://github.com/RemoteDebug) - Initiative to normalize debugging protocols across today's browsers.
- 🌎 [ChromeDriver](https://sites.google.com/corp/chromium.org/driver/) - The official Selenium/WebDriver implementation for Chrome is implemented on top of the DevTools Protocol.
- <b><code>&nbsp;&nbsp;1500⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [BrowserGap Community Edition](https://github.com/dosycorp/browsergap.ce) - A remote browser product, open sourced. Makes heavy use of the raw, tip-of-tree Chrome DevTools protocol.

### Automation
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Puppeteer](https://github.com/GoogleChrome/puppeteer/) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol.
  - Python port: <b><code>&nbsp;&nbsp;2155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [pyppeteer](https://github.com/pyppeteer/pyppeteer)
  - Rust port: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/)
  - .NET port: <b><code>&nbsp;&nbsp;2221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;328🍴</code></b> [Puppeteer Sharp](https://github.com/kblok/puppeteer-sharp)
  - Ruby port: <b><code>&nbsp;&nbsp;1180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Ferrum](https://github.com/route/ferrum)
  - <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [headless-devtools](https://github.com/cowchimp/headless-devtools) - Puppeteer plugin to get CSS Coverage or JS Heap snapshot.
  - <b><code>&nbsp;&nbsp;1219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [PuPHPeteer](https://github.com/rialto-php/puphpeteer) - PHP-bridge to control Puppeteer using PHP.
- <b><code>&nbsp;35046⭐</code></b> <b><code>&nbsp;&nbsp;1538🍴</code></b> [Playwright](https://github.com/microsoft/playwright) - Node.js library to automate Chromium, Firefox and WebKit with a single API.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Taiko](https://github.com/getgauge/taiko/) - A Node.js module to automate the Chrome/Chromium using DevTools protocol.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [cuic](https://github.com/milankinen/cuic) - Clojure library providing a high-level API for UI test automation over the DevTools Protocol.
- Also all `Protocol Driver Libraries` below

### Protocol Driver Libraries
- JavaScript/Node.js: <b><code>&nbsp;&nbsp;3656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - The most-used JavaScript API for the protocol
- TypeScript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [chrome-debugging-client](https://github.com/krisselden/chrome-debugging-client)
- Java: <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
- Java: 🌎 [karate](https://intuit.github.io/karate/karate-core/) - Web-service testing framework with a Java API to automate Chrome
- Java: <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [jvppeteer](https://github.com/fanyong920/jvppeteer)  - Headless Chrome For Java 
- Python: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol) - Pure-Python, sans-IO wrappers. See also the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
- Python: <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [chromewhip](https://github.com/chuckus/chromewhip) - drop-in replacement for the `splash` service
- Python: <b><code>&nbsp;&nbsp;&nbsp;500⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [pychrome](https://github.com/fate0/pychrome) - low level CDP transport handler
- Python: <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ChromeController](https://github.com/fake-name/ChromeController) - high-level browser mgmt
- Go: <b><code>&nbsp;&nbsp;7321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;603🍴</code></b> [chromedp](https://github.com/chromedp/chromedp) - High-level actions and tasks for driving browsers
- Go: <b><code>&nbsp;&nbsp;&nbsp;597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [cdp](https://github.com/mafredri/cdp)
- Go: <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [gcd](https://github.com/wirepair/gcd)
- Go: <b><code>&nbsp;&nbsp;&nbsp;334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [godet](https://github.com/raff/godet)
- Go: <b><code>&nbsp;&nbsp;2174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [Rod](https://github.com/go-rod/rod)
- C#/dotnet: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
- Ruby: <b><code>&nbsp;&nbsp;&nbsp;919⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Cuprite](https://github.com/machinio/cuprite) - Capybara driver
- Ruby: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ChromeRemote](https://github.com/cavalle/chrome_remote/)
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) - reactive (rxjava 2.x), low-level client library in Kotlin
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin) - A coroutine-based client library, providing low-level CDP primitives and high-level extensions.
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- PHP: <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - A PHP client library for the protocol.

### Browser Adapters
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - Translates Firefox's devtools protocol to the CDP.
- <b><code>&nbsp;&nbsp;5438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP.
  - <b><code>&nbsp;&nbsp;2580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP.
- <b><code>&nbsp;&nbsp;&nbsp;581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 11 to CDP.


## Using DevTools frontend with other platforms

#### Android
- <b><code>&nbsp;12457⭐</code></b> <b><code>&nbsp;&nbsp;1147🍴</code></b> [Facebook Stetho](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger) - Debugging JavaScript running in <b><code>&nbsp;&nbsp;2163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [J2V8](https://github.com/eclipsesource/J2V8) with Chrome DevTools.

#### ClojureScript
- <b><code>&nbsp;&nbsp;&nbsp;752⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Dirac](https://github.com/binaryage/dirac) - Debugging of ClojsureScript.

#### Lua
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Mare](https://github.com/muzuiget/mare) - Lua debugging with Chrome DevTools.

#### iOS
- <b><code>&nbsp;&nbsp;5861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;617🍴</code></b> [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools.

#### Go
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [go-debugger-devtools](https://github.com/allada/go-debugger-devtools)

#### Node.js
- <b><code>&nbsp;10626⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [ndb](https://github.com/GoogleChromeLabs/ndb) - An improved Node.js debugging experience with the DevTools Frontend.
- 🌎 [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
- <b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [thetool](https://github.com/sfninja/thetool) - CPU, memory, coverage, type profiling with Node.
- 🌎 [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.

---

## DevTools Extensions

### Accessibility (A11y)
- 🌎 [Chromelens](http://chromelens.xyz) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow
- 🌎 [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- 🌎 [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- 🌎 [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- 🌎 [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- 🌎 [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- <b><code>&nbsp;22021⭐</code></b> <b><code>&nbsp;&nbsp;3681🍴</code></b> [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) - Inspect VueJS components and manipulate their data.
- 🌎 [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- 🌎 [Augury](https://augury.angular.io) - Debugging and Profiling for Angular 2 applications.
- 🌎 [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- 🌎 [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- 🌎 [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- 🌎 [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- 🌎 [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Insight](https://github.com/3Dparallax/insight/) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework.
- 🌎 [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.

### Themes
- 🌎 [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- 🌎 [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.
- 🌎 [Material UI Theme](https://chrome.google.com/webstore/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - Provides various Material Design inspired themes.

### Performance
- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [sloth](https://github.com/denar90/sloth) - Chrome extension allows to enable and save CPU and network throttling for selected tabs.
- <b><code>&nbsp;&nbsp;&nbsp;212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [TracerBench](https://github.com/TracerBench/tracerbench) - TracerBench is a controlled performance benchmarking tool for web applications, providing clear, actionable and usable insights into performance deltas.

### Automation
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Puppeteer IDE](https://github.com/gajananpp/puppeteer-ide-extension) - Standalone Puppeteer playground in browser's developer tools.
