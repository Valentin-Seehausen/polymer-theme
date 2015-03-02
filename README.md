# Polymer Theme

Polymer theme based on
[Material Design](http://www.google.com/design/spec/material-design/introduction.html) language.

For scaffolding Polymer apps use [Polymer Starter Kit](https://github.com/StartPolymer/polymer-starter-kit)
or [Polymer generator](https://github.com/yeoman/generator-polymer).

## Features

- Using [Sass](http://sass-lang.com) CSS Preprocessor
- [Material Design Colors](http://www.google.com/design/spec/style/color.html#color-color-palette)
- [Roboto Font Combinations](https://github.com/StartPolymer/polymer-theme/wiki/Roboto-Font-Combinations)

## Installation

```sh
bower install polymer-theme --save
```

## Usage

### main.scss

```scss
$primary-color-name:    'indigo';
$accent-color-name:     'pink';

$heading-font-name:     'roboto-slab';
$font-lang:             'en';

@import 'bower_components/polymer-theme/sass/variables';
@import url($font-url);

.polymer-theme {
  @import 'bower_components/polymer-theme/sass/base';
}
```

### index.html

```html
<body class="polymer-theme">
```

## [Variables](https://github.com/StartPolymer/polymer-theme/blob/master/sass/variables.scss)

### Material Design Colors

- [Link to module](https://github.com/StartPolymer/polymer-theme/blob/master/sass/modules/material-colors.scss)

```scss
$primary-color-name:    'indigo';
$accent-color-name:     'pink';
```

### Roboto Font Combinations

- [Link to module](https://github.com/StartPolymer/polymer-theme/blob/master/sass/modules/roboto-fonts.scss)

```scss
$heading-font-name:     'roboto-slab';
$font-lang:             'en';
```

## [MIT License](https://github.com/StartPolymer/polymer-theme/blob/master/LICENSE)

Copyright (c) 2015 Start Polymer ([http://startpolymer.org](http://startpolymer.org))
