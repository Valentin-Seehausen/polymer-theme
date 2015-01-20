# Polymer Theme

Polymer theme using [Sass](http://sass-lang.com) and [Material Design](http://www.google.com/design/).

For scaffolding Polymer apps use [Polymer Base Template](https://github.com/StartPolymer/polymer-base-template).

## Installation

### Bower Component

```sh
bower install polymer-theme --save
```

## Usage

### main.scss

```scss
@import '../bower_components/polymer-theme/sass/modules/all';

.polymer-theme {
  // Make copy of ../bower_components/polymer-theme/sass/_variables.scss to styles dir
  @import 'variables';

  @import '../bower_components/polymer-theme/sass/theme';

  /deep/ {
    @import '../bower_components/polymer-theme/sass/elements/all';
  }
}
```

### index.html

```html
<body class="polymer-theme">
```

## [Variables](https://github.com/StartPolymer/polymer-theme/blob/master/sass/_variables.scss)

### [Material Design Colors](https://github.com/StartPolymer/polymer-theme/blob/master/sass/modules/_material-colors.scss)

- [Link to source](http://www.google.com/design/spec/style/color.html#color-color-palette)

```scss
$primary-color-name:    'indigo';
$accent-color-name:     'pink';
```

### [Roboto Font Combinations](https://github.com/StartPolymer/polymer-theme/blob/master/sass/modules/_roboto-fonts.scss)

- [Link to source](https://gist.github.com/8faa215aca23696a3e3c)

```scss
$font-name:             'alegreya';
$font-lang:             'en';
```
