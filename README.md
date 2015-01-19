# Polymer theme

Polymer theme using [Sass](http://sass-lang.com) and [Material Design](http://www.google.com/design/).

For scaffolding Polymer apps use [Yeoman generator](https://github.com/yeoman/generator-polymer).

## Installation

### Bower Component

```
bower install polymer-theme --save
```

## Usage

### main.scss

```
// Make copy of _variables.scss and place to styles dir
@import 'variables';

.polymer-theme {
  @import '../bower_components/polymer-theme/sass/base';
}
```

### index.html

```
<body class="polymer-theme">
```

## [Variables](https://github.com/StartPolymer/polymer-theme/blob/master/sass/_variables.scss)

```scss
// Roboto Font Combinations
$font-name:             'alegreya';
$font-lang:             'en';

// Material Design Colors
$primary-color-name:    'indigo';
$accent-color-name:     'pink';
```
