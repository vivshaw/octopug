# octopug :dog:
Pug mixin for a [tholman-style GitHub corner](http://tholman.com/github-corners/)! Now you can add one to your pages as easy as `npm install`.

All credit for the awesome GitHub corner design goes of course to its creator, [Tim Holman](https://github.com/tholman). I merely Pugified it, wrapped it in a mixin, and set it up for npm deployment.

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
