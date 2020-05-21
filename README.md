# COMRADE-STYLES

## What is?

This is just a "simple" CSS library for use in my own projects. Please ignore.

Somewhat influenced by Botstrap 4.

## Why is?

For fun & learning, mostly. It's fun to have your own custom tailored CSS-library at your disposal. Also to hopefully save time with "bootstrapping" new projects UI.

## Installation

`npm install comrade-styles`

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
