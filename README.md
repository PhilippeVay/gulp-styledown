
gulp-styledown
===

A gulp plugin for Styledown (its fork found at [@philippevay/styledown](https://www.npmjs.com/package/@philippevay/gulp-styledown)).


Quick Start
---

```js
var styledown = require('@philippevay/gulp-styledown');

gulp.src('/path/to/styledown/*.md')
.pipe(styledown({
  config: '/path/to/config.md'
  filename: 'output.html'
}))
.pipe(gulp.dest('/path/to/'));
```

Options
---

- config : Path to config.md
- filename : Path to output html

Other options are pass to [styledown](https://github.com/PhilippeVay/styledown).
