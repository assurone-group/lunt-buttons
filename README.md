# lunt-buttons
Button components for the Lunt framework.

```css
/* Basic properties */
.Btn {}

/* Visual properties for primary button*/
.Btn--primary {}
```
```html
<input class="Btn Btn--primary" type="submit" name="name" value="Input submit">
<span class="Btn Btn--primary">Span button</span>
```
## Installation

    npm install lunt-buttons --save

## Usage

You can use this component the way you want. It's just a Node.js module with a little bit of CSS.

### 1. In your CSS file

    @import "../node_modules/lunt-buttons/lunt-buttons.css"

You can also use [postcss-import](https://github.com/postcss/postcss-import) plugin to make it even easier.

### 2. In your Node.js modules

    var luntBoxSizing = require('lunt-buttons');
