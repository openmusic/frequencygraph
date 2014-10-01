# openmusic-frequencygraph

> A component for plotting wave data on a canvas

** YOU NEED SUPPORT FOR WEB COMPONENTS IN YOUR BROWSER BECAUSE WE'RE NOT SHIMMING ANYTHING IN **

Firefox: go to `about:config`, find `dom.webcomponents.enabled` and set it to true.

Chrome: maybe nothing to do?

## Installation

Just grab `FrequencyGraph.js` from the repo or do `npm install openmusic-frequencygraph`.

## Usage

### If not using any package manager

Just include `FrequencyGraph.js` before you use the component. It will be registered automatically as `openmusic-frequencygraph` so you can `document.createElement('openmusic-frequencygraph')` or just have `<openmusic-frequencygraph>` elements in your HTML source.

### If using npm

You need to load the module and then register it--it is not automatically registered!

```javascript
require('openmusic-frequencygraph').register('openmusic-frequencygraph');
```

But you could even register it with other name. Up to you.


