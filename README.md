# Revert User Agent Stylesheet

## Usage

With [Dart Sass](https://github.com/sass/dart-sass):

```scss
@use 'revert-ua-styles' as revert;

body {
  @include revert.ua-style(body);
}
```

```css
body {
  margin: 0;
}
```

## API

### Sass mixins

- `ua-style($element, $support-ie11: false)`
- `initial-value($property, $support-ie11: false)`
