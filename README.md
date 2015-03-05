# Polymer Theme

Polymer theme based on
[Material Design](http://www.google.com/design/spec/material-design/introduction.html) language.

For scaffolding Polymer apps use [Polymer Starter Kit](https://github.com/StartPolymer/polymer-starter-kit)
or [Polymer generator](https://github.com/yeoman/generator-polymer).

:sparkles: [DEMO](http://polymer-starter-kit.startpolymer.org) :sparkles:

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
$heading-font-name:       'roboto-slab';
$font-lang:               'en';
@import 'bower_components/polymer-theme/sass/fonts';

.polymer-theme {
  $primary-color-name:    'indigo';
  $secondary-color-name:  'pink';
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
$primary-color-name:      'indigo';
$secondary-color-name:    'pink';
```

### Roboto Font Combinations

- [Link to module](https://github.com/StartPolymer/polymer-theme/blob/master/sass/modules/roboto-fonts.scss)

```scss
$heading-font-name:       'roboto-slab';
$font-lang:               'en';
```

## Contributing :+1:

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make your changes
4. Run the tests, adding new ones for your own code if necessary
5. Commit your changes (`git commit -am 'Added some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create new Pull Request

## [MIT License](https://github.com/StartPolymer/polymer-theme/blob/master/LICENSE)

Copyright (c) 2015 Start Polymer ([http://startpolymer.org](http://startpolymer.org))
