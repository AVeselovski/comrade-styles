# COMRADE-STYLES

## What is?

**WIP**, please ignore. This is a CSS library / style pattern for use in hobby projects. Not meant for "wider" use.

Strongly influenced by Bootstarp 4, somewhat by Material UI. Everything is very much a work in progress, nothing is decided, nothing is set in stone. A whole new library with almost every major update.

## Why is?

Mainly it's fun to have your own custom tailored CSS-library at your disposal. Convenience and function are secondary (will get there...).

## How is?

Just CSS, no JS. Meant to be used as a base for possible JS Framework integrations, or as is.

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
