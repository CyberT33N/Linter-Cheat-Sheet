# Linter Cheat Sheet
Linter Cheat Sheet with the most needed stuff..


<br><br>

# ESLint
- https://eslint.org/docs/user-guide/getting-started

## Install

```bash
npm i -g eslint

# cd into your project
eslint --init # will create .eslintrc.yml
```

#### Atom
https://atom.io/packages/linter-eslint (https://www.youtube.com/watch?v=dG9EEkSCbWM)

<br><br>

## Rules
- https://eslint.org/docs/rules/


#### Disable Rules
```yaml
rules:
  arrow-parens: off
``` 
<br><br>

#### arrow-parens
https://eslint.org/docs/rules/arrow-parens
```javascript
// Bad
(a) => {}

// Good
a => {}
```

<br>

#### no-multiple-empty-lines
https://eslint.org/docs/rules/no-multiple-empty-lines
```javascript
/*eslint no-multiple-empty-lines: "error"*/

var foo = 5;



var bar = 3;
```

<br>

#### brace-style
https://eslint.org/docs/rules/brace-style
```javascript
// Good
if (foo) {
  bar();
} else {
  baz();
}

// Bad
if (foo) { bar(); }
else { baz(); }
```

<br>

#### require-jsdoc
https://eslint.org/docs/rules/require-jsdoc
```javascript
/**
 * Adds two numbers together.
 * @param {int} num1 The first number.
 * @param {int} num2 The second number.
 * @returns {int} The sum of the two numbers.
 */
function sum(num1, num2) {
    return num1 + num2;
}
```
