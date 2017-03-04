# octopug
Pug mixin for a @tholman-style GitHub corner

## Usage
```
npm install --save octopug
```
Then add to whichever Pug file you want it on:

```
include /node_modules/octopug/octopug.pug
+octopug('https://github.com/YOUR-REPO-HERE', bgColor, catColor)
```

`bgColor` & `catColor` should be strings containing a CSS color.
`bgColor` defaults to `'#000'`, catColor defaults to `'#fff'`.
