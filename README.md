# Scroll Behaviour
This is a paper thin wrapper around the existing https://github.com/iamdustan/smoothscroll polyfill.

It allows for importing in nodejs (which does nothing), and automatically calls `smoothscroll.polyfill()` in the browser to make things simpler.

# Installation

#### Npm
```console
npm install scroll-behaviour
```

# Example Manual

```javascript
// commonjs
require('scroll-behaviour').polyfill()

// es6
import { polyfill } 'scroll-behaviour'
polyfill()
```

# Example Automatic

Automatically call `.polyfill()`

```javascript
// commonjs
require('scroll-behaviour/polyfill')

// es6
import 'scroll-behaviour/polyfill'
```

## Browser Support

Successfully tested in:

- Safari 6+
- iOS Safari 6+
- Chrome (last version)
- _natively supported in Firefox_
- Internet Explorer 9+
- Microsoft Edge
- Opera Next

If you have tested this and worked as expected in a different browser let us know so we can add it to the list, if not [open an issue](https://github.com/iamdustan/smoothscroll/issues) providing browser, browser version and a good description about it.

# Standards Documentation

- http://dev.w3.org/csswg/cssom-view
- http://lists.w3.org/Archives/Public/www-style/2013Mar/0314.html
