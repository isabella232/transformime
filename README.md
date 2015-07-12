# transformime

[![Build Status](https://travis-ci.org/nteract/transformime.svg)](https://travis-ci.org/nteract/transformime)

Transforms MIMEtype+data to HTML Elements

Intended to be used in context of Jupyter and IPython projects, particularly by display areas.

## Installation

```
npm install transformime
```

## Using as a node package

```javascript
> var Transformime = require('transformime').Transformime;
> var transformer = new Transformime();
> var el = transformer.transform("<h1>Woo</h1>", "text/html", document)
> el.innerHTML
'<h1>Woo</h1>'
> el.textContent
'Woo'
```
