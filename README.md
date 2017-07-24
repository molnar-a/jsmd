# Jsmd
A Markdown parser written in JavaScript ES6.  
Uses regular expressions internally.

## Adding

    <script src="jsmd.min.js"></script>

## Usage

```javascript
jsmd("_FAGN_ [__SHIT__](http://www.google.com)") // <p><i>FAGN</i> <a href='http://www.google.com'><b>SHIT</b></a></p>
```

## Why?
Because all the other parsers are fagn huge  
The price to pay is the speed, it's not that good considering all those regexes
