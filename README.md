# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

Tools, protocol drivers, trace viewers, and standalone frontends built around Chrome DevTools and the Chrome DevTools Protocol (CDP). Following the <b><code>517049⭐</code></b> <b><code>&nbsp;37368🍴</code></b> [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)), we keep this list focused on what's genuinely useful rather than indexing everything in the space.

## Contents

- [Learning](#learning)
- [Tracing & Profiling](#tracing--profiling)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [DevTools Extensions](#devtools-extensions)
- [Alumni](#alumni)

---

## Learning
- 🌎 [Dev Tips](umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- 🌎 [DevTools Tips](devtoolstips.org/) - Collection of illustrated tips as mini tutorials.
- 🌎 [Web cheatcodes](codepo8.github.io/web-cheatcodes/) - Browser developer tools for non-developers.
- 🌎 [Dear Console](codepo8.github.io/dearconsole) - A collection of snippets to use in the browser console.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Chrome Secret Menus](https://github.com/sparkyrider/chrome-secret-menus)) - Guide to Chrome's internal `chrome://` pages and diagnostic tools.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Front-end Debugging Tools Handbook](https://github.com/lala-hakobyan/front-end-debugging-handbook)) - Practical guide to front-end debugging across DevTools, framework extensions, and IDEs.

---

## Tracing & Profiling

DevTools Performance traces and V8 `.cpuprofile` logs are plain JSON under the hood, and a few standalone viewers do great things with them:

- 🌎 [trace.cafe](trace.cafe/) - Share and view web performance traces directly in the DevTools Performance panel (<b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [source](https://github.com/paulirish/trace.cafe))).
- <b><code>&nbsp;&nbsp;6768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [speedscope](https://github.com/jlfwong/speedscope)) - Fast, interactive flamegraph viewer that imports Chrome `.cpuprofile` and timeline traces.
- <b><code>&nbsp;&nbsp;&nbsp;788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [cpupro](https://github.com/discoveryjs/cpupro)) - Deep V8/Chrome `.cpuprofile` analyzer with flamegraphs, call trees, and hot-spot diagnostics.
- <b><code>&nbsp;&nbsp;6623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;896🍴</code></b> [Perfetto](https://github.com/google/perfetto)) - System profiling and trace analysis suite  🌎 [ui.perfetto.dev](ui.perfetto.dev/)) with Chromium trace support and SQL trace querying.

---

## Chrome DevTools Protocol

Pro-tip: flip on Chrome's built-in 🌎 [Protocol Monitor](developer.chrome.com/docs/devtools/protocol-monitor) (`More tools > Protocol monitor`) to watch live CDP traffic and fire off raw commands right in the browser.

- <b><code>&nbsp;&nbsp;1569⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol)) - **Canonical location of the protocol JSON**, TypeScript types, and issue tracker for protocol bugs.
- 🌎 [DevTools Protocol API Docs](chromedevtools.github.io/devtools-protocol/) - Browsable UI for exploring the protocol's domains, methods, and events.

### Developing with the protocol
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki)) - Handy recipes for common raw-CDP tasks.
- <b><code>&nbsp;&nbsp;&nbsp;253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy)) - Proxy for inspecting and debugging CDP client traffic.

### The big two automation libraries
- <b><code>&nbsp;95673⭐</code></b> <b><code>&nbsp;&nbsp;9590🍴</code></b> [Puppeteer](https://github.com/puppeteer/puppeteer)) - High-level Node.js API for controlling Chrome over CDP and WebDriver BiDi. See also <b><code>&nbsp;&nbsp;2584⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [awesome-puppeteer](https://github.com/transitive-bullshit/awesome-puppeteer)).
- <b><code>&nbsp;97415⭐</code></b> <b><code>&nbsp;&nbsp;6576🍴</code></b> [Playwright](https://github.com/microsoft/playwright)) - Cross-browser automation for Chromium, Firefox, and WebKit across Node.js, Python, .NET, and Java. See also <b><code>&nbsp;&nbsp;1589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [awesome-playwright](https://github.com/mxschmitt/awesome-playwright)).

### Libraries for driving the protocol (or a layer above)

- JavaScript/Node.js: <b><code>&nbsp;&nbsp;4556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)) - Low-level CDP client
- Rust: <b><code>&nbsp;&nbsp;1402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [chromiumoxide](https://github.com/mattsse/chromiumoxide)) - Async/tokio library with generated types
- Rust: <b><code>&nbsp;&nbsp;2952⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [Rust Headless Chrome](https://github.com/rust-headless-chrome/rust-headless-chrome)) - High-level headless Chrome client
- Java: <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)) - Low-level protocol client
- Java: <b><code>&nbsp;&nbsp;&nbsp;805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [jvppeteer](https://github.com/fanyong920/jvppeteer)) - Headless Chrome for Java
- Python: <b><code>&nbsp;&nbsp;1455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Zendriver](https://github.com/cdpdriver/zendriver)) - Async CDP browser automation
- Python: <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol)) - Sans-IO wrappers (see also <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Trio driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)))
- Python: <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [ChromeController](https://github.com/fake-name/ChromeController)) - High-level browser mgmt
- Go: <b><code>&nbsp;13302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;889🍴</code></b> [chromedp](https://github.com/chromedp/chromedp)) - High-level actions and tasks
- Go: <b><code>&nbsp;&nbsp;7124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;486🍴</code></b> [Rod](https://github.com/go-rod/rod)) - High-level automation and scraping
- Go: <b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [cdp](https://github.com/mafredri/cdp)) - Type-safe bindings for CDP
- C#/.NET: <b><code>&nbsp;&nbsp;3922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;485🍴</code></b> [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp)) - Puppeteer port
- C#/.NET: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [dotnet-chrome-protocol](https://github.com/seclerp/dotnet-chrome-protocol)) - Runtime library and schema codegen
- Ruby: <b><code>&nbsp;&nbsp;2063⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Ferrum](https://github.com/rubycdp/ferrum)) - High-level API to control Chrome
- Ruby: <b><code>&nbsp;&nbsp;1398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [Cuprite](https://github.com/rubycdp/cuprite)) - Capybara driver
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin)) - Coroutine-based client library
- Kotlin: <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [kdriver](https://github.com/cdpdriver/kdriver)) - High-level coroutine-based automation
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools)) - Autogenerated CDP wrapper
- Clojure: <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [cuic](https://github.com/milankinen/cuic)) - High-level UI test automation
- PHP: <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol)) - Client library

### Agentic Browser Automation

> We're *extremely* picky with this section. Everyone is wrapping a browser for agents right now—expect any PR adding another MCP server or agent CLI to be closed unless it has real traction and does something novel with CDP under the hood.

- <b><code>&nbsp;53219⭐</code></b> <b><code>&nbsp;&nbsp;6090🍴</code></b> [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)) - Official MCP server for Chrome DevTools, which also includes a <b><code>&nbsp;53219⭐</code></b> <b><code>&nbsp;&nbsp;6090🍴</code></b> [CLI](https://github.com/ChromeDevTools/chrome-devtools-mcp/blob/main/skills/chrome-devtools-cli/SKILL.md)).
- <b><code>&nbsp;&nbsp;2687⭐</code></b> <b><code>&nbsp;&nbsp;1545🍴</code></b> [Webcmd](https://github.com/agentrhq/webcmd)) - Compiles site navigation into deterministic per-site CLI commands for AI agents.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Lumen](https://github.com/omxyz/lumen)) - Vision-first browser agent with self-healing deterministic replay over CDP.
- <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [bdg](https://github.com/szymdzum/browser-debugger-cli)) - Persistent background CDP session exposing DOM, network, console, and raw protocol methods as shell commands.


### Browser Adapters
- <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [devtools-remote-debugger](https://github.com/Nice-PLQ/devtools-remote-debugger)) - Debug a webpage remotely via a CDP agent implemented in client-side JS.
- 🌎 [Inspect](inspect.dev/) - Use DevTools against iOS and Android browsers and WebViews. **(closed source)**


## Using DevTools frontend with other platforms

The DevTools UI is a web app speaking CDP over a WebSocket, so you can embed it or point it at Node, Ruby, mobile webviews, or custom runtimes (see `chrome://inspect` for built-in targets).

- <b><code>&nbsp;&nbsp;4068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;727🍴</code></b> [ChromeDevTools/devtools-frontend](https://github.com/ChromeDevTools/devtools-frontend)) - Canonical source repo for the Chrome DevTools UI (published to npm as 🌎 [chrome-devtools-frontend](www.npmjs.com/package/chrome-devtools-frontend)).
- <b><code>&nbsp;&nbsp;2247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Chii](https://github.com/liriliri/chii)) & <b><code>&nbsp;21212⭐</code></b> <b><code>&nbsp;&nbsp;1393🍴</code></b> [Eruda](https://github.com/liriliri/eruda)) - Remote debugging server using the real `devtools-frontend` UI (`Chii`, a modern Weinre replacement) and in-page mobile DevTools console (`Eruda`).
- <b><code>&nbsp;&nbsp;1983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [vscode-js-debug](https://github.com/microsoft/vscode-js-debug)) - Official DAP-compliant JavaScript and Chrome CDP debugger powering VS Code.
- <b><code>&nbsp;&nbsp;&nbsp;829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;360🍴</code></b> [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools)) - Elements and Network panels embedded inside VS Code.
- 🌎 [Debugging Node.js with Chrome DevTools](medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on debugging and profiling Node.js with `node --inspect`.
- <b><code>&nbsp;&nbsp;1276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [ruby/debug](https://github.com/ruby/debug)) - Ruby's official debugger, which supports connecting Chrome DevTools over CDP (`rdbg --open=chrome`).

---

## DevTools Extensions

- 🌎 [React Developer Tools](chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect React component hierarchies, props, and profiler flamegraphs.
- <b><code>&nbsp;&nbsp;2922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [Vue.js Developer Tools](https://github.com/vuejs/devtools)) - Inspect Vue.js components, state, and routing.
- 🌎 [Angular DevTools](chromewebstore.google.com/detail/angular-devtools/ienfalfjdbdpebioblfackkekamfmbnh) - Component tree inspection and change-detection profiling for Angular.
- 🌎 [Redux Devtools](chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Time-travel debugging and action history for Redux.
- 🌎 [Ember.js Inspector](chromewebstore.google.com/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Inspect Ember.js objects, routes, and data.
- 🌎 [Web Component DevTools](chromewebstore.google.com/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify, and observe custom elements and shadow DOM on the page.
- 🌎 [Clockwork](chromewebstore.google.com/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - PHP application profiling and request inspection in DevTools.
- 🌎 [RailsPanel](chromewebstore.google.com/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - Ruby on Rails request and SQL profiling panel.

## Alumni
Old projects, likely not maintained any longer… But still cool.

- <b><code>&nbsp;10863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [ndb](https://github.com/GoogleChromeLabs/ndb)) - Improved Node.js debugging experience built on the DevTools frontend.
- <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [thetool](https://github.com/sfninja/thetool)) - CPU, memory, coverage, and type profiling for Node.js.
- <b><code>&nbsp;12648⭐</code></b> <b><code>&nbsp;&nbsp;1117🍴</code></b> [Facebook Stetho](https://github.com/facebook/stetho)) - Native Android debugging with Chrome DevTools.
- <b><code>&nbsp;&nbsp;5849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;585🍴</code></b> [PonyDebugger](https://github.com/square/PonyDebugger)) - Remote network and Core Data debugging for iOS apps via Chrome DevTools.
- <b><code>&nbsp;&nbsp;4557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [betwixt](https://github.com/kdzwinel/betwixt)) - System-level network proxy inspected through a standalone DevTools Network panel.
- <b><code>&nbsp;&nbsp;&nbsp;775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Dirac](https://github.com/binaryage/dirac)) - ClojureScript debugging with a custom DevTools fork.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/)) - Original Chrome debugger for VS Code (superseded by built-in <b><code>&nbsp;&nbsp;1983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [vscode-js-debug](https://github.com/microsoft/vscode-js-debug)), which has a rich CDP/DAP implementation).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [noice-json-rpc](https://github.com/nojvek/noice-json-rpc)) - Proxy-based TypeScript/JS library exposing CDP domains directly as an API.
- <b><code>&nbsp;&nbsp;1329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [PuPHPeteer](https://github.com/rialto-php/puphpeteer)) - PHP bridge to Node Puppeteer.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Insight](https://github.com/3Dparallax/insight/)) - WebGL debugging toolkit for Chrome DevTools.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway)) - Connect a debugging client to multiple browsers at once.
  - Multiuser DevTools: <b><code>&nbsp;&nbsp;&nbsp;700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [DevTools Remote](https://github.com/auchenberg/devtools-remote)) - Remotely debug someone else's browser.
- <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [DevTools Backend](https://github.com/christian-bromann/devtools-backend)) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
- Python CDP driver: <b><code>&nbsp;&nbsp;&nbsp;649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [pychrome](https://github.com/fate0/pychrome)) - Low-level CDP transport handler.
- <b><code>&nbsp;&nbsp;6202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;481🍴</code></b> [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy)) - Exposes Mobile Safari & UIWebView instances via CDP.
  - <b><code>&nbsp;&nbsp;2740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter)) - Builds on `ios-webkit-debug-proxy` and translates WebKit's Remote Debugging Protocol to CDP.
- <b><code>&nbsp;&nbsp;&nbsp;569⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter)) - Protocol adapter translating IE 11 to CDP.


## Source
<b><code>&nbsp;&nbsp;7158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools))