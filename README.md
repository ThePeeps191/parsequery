# parsequery

a simple program to find query parameters

# usage

## regular version

```html
<script src="https://raw.githubusercontent.com/ThePeeps191/parsequery/main/parsequery.js"></script>
```

## minified

```html
<script src="https://raw.githubusercontent.com/ThePeeps191/parsequery/main/parsequery.min.js"></script>
```

# fetching query parameters

```javascript

// url = https://my-cool-site.com?a=b&hi=there

console.log(parseQuery("a")) // prints "b"

console.log(parseQuery("hi")) // prints "there"
```

# see also

[parsecookie](https://github.com/ThePeeps191/parsecookie)
