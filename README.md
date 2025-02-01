# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Contents

- [Learning](#learning)
- [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [DevTools Extensions](#devtools-extensions)
- [Alumni](#alumni)

---

## Learning
- 🌎 [Dev Tips](umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- 🌎 [DevTools Tips](devtoolstips.org/) - Collection of illustrated tips as mini tutorials.
- 🌎 [Can I DevTools?](www.canidev.tools/) - Various workflows, documented. Also a weekly tips & tricks 🌎 [newsletter](canidevtools.substack.com/).
- 🌎 [Web cheatcodes](codepo8.github.io/web-cheatcodes/) - Browser developer tools for non-developers.
- 🌎 [Dear Console](codepo8.github.io/dearconsole) - A collection of snippets to use in the browser console.

---

## DevTools tooling and ecosystem

### Object formatting
- <b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [immutable-devtools](https://github.com/andrewdavey/immutable-devtools)) - Custom formatter for Immutable-js values.

### Network Inspection
- <b><code>&nbsp;&nbsp;4544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [betwixt](https://github.com/kdzwinel/betwixt)) - System level network proxy, providing inspection via Network panel.
- 🌎 [Weer](weerdbg.com/) - A HTTP protocol debugger **(closed source)**

### CPU profile
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [call-trace](https://github.com/brendankenny/call-trace)) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
- <b><code>&nbsp;&nbsp;&nbsp;168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [cpuprofilify](https://github.com/thlorenz/cpuprofilify)) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
- 🌎 [Wishbone python framework](wishbone.readthedocs.io/en/latest/misc/profiling.html) - Profiling data can export as `.cpuprofile`.

### Multimedia
- <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [snapline](https://github.com/pmdartus/snapline)) - Converts timeline screenshots to gif.

### Timeline, Tracing & Profiling
- 🌎 [DevTools Timeline Viewer](chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/)) - Breakpoint debugging in VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;765⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools)) - Elements panel inside VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [ChromeREPL](https://github.com/acarabott/ChromeREPL)) - Within Sublime Text, use the Chrome console.
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - JavaScript Breakpoint debugging right in Sublime Text.
- 🌎 [WebStorm/JetBrains Chrome Extension](www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- <b><code>&nbsp;&nbsp;1185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol)) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types.
- 🌎 [DevTools Protocol API Docs](chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki)) - Many useful recipes.
- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy)) - Tool for debugging clients using devtools protocol.

### The big two automation libraries
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Puppeteer](https://github.com/GoogleChrome/puppeteer/)) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol. See also <b><code>&nbsp;&nbsp;2432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [awesome-puppeteer](https://github.com/transitive-bullshit/awesome-puppeteer)).
- <b><code>&nbsp;68919⭐</code></b> <b><code>&nbsp;&nbsp;3820🍴</code></b> [Playwright](https://github.com/microsoft/playwright)) - Library to automate Chromium, Firefox and WebKit with a single API. Available for Node.js, Python, .Net, Java. See also <b><code>&nbsp;&nbsp;1003⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [awesome-playwright](https://github.com/mxschmitt/awesome-playwright)).

### Libraries for driving the protocol (or a layer above)

- JavaScript/Node.js: <b><code>&nbsp;&nbsp;4321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;312🍴</code></b> [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface))
- TypeScript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [chrome-debugging-client](https://github.com/TracerBench/chrome-debugging-client))
- Typescript/Node.js: 🌎 [noice-json-rpc](www.npmjs.com/package/noice-json-rpc) - A proxy-based implementation to expose the CDP as its API.
- Typescript/Node.js: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Taiko](https://github.com/getgauge/taiko/))
- Rust: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/))
- Java: <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client))
- Java: <b><code>&nbsp;&nbsp;&nbsp;753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [jvppeteer](https://github.com/fanyong920/jvppeteer))  - Headless Chrome For Java 
- Python: <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol)) - Pure-Python, sans-IO wrappers. See also the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol))
- Python: <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [chromewhip](https://github.com/chuckus/chromewhip)) - drop-in replacement for the `splash` service
- Python: <b><code>&nbsp;&nbsp;3753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [pyppeteer](https://github.com/pyppeteer/pyppeteer)) - puppeteer port
- Python: <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [ChromeController](https://github.com/fake-name/ChromeController)) - high-level browser mgmt
- Go: <b><code>&nbsp;11333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;799🍴</code></b> [chromedp](https://github.com/chromedp/chromedp)) - High-level actions and tasks for driving browsers
- Go: <b><code>&nbsp;&nbsp;&nbsp;739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [cdp](https://github.com/mafredri/cdp))
- Go: <b><code>&nbsp;&nbsp;&nbsp;185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [gcd](https://github.com/wirepair/gcd))
- Go: <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [godet](https://github.com/raff/godet))
- Go: <b><code>&nbsp;&nbsp;5663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;371🍴</code></b> [Rod](https://github.com/go-rod/rod))
- C#/.NET: <b><code>&nbsp;&nbsp;3499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp)) - puppeteer port
- C#/dotnet: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools)) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
- C#/.NET: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [dotnet-chrome-protocol](https://github.com/seclerp/dotnet-chrome-protocol)) - A runtime library and schema code generation tools for Chrome DevTools Protocol support in C#/.NET.
- Ruby: <b><code>&nbsp;&nbsp;1805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Ferrum](https://github.com/route/ferrum)) - high-level API to control Chrome in Ruby
- Ruby: <b><code>&nbsp;&nbsp;1272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Cuprite](https://github.com/machinio/cuprite)) - Capybara driver
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin)) - reactive (rxjava 2.x), low-level client library in Kotlin
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin)) - A coroutine-based client library, providing low-level CDP primitives and high-level extensions.
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools)) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [cuic](https://github.com/milankinen/cuic)) - Providing a high-level API for UI test automation over the DevTools Protocol.
- PHP: <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol)) - A PHP client library for the protocol.
- PHP: <b><code>&nbsp;&nbsp;1339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [PuPHPeteer](https://github.com/rialto-php/puphpeteer)) - php bridge to node puppeteer


### Browser Adapters
- <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [devtools-remote-debugger](https://github.com/Nice-PLQ/devtools-remote-debugger)) - Use devtools against a webpage; a CDP agent implemeted in client-side JS.
- 🌎 [Inspect](inspect.dev/) - Use devtools against iOS and Android, easily. Browser and Webviews. **(closed source)**


## Using DevTools frontend with other platforms

#### Android
- <b><code>&nbsp;12683⭐</code></b> <b><code>&nbsp;&nbsp;1127🍴</code></b> [Facebook Stetho](https://github.com/facebook/stetho)) - Native Android debugging with Chrome DevTools.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger)) - Debugging JavaScript running in <b><code>&nbsp;&nbsp;2571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;358🍴</code></b> [J2V8](https://github.com/eclipsesource/J2V8)) with Chrome DevTools.

#### ClojureScript
- <b><code>&nbsp;&nbsp;&nbsp;771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Dirac](https://github.com/binaryage/dirac)) - Debugging of ClojsureScript.

#### iOS
- <b><code>&nbsp;&nbsp;5861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;595🍴</code></b> [PonyDebugger](https://github.com/square/PonyDebugger)) - Remote network and data debugging iOS apps with Chrome DevTools.

#### Node.js
- <b><code>&nbsp;10896⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [ndb](https://github.com/GoogleChromeLabs/ndb)) - An improved Node.js debugging experience with the DevTools Frontend.
- 🌎 [Debugging Node.js with Chrome DevTools](medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
- <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [thetool](https://github.com/sfninja/thetool)) - CPU, memory, coverage, type profiling with Node.
- 🌎 [chrome-devtools-frontend](www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.

#### Ruby
- <b><code>&nbsp;&nbsp;1172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [ruby/debug](https://github.com/ruby/debug)) - Debugging functionality for Ruby.

---

## DevTools Extensions

### Accessibility (A11y)
- 🌎 [Chromelens](chrome.google.com/webstore/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow
- 🌎 [Clockwork](chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- 🌎 [Emulated Device Lab](chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- 🌎 [RailsPanel](chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- 🌎 [React Developer Tools](chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- 🌎 [EmberJS Inspector](chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- <b><code>&nbsp;24701⭐</code></b> <b><code>&nbsp;&nbsp;4149🍴</code></b> [VueJS Developer Tools](https://github.com/vuejs/vue-devtools)) - Inspect VueJS components and manipulate their data.
- 🌎 [Angular Batarang](chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- 🌎 [Augury](augury.angular.io) - Debugging and Profiling for Angular 2 applications.
- 🌎 [Marionette Inspector](chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- 🌎 [Backbone Debugger](chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- 🌎 [App Inspector for Sencha](chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- 🌎 [Redux Devtools](chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- 🌎 [Three.js](chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Insight](https://github.com/3Dparallax/insight/)) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [BEM devtools](https://github.com/escaton/bem-chrome-devtools)) - Inspect BEM entities expressed in `i-bem` framework.
- 🌎 [Metal.js Developer Tools](chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.
- 🌎 [Web Component DevTools](chrome.google.com/webstore/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify and observe Web Components on page.

### Themes
- 🌎 [DevTools Author](chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- 🌎 [Zero Dark Matrix](chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.
- 🌎 [Material UI Theme](chrome.google.com/webstore/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - Provides various Material Design inspired themes.

### Performance
- <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [sloth](https://github.com/denar90/sloth)) - Chrome extension allows to enable and save CPU and network throttling for selected tabs.
- <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [TracerBench](https://github.com/TracerBench/tracerbench)) - TracerBench is a controlled performance benchmarking tool for web applications, providing clear, actionable and usable insights into performance deltas.

### Automation
- <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Puppeteer IDE](https://github.com/gajananpp/puppeteer-ide-extension)) - Standalone Puppeteer playground in browser's developer tools.
- <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [k6 browser](https://github.com/grafana/xk6-browser)) - Browser automation and end-to-end web testing tool that interacts with browsers and collects frontend performance metrics.

## Alumni
Old projects, likely not maintained any longer… But still cool.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway)) - Allows you to connect a client to multiple browsers at once.  
   - Multiuser DevTools: <b><code>&nbsp;&nbsp;&nbsp;688⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [DevTools Remote](https://github.com/auchenberg/devtools-remote)) - Remotely debug someone else's browser.
- <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [DevTools Backend](https://github.com/christian-bromann/devtools-backend)) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
- Python CDP driver: <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [pychrome](https://github.com/fate0/pychrome)) - low level CDP transport handler
- <b><code>&nbsp;&nbsp;5994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy)) - Exposes Mobile Safari & UIWebView instances via the CDP.
  - <b><code>&nbsp;&nbsp;2728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter)) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP.
- <b><code>&nbsp;&nbsp;&nbsp;573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter)) - Protocol adaptor for Microsoft IE 11 to CDP.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [go-debugger-devtools](https://github.com/allada/go-debugger-devtools))

## Source
<b><code>&nbsp;&nbsp;6218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;354🍴</code></b> [ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools))