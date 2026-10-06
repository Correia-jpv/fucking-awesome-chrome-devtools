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
- [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- [DevTools Tips](https://devtoolstips.org/) - Collection of illustrated tips as mini tutorials.
- [Web cheatcodes](https://codepo8.github.io/web-cheatcodes/) - Browser developer tools for non-developers.
- [Dear Console](https://codepo8.github.io/dearconsole) - A collection of snippets to use in the browser console.
- [Chrome Secret Menus](https://github.com/sparkyrider/chrome-secret-menus) - Comprehensive guide to internal pages and diagnostic tools in Chrome.
- [Front-end Debugging Tools Handbook](https://github.com/lala-hakobyan/front-end-debugging-handbook) - Practical guide to mastering front-end debugging tools, from Chrome DevTools and framework extensions to AI-enhanced IDE debugging.

---

## DevTools tooling and ecosystem

### Timeline, Tracing & Profiling
- [Perfetto](https://github.com/google/perfetto) - System profiling, app tracing, and trace analysis suite ([ui.perfetto.dev](https://ui.perfetto.dev/)) with native support for Chromium traces and SQL-based trace querying.
- [speedscope](https://github.com/jlfwong/speedscope) - Fast, interactive web-based flamegraph viewer that natively imports Chrome `.cpuprofile` and timeline trace files.
- [cpupro](https://github.com/discoveryjs/cpupro) - Interactive viewer and deep analyzer for V8/Chrome `.cpuprofile` logs with flamegraphs, call trees, and hot-spot diagnostics.
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.
- [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile` of the complete (non-sampled) execution. View either time or call counts.

### Chrome Debugger integration with Editors
- [vscode-js-debug](https://github.com/microsoft/vscode-js-debug) - Official DAP-compliant JavaScript and Chrome CDP debugger powering VS Code.
- [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) - Elements panel inside VS Code.

---

## Chrome DevTools Protocol
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types.
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes.
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - Tool for debugging clients using devtools protocol.

### The big two automation libraries
- [Puppeteer](https://github.com/puppeteer/puppeteer) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol. See also [awesome-puppeteer](https://github.com/transitive-bullshit/awesome-puppeteer).
- [Playwright](https://github.com/microsoft/playwright) - Library to automate Chromium, Firefox and WebKit with a single API. Available for Node.js, Python, .Net, Java. See also [awesome-playwright](https://github.com/mxschmitt/awesome-playwright).

### Libraries for driving the protocol (or a layer above)

- JavaScript/Node.js: [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)
- TypeScript/Node.js: [chrome-debugging-client](https://github.com/TracerBench/chrome-debugging-client)
- TypeScript/Node.js: [Taiko](https://github.com/getgauge/taiko/)
- Rust: [chromiumoxide](https://github.com/mattsse/chromiumoxide) - High-level async/tokio CDP library with generated types.
- Rust: [Rust Headless Chrome](https://github.com/rust-headless-chrome/rust-headless-chrome)
- Java: [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
- Java: [jvppeteer](https://github.com/fanyong920/jvppeteer) - Headless Chrome For Java
- Python: [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol) - Pure-Python, sans-IO wrappers. See also the [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
- Python: [pyppeteer](https://github.com/pyppeteer/pyppeteer) - Puppeteer port
- Python: [ChromeController](https://github.com/fake-name/ChromeController) - high-level browser mgmt
- Go: [chromedp](https://github.com/chromedp/chromedp) - High-level actions and tasks for driving browsers
- Go: [cdp](https://github.com/mafredri/cdp)
- Go: [godet](https://github.com/raff/godet)
- Go: [Rod](https://github.com/go-rod/rod)
- C#/.NET: [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp) - Puppeteer port
- C#/.NET: [dotnet-chrome-protocol](https://github.com/seclerp/dotnet-chrome-protocol) - A runtime library and schema code generation tools for Chrome DevTools Protocol support in C#/.NET.
- Ruby: [Ferrum](https://github.com/rubycdp/ferrum) - high-level API to control Chrome in Ruby
- Ruby: [Cuprite](https://github.com/rubycdp/cuprite) - Capybara driver
- Kotlin: [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin) - A coroutine-based client library, providing low-level CDP primitives and high-level extensions.
- Kotlin: [kdriver](https://github.com/cdpdriver/kdriver) - High-level, coroutine-based browser automation built on CDP.
- Clojure: [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- Clojure: [cuic](https://github.com/milankinen/cuic) - Providing a high-level API for UI test automation over the DevTools Protocol.
- PHP: [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - A PHP client library for the protocol.

### Agentic Browser Automation

> **Note to contributors:** We are *extremely* picky about this section. Expect that almost any pull request adding another AI browser wrapper, MCP server, or agent CLI will be rejected unless it has standout community adoption and novel CDP integration.

- [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Official Model Context Protocol (MCP) server for Chrome DevTools.
- [Webcmd](https://github.com/agentrhq/webcmd) - Compiles site navigation into deterministic per-site CLI commands for AI agents.
- [Lumen](https://github.com/omxyz/lumen) - Vision-first browser agent with self-healing deterministic replay over CDP.
- [bdg](https://github.com/szymdzum/browser-debugger-cli) - Persistent background CDP session exposing DOM, network, console, and raw protocol methods as shell commands.


### Browser Adapters
- [devtools-remote-debugger](https://github.com/Nice-PLQ/devtools-remote-debugger) - Use devtools against a webpage; a CDP agent implemeted in client-side JS.
- [Inspect](https://inspect.dev/) - Use devtools against iOS and Android, easily. Browser and Webviews. **(closed source)**


## Using DevTools frontend with other platforms

- [ChromeDevTools/devtools-frontend](https://github.com/ChromeDevTools/devtools-frontend) - Canonical standalone source repository for the Chrome DevTools UI (published to npm as [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend), including the headless [`mcp/mcp.ts`](https://github.com/ChromeDevTools/devtools-frontend/blob/main/mcp/mcp.ts) barrel entrypoint).
- [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Compiles and bundles `devtools-frontend`'s core SDK, `TraceEngine`, `HeapSnapshotModel`, source-map resolver, and insight formatters into a standalone Node.js ESM bundle (`chrome-devtools-mcp/build/src/third_party/index.js`).
- [Chii](https://github.com/liriliri/chii) & [Eruda](https://github.com/liriliri/eruda) - Remote debugging server using the real `devtools-frontend` UI (`Chii`, a modern Weinre replacement) and in-page mobile DevTools console (`Eruda`).
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
- [thetool](https://github.com/sfninja/thetool) - CPU, memory, coverage, type profiling with Node.
- [ruby/debug](https://github.com/ruby/debug) - Debugging functionality for Ruby.
- [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger) - Debugging JavaScript running in [J2V8](https://github.com/eclipsesource/J2V8) with Chrome DevTools.

---

## Applications

### Browsers
- [BrowserBox](https://github.com/BrowserBox/BrowserBox) - Embed Chrome in a web page, largely powered by DevTools and supporting multiuser browsing, remote DevTools, audio, and documents like `.docx`, `.pdf`, and more.

### Web Archivers and Indexers
- [dn](https://github.com/DO-SAY-GO/tdf) - Archive and index pages you browse for offline viewing and search, implemented using the `Fetch` domain's interceptions, and works with any Chromium-based browser.
  
---

## DevTools Extensions

### Workflow
- [Clockwork](https://chromewebstore.google.com/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- [RailsPanel](https://chromewebstore.google.com/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [Ember.js Inspector](https://chromewebstore.google.com/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect Ember.js objects in your application.
- [Vue.js Developer Tools](https://github.com/vuejs/devtools) - Inspect Vue.js components and manipulate their data.
- [Angular DevTools](https://chromewebstore.google.com/detail/angular-devtools/ienfalfjdbdpebioblfackkekamfmbnh) - Debugging and Profiling for Angular applications.
- [Redux Devtools](https://chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- [Web Component DevTools](https://chromewebstore.google.com/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify and observe Web Components on page.

### Performance
- [TracerBench](https://github.com/TracerBench/tracerbench) - A controlled performance benchmarking tool for web applications, providing clear, actionable and usable insights into performance deltas.

### Automation
- [Puppeteer IDE](https://github.com/gajananpp/puppeteer-ide-extension) - Standalone Puppeteer playground in browser's developer tools.

## Alumni
Old projects, likely not maintained any longer… But still cool.

- [ndb](https://github.com/GoogleChromeLabs/ndb) - An improved Node.js debugging experience with the DevTools Frontend.
- [Facebook Stetho](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools.
- [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools.
- [betwixt](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel.
- [Dirac](https://github.com/binaryage/dirac) - Debugging of ClojureScript with a custom DevTools fork.
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - Breakpoint debugging in VS Code (superseded by built-in [vscode-js-debug](https://github.com/microsoft/vscode-js-debug), which has a rich CDP/DAP implementation).
- [noice-json-rpc](https://github.com/nojvek/noice-json-rpc) - A proxy-based TypeScript/JS implementation exposing the CDP as its API.
- [PuPHPeteer](https://github.com/rialto-php/puphpeteer) - PHP bridge to Node Puppeteer.
- [Insight](https://github.com/3Dparallax/insight/) - A WebGL debugging toolkit for Chrome DevTools.
- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once.  
   - Multiuser DevTools: [DevTools Remote](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser.
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
- Python CDP driver: [pychrome](https://github.com/fate0/pychrome) - low level CDP transport handler
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP.
  - [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP.
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 11 to CDP.

