# ios-color

[iOS built-in colors](https://developer.apple.com/design/human-interface-guidelines/color) defined as CSS variables.

## Usage

Usage pre-defined variables in modern browsers or with transforming tools like PostCSS.

```css
@import "ios-color";

body {
  color: var(--label);
  background-color: var(--system-background);
}

a {
  color: var(--system-blue);
}
```

## Install

### NPM

```bash
npm install ios-color
```

### Yarn

```bash
yarn add ios-color
```

## License

Copyright © 2023 Jianqiu Xiao swordray@gmail.com under The [MIT License](http://opensource.org/licenses/MIT).
