# Style guide documentation

## Names and Capitalization

ID and class names should be in lowercase, with words separated by hifen.

```
#my-id
```
```
.my-class
```

HTML elements should be in lowercase.

```
body, div {
```
## Comments

Comments that refer to a closing tag should be on a separate line immediately after the closing tag.

Only C++ style comments are valid for CSS code.

```
// Comment goes here
```
## Fonts

All fonts should be set using rem values.

## Colors

All colors should be set as SASS variables, except for black and white that should be set by the name of the color.

```
color: $dandelion;
```
```
color: white;
```

## Selectors

Selectors should be on a single line, with a space after the last selector, followed by an opening brace. A selector block should end with a closing curly brace that is unindented and on a separate line. A blank line should be placed between each selector block. Selectors should never be indented.

```
selector {
}

selector {
}
```
Multiple selectors should each be on a single line, with no space after each comma.

```
selector1,
selector2,
selector3,
selector4 {
}
```

# Project link

[Beatrice Duncan & Fernanda Thiesen - Project 1](https://fernanda-bea.github.io/project1/)