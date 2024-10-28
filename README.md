# split-innertext-html

A utility to split an HTML element’s text into individual words, characters, and
spaces. Useful for animations and styling.

## Installation

```bash
npm install split-inner-text
```

### Example

```html
<div id="target">A test</div>
```

```javascript
import SplitInnerText from "split-inner-text"

// Select the target element from the DOM.
const element = document.getElementById("target")

// Apply SplitInnerText to the target element.
const splitter = new SplitInnerText(element)

// Access individual elements if needed.
console.log(splitter.words) // NodeList of word wrappers
console.log(splitter.chars) // NodeList of character spans
```
