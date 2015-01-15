# Polymer theme

Polymer theme using [Sass](http://sass-lang.com) and [Material Design](http://www.google.com/design/).

For scaffolding Polymer apps use [Yeoman generator](https://github.com/yeoman/generator-polymer).

## Dependencies

- [Sass Material Colors](https://github.com/minusfive/sass-material-colors)

## Installation

### Bower Component

```
bower install polymer-theme --save
```

## Usage

### main.scss

```
// Local copy of _variables.scss
@import 'variables';

.polymer-theme {
  @import '../bower_components/polymer-theme/sass/polymer-theme';
}
```

### index.html

```
<body class="polymer-theme">
```

## Variables

[_variables.scss](https://github.com/StartPolymer/polymer-theme/sass/_variables.scss)
