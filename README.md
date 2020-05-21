# COMRADE-STYLES

## What is?

This is a CSS library for use in my own projects. WIP, please ignore.

Somewhat influenced by Botstrap 4, somewhat by Material UI.

## Why is?

Mainly it's fun to have your own custom tailored CSS-library at your disposal. Eventually, to save time "bootstrapping" new projects UI.

## Installation

`yarn add comrade-styles`

## Usage

Import in project's _SCSS_ to get access to variables:

```scss
@import "~comrade-styles/scss/comrade";
```

Place desired variable overrides _before_ above import.

#### OR

If no need for variables, just import compiled _CSS_:

```js
import "comrade-styles";
// OR
require("comrade-styles");
```

#### Variables for theming are located here:

`scss/utils/_config.scss`
